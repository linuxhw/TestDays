Linux in Iran - Tested Hardware & Statistics
--------------------------------------------

A project to collect tested hardware configurations for Linux in Iran.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Iran/Desktop/README.md) and [notebooks](/Location/Iran/Notebook/README.md).

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

Total: 837

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [63c110632a](https://linux-hardware.org/?probe=63c110632a) | Jun 10, 2023 |
| Dell          | Latitude E5470              | Notebook    | [c9b909273b](https://linux-hardware.org/?probe=c9b909273b) | Jun 09, 2023 |
| Biostar       | A68N-2100K                  | Desktop     | [9ac86a512d](https://linux-hardware.org/?probe=9ac86a512d) | Jun 09, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [262ee566e1](https://linux-hardware.org/?probe=262ee566e1) | Jun 06, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [b6613930a2](https://linux-hardware.org/?probe=b6613930a2) | Jun 05, 2023 |
| ASUSTek       | X540UP                      | Notebook    | [5102ecc266](https://linux-hardware.org/?probe=5102ecc266) | Jun 04, 2023 |
| Sony          | VPCEA45FG                   | Notebook    | [873ca04445](https://linux-hardware.org/?probe=873ca04445) | May 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [c2125f60d2](https://linux-hardware.org/?probe=c2125f60d2) | May 28, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [8e5402cb16](https://linux-hardware.org/?probe=8e5402cb16) | May 24, 2023 |
| Lenovo        | IdeaPadFlex 5-1570 80XB     | Convertible | [9e2f0c46ef](https://linux-hardware.org/?probe=9e2f0c46ef) | May 20, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | Desktop     | [061e1e2aec](https://linux-hardware.org/?probe=061e1e2aec) | May 19, 2023 |
| Lenovo        | ThinkPad T440p 20AWS0GK0... | Notebook    | [177f30243c](https://linux-hardware.org/?probe=177f30243c) | May 08, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [2cbff804d8](https://linux-hardware.org/?probe=2cbff804d8) | May 08, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [728b1e3209](https://linux-hardware.org/?probe=728b1e3209) | May 03, 2023 |
| Toshiba       | Satellite C640              | Notebook    | [20d436bfa7](https://linux-hardware.org/?probe=20d436bfa7) | May 02, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [9a43268d9b](https://linux-hardware.org/?probe=9a43268d9b) | May 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [5086f7f4a2](https://linux-hardware.org/?probe=5086f7f4a2) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [dd0a47b6fc](https://linux-hardware.org/?probe=dd0a47b6fc) | May 01, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [7087295cd7](https://linux-hardware.org/?probe=7087295cd7) | May 01, 2023 |
| ASUSTek       | H110-PLUS                   | Desktop     | [f8317bce7b](https://linux-hardware.org/?probe=f8317bce7b) | Apr 26, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [e37aab534f](https://linux-hardware.org/?probe=e37aab534f) | Apr 24, 2023 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | Notebook    | [a8644a5b03](https://linux-hardware.org/?probe=a8644a5b03) | Apr 23, 2023 |
| Sony          | VGN-SZ640N                  | Notebook    | [659b01c666](https://linux-hardware.org/?probe=659b01c666) | Apr 21, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c10e38e18e](https://linux-hardware.org/?probe=c10e38e18e) | Apr 20, 2023 |
| Toshiba       | Satellite A100              | Notebook    | [f95e411124](https://linux-hardware.org/?probe=f95e411124) | Apr 20, 2023 |
| HP            | ZBook 15                    | Notebook    | [c5397a7fbb](https://linux-hardware.org/?probe=c5397a7fbb) | Apr 14, 2023 |
| HP            | ZBook 15                    | Notebook    | [aaaa838a8f](https://linux-hardware.org/?probe=aaaa838a8f) | Apr 13, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [110fdee9b2](https://linux-hardware.org/?probe=110fdee9b2) | Apr 10, 2023 |
| Lenovo        | ThinkPad T420 4178A4G       | Notebook    | [206861226d](https://linux-hardware.org/?probe=206861226d) | Apr 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9e7e969310](https://linux-hardware.org/?probe=9e7e969310) | Apr 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [a64c365f62](https://linux-hardware.org/?probe=a64c365f62) | Apr 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [0a028a43f8](https://linux-hardware.org/?probe=0a028a43f8) | Apr 01, 2023 |
| ASUSTek       | X555BP                      | Notebook    | [c7f621e335](https://linux-hardware.org/?probe=c7f621e335) | Apr 01, 2023 |
| ASUSTek       | PRIME H370-PLUS             | Desktop     | [4a7e7763c1](https://linux-hardware.org/?probe=4a7e7763c1) | Mar 28, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [54f096fd88](https://linux-hardware.org/?probe=54f096fd88) | Mar 27, 2023 |
| ASUSTek       | K54HR                       | Notebook    | [ac6cf948d5](https://linux-hardware.org/?probe=ac6cf948d5) | Mar 27, 2023 |
| YANYU         | ITX-S192                    | Desktop     | [0d2fb6a8d7](https://linux-hardware.org/?probe=0d2fb6a8d7) | Mar 27, 2023 |
| Gigabyte      | G31M-ES2C                   | Desktop     | [fcd077e70a](https://linux-hardware.org/?probe=fcd077e70a) | Mar 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [fe79f70952](https://linux-hardware.org/?probe=fe79f70952) | Mar 27, 2023 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [e4a88fa14e](https://linux-hardware.org/?probe=e4a88fa14e) | Mar 27, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [30e77255e4](https://linux-hardware.org/?probe=30e77255e4) | Mar 20, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [95ae633abb](https://linux-hardware.org/?probe=95ae633abb) | Mar 19, 2023 |
| Lenovo        | IdeaPad L3 15IML05 81Y3     | Notebook    | [54025a10f5](https://linux-hardware.org/?probe=54025a10f5) | Mar 19, 2023 |
| ASUSTek       | X550LC                      | Notebook    | [5f73fa5db7](https://linux-hardware.org/?probe=5f73fa5db7) | Mar 18, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [51ec4d252f](https://linux-hardware.org/?probe=51ec4d252f) | Mar 17, 2023 |
| ASUSTek       | P5P43TD                     | Desktop     | [f2be993036](https://linux-hardware.org/?probe=f2be993036) | Mar 13, 2023 |
| Toshiba       | PORTEGE X30-D               | Notebook    | [9b7e4e10af](https://linux-hardware.org/?probe=9b7e4e10af) | Mar 12, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [5e4e9bde6f](https://linux-hardware.org/?probe=5e4e9bde6f) | Mar 03, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [7f72d6bba7](https://linux-hardware.org/?probe=7f72d6bba7) | Feb 26, 2023 |
| Gigabyte      | G41MT-S2                    | Desktop     | [d81c35b55b](https://linux-hardware.org/?probe=d81c35b55b) | Feb 25, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [6d36ab1fcf](https://linux-hardware.org/?probe=6d36ab1fcf) | Feb 24, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [0a1b4d8122](https://linux-hardware.org/?probe=0a1b4d8122) | Feb 23, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [72f074b930](https://linux-hardware.org/?probe=72f074b930) | Feb 19, 2023 |
| ASUSTek       | ROG Strix G733ZW_G733ZW     | Notebook    | [c6d06c27c7](https://linux-hardware.org/?probe=c6d06c27c7) | Feb 19, 2023 |
| Lenovo        | Z50-70 20354                | Notebook    | [3932889971](https://linux-hardware.org/?probe=3932889971) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f6276d350a](https://linux-hardware.org/?probe=f6276d350a) | Feb 08, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [1b800ff8c2](https://linux-hardware.org/?probe=1b800ff8c2) | Feb 07, 2023 |
| ASUSTek       | PRIME H610M-A WIFI D4       | Desktop     | [69f96bffa5](https://linux-hardware.org/?probe=69f96bffa5) | Feb 07, 2023 |
| MSI           | S12T 3M/S12 3M              | Notebook    | [787543930a](https://linux-hardware.org/?probe=787543930a) | Feb 07, 2023 |
| Acer          | Aspire VN7-592G             | Notebook    | [a313fa3b83](https://linux-hardware.org/?probe=a313fa3b83) | Feb 02, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [e64a1e0a5a](https://linux-hardware.org/?probe=e64a1e0a5a) | Jan 31, 2023 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [4427845ac1](https://linux-hardware.org/?probe=4427845ac1) | Jan 30, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [2b2401b0f0](https://linux-hardware.org/?probe=2b2401b0f0) | Jan 28, 2023 |
| ASUSTek       | ZenBook UX434IQ_UM433IQ     | Notebook    | [17b4a2466c](https://linux-hardware.org/?probe=17b4a2466c) | Jan 20, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [8474e8ce69](https://linux-hardware.org/?probe=8474e8ce69) | Jan 17, 2023 |
| HP            | 805A                        | Desktop     | [4061c209e2](https://linux-hardware.org/?probe=4061c209e2) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [dcbf101b59](https://linux-hardware.org/?probe=dcbf101b59) | Jan 17, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [3964c82d71](https://linux-hardware.org/?probe=3964c82d71) | Jan 17, 2023 |
| ASUSTek       | X550VX                      | Notebook    | [b325ae9a48](https://linux-hardware.org/?probe=b325ae9a48) | Jan 11, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [268f34635a](https://linux-hardware.org/?probe=268f34635a) | Dec 28, 2022 |
| HIGRADED      | W651UI                      | Notebook    | [66d9d484cd](https://linux-hardware.org/?probe=66d9d484cd) | Dec 27, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [d70aca4ad6](https://linux-hardware.org/?probe=d70aca4ad6) | Dec 24, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6d43b6afd](https://linux-hardware.org/?probe=a6d43b6afd) | Dec 22, 2022 |
| ASUSTek       | PRIME B250-PLUS             | Desktop     | [4d24d45918](https://linux-hardware.org/?probe=4d24d45918) | Dec 21, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [01ba4c7b4a](https://linux-hardware.org/?probe=01ba4c7b4a) | Dec 16, 2022 |
| Acer          | Predator PH315-55           | Notebook    | [e2297c201d](https://linux-hardware.org/?probe=e2297c201d) | Dec 16, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [d1342c521a](https://linux-hardware.org/?probe=d1342c521a) | Dec 15, 2022 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5c0099832f](https://linux-hardware.org/?probe=5c0099832f) | Dec 15, 2022 |
| HP            | Pavilion g6                 | Notebook    | [1120db45a3](https://linux-hardware.org/?probe=1120db45a3) | Dec 13, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [df78e85dfe](https://linux-hardware.org/?probe=df78e85dfe) | Dec 08, 2022 |
| Acer          | Aspire A315-56              | Notebook    | [a1ec8cb1b2](https://linux-hardware.org/?probe=a1ec8cb1b2) | Nov 29, 2022 |
| HP            | 3397                        | Desktop     | [e264b68f30](https://linux-hardware.org/?probe=e264b68f30) | Nov 27, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [89ec4e86f7](https://linux-hardware.org/?probe=89ec4e86f7) | Nov 26, 2022 |
| HPE           | ProLiant DL380 Gen10        | Server      | [4cdcad1148](https://linux-hardware.org/?probe=4cdcad1148) | Nov 24, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2c8a884430](https://linux-hardware.org/?probe=2c8a884430) | Nov 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [451d2e210d](https://linux-hardware.org/?probe=451d2e210d) | Nov 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [51809e1ff3](https://linux-hardware.org/?probe=51809e1ff3) | Nov 11, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [f8cd836199](https://linux-hardware.org/?probe=f8cd836199) | Nov 10, 2022 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [db0a79fbd9](https://linux-hardware.org/?probe=db0a79fbd9) | Nov 07, 2022 |
| Lenovo        | G50-70 20351                | Notebook    | [0d4536a010](https://linux-hardware.org/?probe=0d4536a010) | Nov 07, 2022 |
| ASUSTek       | H97-PLUS                    | Desktop     | [f22f67754e](https://linux-hardware.org/?probe=f22f67754e) | Oct 29, 2022 |
| MSI           | Modern 15 A10RBS            | Notebook    | [ddc3eded89](https://linux-hardware.org/?probe=ddc3eded89) | Oct 28, 2022 |
| HP            | G62                         | Notebook    | [a7b5ac8e19](https://linux-hardware.org/?probe=a7b5ac8e19) | Oct 20, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [6459e3fedb](https://linux-hardware.org/?probe=6459e3fedb) | Oct 16, 2022 |
| MSI           | Modern 15 A5M               | Notebook    | [5192a80499](https://linux-hardware.org/?probe=5192a80499) | Oct 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [d844ce4115](https://linux-hardware.org/?probe=d844ce4115) | Oct 13, 2022 |
| HP            | G62                         | Notebook    | [dbe9a778bb](https://linux-hardware.org/?probe=dbe9a778bb) | Oct 12, 2022 |
| Lenovo        | ThinkPad T420 42361L0       | Notebook    | [abe6563e67](https://linux-hardware.org/?probe=abe6563e67) | Sep 30, 2022 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [77b578f861](https://linux-hardware.org/?probe=77b578f861) | Sep 23, 2022 |
| ASUSTek       | UX490UA                     | Notebook    | [e953c29d50](https://linux-hardware.org/?probe=e953c29d50) | Sep 19, 2022 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [d8be5e602a](https://linux-hardware.org/?probe=d8be5e602a) | Sep 19, 2022 |
| ASUSTek       | H110M-K                     | Desktop     | [a15d189c98](https://linux-hardware.org/?probe=a15d189c98) | Sep 17, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [0737d49df2](https://linux-hardware.org/?probe=0737d49df2) | Sep 15, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [968826d76c](https://linux-hardware.org/?probe=968826d76c) | Sep 13, 2022 |
| ASUSTek       | K56CB                       | Notebook    | [8718c2bb09](https://linux-hardware.org/?probe=8718c2bb09) | Sep 12, 2022 |
| Acer          | Aspire V3-571G              | Notebook    | [33c08b8aef](https://linux-hardware.org/?probe=33c08b8aef) | Sep 09, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [c803fe67f3](https://linux-hardware.org/?probe=c803fe67f3) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | Desktop     | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [c98348c9a3](https://linux-hardware.org/?probe=c98348c9a3) | Sep 07, 2022 |
| ASUSTek       | PRIME A320M-C R2.0          | Desktop     | [7649a53341](https://linux-hardware.org/?probe=7649a53341) | Sep 06, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [68b6da5fe1](https://linux-hardware.org/?probe=68b6da5fe1) | Sep 04, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [349fc1d85c](https://linux-hardware.org/?probe=349fc1d85c) | Sep 03, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f0d85f4991](https://linux-hardware.org/?probe=f0d85f4991) | Sep 03, 2022 |
| Lenovo        | G50-80 80E5                 | Notebook    | [ec5bb450ff](https://linux-hardware.org/?probe=ec5bb450ff) | Sep 01, 2022 |
| ASUSTek       | X550ZE                      | Notebook    | [187a6feadf](https://linux-hardware.org/?probe=187a6feadf) | Sep 01, 2022 |
| ASUSTek       | E202SA                      | Notebook    | [393cb25da2](https://linux-hardware.org/?probe=393cb25da2) | Aug 30, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [c96e8a8254](https://linux-hardware.org/?probe=c96e8a8254) | Aug 30, 2022 |
| ASUSTek       | N61Jv                       | Notebook    | [a8b586b903](https://linux-hardware.org/?probe=a8b586b903) | Aug 27, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [93ac400083](https://linux-hardware.org/?probe=93ac400083) | Aug 23, 2022 |
| ASUSTek       | H61M-C                      | Desktop     | [8d187f0a28](https://linux-hardware.org/?probe=8d187f0a28) | Aug 22, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [c8f8e78df8](https://linux-hardware.org/?probe=c8f8e78df8) | Aug 17, 2022 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fa12e95e32](https://linux-hardware.org/?probe=fa12e95e32) | Aug 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [a36a32eb0e](https://linux-hardware.org/?probe=a36a32eb0e) | Aug 10, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [759c9dee6b](https://linux-hardware.org/?probe=759c9dee6b) | Aug 09, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [1636ef38d5](https://linux-hardware.org/?probe=1636ef38d5) | Aug 09, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [114ada270e](https://linux-hardware.org/?probe=114ada270e) | Aug 08, 2022 |
| ASUSTek       | H110M-C/PS                  | Desktop     | [b633163f9f](https://linux-hardware.org/?probe=b633163f9f) | Aug 06, 2022 |
| ASUSTek       | 1015CX                      | Notebook    | [f8d358f521](https://linux-hardware.org/?probe=f8d358f521) | Aug 05, 2022 |
| Timi          | RedmiBook 14                | Notebook    | [10c33f11cf](https://linux-hardware.org/?probe=10c33f11cf) | Aug 02, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0851479f6b](https://linux-hardware.org/?probe=0851479f6b) | Aug 01, 2022 |
| Lenovo        | ThinkPad P17 Gen 2i 20YU... | Notebook    | [9996781aa7](https://linux-hardware.org/?probe=9996781aa7) | Jul 29, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [be9941b639](https://linux-hardware.org/?probe=be9941b639) | Jul 28, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [56faf89859](https://linux-hardware.org/?probe=56faf89859) | Jul 28, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [117f3d3969](https://linux-hardware.org/?probe=117f3d3969) | Jul 26, 2022 |
| Gigabyte      | H61M-D2P-B3                 | Desktop     | [8f0769b485](https://linux-hardware.org/?probe=8f0769b485) | Jul 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb442470d4](https://linux-hardware.org/?probe=fb442470d4) | Jul 24, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [6f2adb5629](https://linux-hardware.org/?probe=6f2adb5629) | Jul 24, 2022 |
| ASUSTek       | X555LD                      | Notebook    | [bc783f5d64](https://linux-hardware.org/?probe=bc783f5d64) | Jul 23, 2022 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [e632ef83da](https://linux-hardware.org/?probe=e632ef83da) | Jul 20, 2022 |
| HP            | G62                         | Notebook    | [bcb07d1cc9](https://linux-hardware.org/?probe=bcb07d1cc9) | Jul 16, 2022 |
| HP            | G62                         | Notebook    | [020a13b927](https://linux-hardware.org/?probe=020a13b927) | Jul 16, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [4e8aa38fb4](https://linux-hardware.org/?probe=4e8aa38fb4) | Jul 11, 2022 |
| Acer          | Nitro AN515-55              | Notebook    | [85845c3282](https://linux-hardware.org/?probe=85845c3282) | Jul 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1a03301817](https://linux-hardware.org/?probe=1a03301817) | Jul 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [859145be97](https://linux-hardware.org/?probe=859145be97) | Jul 02, 2022 |
| ASUSTek       | N43JQ                       | Notebook    | [d73f714472](https://linux-hardware.org/?probe=d73f714472) | Jul 01, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [97613877b7](https://linux-hardware.org/?probe=97613877b7) | Jun 29, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [56e348118b](https://linux-hardware.org/?probe=56e348118b) | Jun 26, 2022 |
| HP            | 3397                        | Desktop     | [337e956c95](https://linux-hardware.org/?probe=337e956c95) | Jun 22, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [43cf14bdd7](https://linux-hardware.org/?probe=43cf14bdd7) | Jun 22, 2022 |
| HP            | EliteBook 8440p             | Notebook    | [4bea8264d3](https://linux-hardware.org/?probe=4bea8264d3) | Jun 20, 2022 |
| ASUSTek       | X542UN                      | Notebook    | [83a04b4dc4](https://linux-hardware.org/?probe=83a04b4dc4) | Jun 17, 2022 |
| Gigabyte      | H510M H                     | Desktop     | [7b1a78a681](https://linux-hardware.org/?probe=7b1a78a681) | Jun 11, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [2893254eb3](https://linux-hardware.org/?probe=2893254eb3) | Jun 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [e64a2a0eeb](https://linux-hardware.org/?probe=e64a2a0eeb) | Jun 10, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b0e13d9a94](https://linux-hardware.org/?probe=b0e13d9a94) | Jun 05, 2022 |
| ASUSTek       | X550JX                      | Notebook    | [05094a5491](https://linux-hardware.org/?probe=05094a5491) | Jun 05, 2022 |
| Lenovo        | ThinkPad E420 1141E9G       | Notebook    | [48b5588cbd](https://linux-hardware.org/?probe=48b5588cbd) | Jun 01, 2022 |
| ASUSTek       | Maximus II Formula          | Desktop     | [84df720c51](https://linux-hardware.org/?probe=84df720c51) | May 30, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [27dffb7089](https://linux-hardware.org/?probe=27dffb7089) | May 29, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a4d6e798d](https://linux-hardware.org/?probe=8a4d6e798d) | May 26, 2022 |
| Toshiba       | Satellite Pro T130          | Notebook    | [2771a53784](https://linux-hardware.org/?probe=2771a53784) | May 23, 2022 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [232b74e86b](https://linux-hardware.org/?probe=232b74e86b) | May 17, 2022 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [1bce5b14e3](https://linux-hardware.org/?probe=1bce5b14e3) | May 17, 2022 |
| MSI           | 760GM-P33                   | Desktop     | [d37fca6b00](https://linux-hardware.org/?probe=d37fca6b00) | May 17, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [247fc8ed78](https://linux-hardware.org/?probe=247fc8ed78) | May 16, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [a0c15e2a2f](https://linux-hardware.org/?probe=a0c15e2a2f) | May 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [8a9646dc78](https://linux-hardware.org/?probe=8a9646dc78) | May 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [b6cb96e1d0](https://linux-hardware.org/?probe=b6cb96e1d0) | May 13, 2022 |
| ASUSTek       | X580VD                      | Notebook    | [1d71c877c7](https://linux-hardware.org/?probe=1d71c877c7) | May 13, 2022 |
| Lenovo        | ThinkPad X230 23253QU       | Notebook    | [fde2b81a1c](https://linux-hardware.org/?probe=fde2b81a1c) | May 11, 2022 |
| Dell          | 0WMJ54 A01                  | Desktop     | [58b3a1b83d](https://linux-hardware.org/?probe=58b3a1b83d) | May 07, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [db9760ae3a](https://linux-hardware.org/?probe=db9760ae3a) | Apr 27, 2022 |
| Biostar       | A68N-2100K                  | Desktop     | [87d629883f](https://linux-hardware.org/?probe=87d629883f) | Apr 27, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [b53c2836e9](https://linux-hardware.org/?probe=b53c2836e9) | Apr 21, 2022 |
| ASUSTek       | ASUSPRO P1440FAC_P1440FA    | Notebook    | [cb2bc8f53e](https://linux-hardware.org/?probe=cb2bc8f53e) | Apr 21, 2022 |
| Lenovo        | ThinkPad SL 2743X12         | Notebook    | [ad56efc5ff](https://linux-hardware.org/?probe=ad56efc5ff) | Apr 19, 2022 |
| HP            | Victus by Laptop 16-d0xx... | Notebook    | [020929c7b4](https://linux-hardware.org/?probe=020929c7b4) | Apr 17, 2022 |
| HP            | 3048h                       | Desktop     | [2d19799047](https://linux-hardware.org/?probe=2d19799047) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a7da4b6ee0](https://linux-hardware.org/?probe=a7da4b6ee0) | Apr 14, 2022 |
| Gigabyte      | 945PL-S3                    | Desktop     | [a0ab75ee00](https://linux-hardware.org/?probe=a0ab75ee00) | Apr 14, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [2cb837e17f](https://linux-hardware.org/?probe=2cb837e17f) | Apr 14, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [8d091affca](https://linux-hardware.org/?probe=8d091affca) | Apr 13, 2022 |
| HP            | ProBook 450 G4              | Notebook    | [fb5bcd7c77](https://linux-hardware.org/?probe=fb5bcd7c77) | Apr 13, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [0809202e65](https://linux-hardware.org/?probe=0809202e65) | Apr 12, 2022 |
| ASUSTek       | X550CC                      | Notebook    | [a3f3072035](https://linux-hardware.org/?probe=a3f3072035) | Apr 12, 2022 |
| MSI           | Katana GF66 11UE            | Notebook    | [36c4b80dbb](https://linux-hardware.org/?probe=36c4b80dbb) | Apr 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000RAD     | Notebook    | [6f4db41ef5](https://linux-hardware.org/?probe=6f4db41ef5) | Apr 06, 2022 |
| Acer          | Aspire xxxx                 | Notebook    | [c389f4acb2](https://linux-hardware.org/?probe=c389f4acb2) | Apr 06, 2022 |
| Dell          | Latitude E7240              | Notebook    | [242cae44a5](https://linux-hardware.org/?probe=242cae44a5) | Apr 04, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [c0dd92f23c](https://linux-hardware.org/?probe=c0dd92f23c) | Apr 03, 2022 |
| Packard Be... | EasyNote TK85               | Notebook    | [bfc20224d0](https://linux-hardware.org/?probe=bfc20224d0) | Mar 28, 2022 |
| Apple         | MacBookPro7,1               | Notebook    | [6e0eef7b54](https://linux-hardware.org/?probe=6e0eef7b54) | Mar 25, 2022 |
| ASUSTek       | N550JK                      | Notebook    | [dac9dfc52d](https://linux-hardware.org/?probe=dac9dfc52d) | Mar 20, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5eb63254f8](https://linux-hardware.org/?probe=5eb63254f8) | Mar 19, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5864c55419](https://linux-hardware.org/?probe=5864c55419) | Mar 19, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [08a511ac81](https://linux-hardware.org/?probe=08a511ac81) | Mar 18, 2022 |
| Fujitsu       | LIFEBOOK AH544              | Notebook    | [61b36dcd42](https://linux-hardware.org/?probe=61b36dcd42) | Mar 18, 2022 |
| ASUSTek       | N501VW                      | Notebook    | [e3df8d9fc2](https://linux-hardware.org/?probe=e3df8d9fc2) | Mar 18, 2022 |
| Dell          | Latitude E7470              | Notebook    | [2eca1925d5](https://linux-hardware.org/?probe=2eca1925d5) | Mar 16, 2022 |
| Dell          | Latitude E7470              | Notebook    | [b10d8b3a00](https://linux-hardware.org/?probe=b10d8b3a00) | Mar 16, 2022 |
| Dell          | Latitude E6530              | Notebook    | [2c3bfeff1d](https://linux-hardware.org/?probe=2c3bfeff1d) | Mar 13, 2022 |
| Unknown       | Unknown                     | Notebook    | [472d23c4f4](https://linux-hardware.org/?probe=472d23c4f4) | Mar 13, 2022 |
| Gigabyte      | G1.Sniper 5                 | Desktop     | [1ee0fc40a2](https://linux-hardware.org/?probe=1ee0fc40a2) | Mar 12, 2022 |
| ASUSTek       | H61-PLUS                    | Desktop     | [0d2de64455](https://linux-hardware.org/?probe=0d2de64455) | Mar 06, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [76da8a616f](https://linux-hardware.org/?probe=76da8a616f) | Mar 05, 2022 |
| ASUSTek       | X550VX                      | Notebook    | [91eafd1ed4](https://linux-hardware.org/?probe=91eafd1ed4) | Mar 04, 2022 |
| HP            | Pavilion dv6                | Notebook    | [dad6067f40](https://linux-hardware.org/?probe=dad6067f40) | Mar 03, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [29926fb03b](https://linux-hardware.org/?probe=29926fb03b) | Mar 03, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [e8956dc4ec](https://linux-hardware.org/?probe=e8956dc4ec) | Feb 27, 2022 |
| ASUSTek       | H81-PLUS                    | Desktop     | [9c68dfb511](https://linux-hardware.org/?probe=9c68dfb511) | Feb 26, 2022 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [071f146979](https://linux-hardware.org/?probe=071f146979) | Feb 24, 2022 |
| Dell          | Inspiron 5520               | Notebook    | [fa0603a25d](https://linux-hardware.org/?probe=fa0603a25d) | Feb 16, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [4d49233d4b](https://linux-hardware.org/?probe=4d49233d4b) | Feb 11, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [8294f013e8](https://linux-hardware.org/?probe=8294f013e8) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [93ca64d766](https://linux-hardware.org/?probe=93ca64d766) | Jan 28, 2022 |
| HP            | 8054                        | Desktop     | [332217129d](https://linux-hardware.org/?probe=332217129d) | Jan 26, 2022 |
| ASUSTek       | UX303UB                     | Notebook    | [c48fbc97e2](https://linux-hardware.org/?probe=c48fbc97e2) | Jan 22, 2022 |
| ECS           | H61H2-A                     | Desktop     | [90c26876b2](https://linux-hardware.org/?probe=90c26876b2) | Jan 21, 2022 |
| Alienware     | 17 R3                       | Notebook    | [032772ad42](https://linux-hardware.org/?probe=032772ad42) | Jan 20, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [e800e249d1](https://linux-hardware.org/?probe=e800e249d1) | Jan 19, 2022 |
| ASUSTek       | N55SF                       | Notebook    | [104263a808](https://linux-hardware.org/?probe=104263a808) | Jan 19, 2022 |
| ECS           | H61H2-A                     | Desktop     | [518e31fcb0](https://linux-hardware.org/?probe=518e31fcb0) | Jan 13, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [6875440733](https://linux-hardware.org/?probe=6875440733) | Jan 10, 2022 |
| ASUSTek       | X450LC                      | Notebook    | [8228658808](https://linux-hardware.org/?probe=8228658808) | Jan 09, 2022 |
| ECS           | H61H2-A                     | Desktop     | [47fb5347c0](https://linux-hardware.org/?probe=47fb5347c0) | Jan 06, 2022 |
| ECS           | H61H2-A                     | Desktop     | [fa589d8ed4](https://linux-hardware.org/?probe=fa589d8ed4) | Jan 06, 2022 |
| HP            | 806A                        | Desktop     | [d7519db95a](https://linux-hardware.org/?probe=d7519db95a) | Jan 02, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [ba7acc9c68](https://linux-hardware.org/?probe=ba7acc9c68) | Jan 01, 2022 |
| ASUSTek       | 1001PX                      | Notebook    | [a175657549](https://linux-hardware.org/?probe=a175657549) | Dec 31, 2021 |
| ASUSTek       | 1001PX                      | Notebook    | [48423d0bef](https://linux-hardware.org/?probe=48423d0bef) | Dec 31, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [71a50bcb50](https://linux-hardware.org/?probe=71a50bcb50) | Dec 30, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [d8d81e5c50](https://linux-hardware.org/?probe=d8d81e5c50) | Dec 30, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [71135c1724](https://linux-hardware.org/?probe=71135c1724) | Dec 27, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | Notebook    | [9f22de7369](https://linux-hardware.org/?probe=9f22de7369) | Dec 24, 2021 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [dcbbdb5fc5](https://linux-hardware.org/?probe=dcbbdb5fc5) | Dec 23, 2021 |
| Acer          | Aspire E1-572G              | Notebook    | [44551d08cd](https://linux-hardware.org/?probe=44551d08cd) | Dec 21, 2021 |
| Razer         | Blade 15 Advanced Model ... | Notebook    | [5408a1a82b](https://linux-hardware.org/?probe=5408a1a82b) | Dec 21, 2021 |
| Raspberry ... | Raspberry Pi                | Soc         | [261f98a324](https://linux-hardware.org/?probe=261f98a324) | Dec 19, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [a931eb10f0](https://linux-hardware.org/?probe=a931eb10f0) | Dec 19, 2021 |
| ASUSTek       | UX430UNR                    | Notebook    | [8e802c50ad](https://linux-hardware.org/?probe=8e802c50ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7b6f9acbf8](https://linux-hardware.org/?probe=7b6f9acbf8) | Dec 15, 2021 |
| HP            | 3397                        | Desktop     | [83d7b8fe86](https://linux-hardware.org/?probe=83d7b8fe86) | Dec 12, 2021 |
| HP            | 3397                        | Desktop     | [469adb677f](https://linux-hardware.org/?probe=469adb677f) | Dec 12, 2021 |
| Microsoft     | Surface Book 2              | Tablet      | [b4a346e899](https://linux-hardware.org/?probe=b4a346e899) | Dec 11, 2021 |
| HP            | ZBook 15 G3                 | Notebook    | [2c739999fa](https://linux-hardware.org/?probe=2c739999fa) | Dec 10, 2021 |
| ASUSTek       | X580VD                      | Notebook    | [8473dd1cc0](https://linux-hardware.org/?probe=8473dd1cc0) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [68820e21d2](https://linux-hardware.org/?probe=68820e21d2) | Dec 08, 2021 |
| Dell          | Vostro 1510                 | Notebook    | [c7e180ab84](https://linux-hardware.org/?probe=c7e180ab84) | Dec 08, 2021 |
| Dell          | Latitude E7470              | Notebook    | [06666f541b](https://linux-hardware.org/?probe=06666f541b) | Dec 07, 2021 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [7eed1618fe](https://linux-hardware.org/?probe=7eed1618fe) | Dec 04, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [01c7adcf94](https://linux-hardware.org/?probe=01c7adcf94) | Nov 28, 2021 |
| HP            | EliteBook 840 G1            | Notebook    | [6eff02505f](https://linux-hardware.org/?probe=6eff02505f) | Nov 27, 2021 |
| HP            | EliteBook 745 G3            | Notebook    | [92968d4a23](https://linux-hardware.org/?probe=92968d4a23) | Nov 27, 2021 |
| ASUSTek       | Z170-PRO                    | Desktop     | [005b267983](https://linux-hardware.org/?probe=005b267983) | Nov 22, 2021 |
| ASUSTek       | GL702VMK                    | Notebook    | [ff58d2a76e](https://linux-hardware.org/?probe=ff58d2a76e) | Nov 21, 2021 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [81a7c19597](https://linux-hardware.org/?probe=81a7c19597) | Nov 17, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [f119e55cf9](https://linux-hardware.org/?probe=f119e55cf9) | Nov 13, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [fa348e4f87](https://linux-hardware.org/?probe=fa348e4f87) | Nov 12, 2021 |
| Gigabyte      | P41T-D3P                    | Desktop     | [54a25af09a](https://linux-hardware.org/?probe=54a25af09a) | Nov 11, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [fc4d285e0a](https://linux-hardware.org/?probe=fc4d285e0a) | Nov 10, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [20aa404ab6](https://linux-hardware.org/?probe=20aa404ab6) | Nov 10, 2021 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [cfafa7735b](https://linux-hardware.org/?probe=cfafa7735b) | Nov 08, 2021 |
| Dell          | Latitude E7240              | Notebook    | [366228fab6](https://linux-hardware.org/?probe=366228fab6) | Nov 05, 2021 |
| ASUSTek       | Z97-K                       | Desktop     | [1e136c311c](https://linux-hardware.org/?probe=1e136c311c) | Nov 03, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d098305f2a](https://linux-hardware.org/?probe=d098305f2a) | Oct 30, 2021 |
| HP            | ProBook 640 G2              | Notebook    | [d99bdece1d](https://linux-hardware.org/?probe=d99bdece1d) | Oct 30, 2021 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8db63e7a74](https://linux-hardware.org/?probe=8db63e7a74) | Oct 28, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [75b53e8d45](https://linux-hardware.org/?probe=75b53e8d45) | Oct 27, 2021 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [19cdc9b391](https://linux-hardware.org/?probe=19cdc9b391) | Oct 26, 2021 |
| Sony          | VPCSA25GX                   | Notebook    | [be4db20b0e](https://linux-hardware.org/?probe=be4db20b0e) | Oct 25, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [6ab1ce41db](https://linux-hardware.org/?probe=6ab1ce41db) | Oct 25, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [6547cded19](https://linux-hardware.org/?probe=6547cded19) | Oct 22, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [30c1b322ad](https://linux-hardware.org/?probe=30c1b322ad) | Oct 22, 2021 |
| ASUSTek       | U56E                        | Notebook    | [a610876405](https://linux-hardware.org/?probe=a610876405) | Oct 20, 2021 |
| HP            | Laptop 15-ef2xxx            | Notebook    | [4e6bceb431](https://linux-hardware.org/?probe=4e6bceb431) | Oct 18, 2021 |
| ASUSTek       | H110M-R                     | Desktop     | [783eeaaa01](https://linux-hardware.org/?probe=783eeaaa01) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [87c7c24dcc](https://linux-hardware.org/?probe=87c7c24dcc) | Oct 17, 2021 |
| Acer          | Aspire A715-75G             | Notebook    | [0d9ad64b08](https://linux-hardware.org/?probe=0d9ad64b08) | Oct 15, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [cce3e9bd74](https://linux-hardware.org/?probe=cce3e9bd74) | Oct 12, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [398dedabb8](https://linux-hardware.org/?probe=398dedabb8) | Oct 07, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [24efeaacb7](https://linux-hardware.org/?probe=24efeaacb7) | Oct 07, 2021 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [23d2e1a73d](https://linux-hardware.org/?probe=23d2e1a73d) | Oct 06, 2021 |
| HP            | ProBook 440 G2              | Notebook    | [cc83275513](https://linux-hardware.org/?probe=cc83275513) | Oct 05, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [325655d6c5](https://linux-hardware.org/?probe=325655d6c5) | Sep 29, 2021 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [6cfb3f0c44](https://linux-hardware.org/?probe=6cfb3f0c44) | Sep 28, 2021 |
| ASUSTek       | P8H61-M LE R2.0             | Desktop     | [b633c9e1d1](https://linux-hardware.org/?probe=b633c9e1d1) | Sep 28, 2021 |
| ASUSTek       | T103HAF                     | Tablet      | [b2d1b00b0a](https://linux-hardware.org/?probe=b2d1b00b0a) | Sep 28, 2021 |
| ASRock        | B85M                        | Desktop     | [566089bd43](https://linux-hardware.org/?probe=566089bd43) | Sep 27, 2021 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [eec5db351d](https://linux-hardware.org/?probe=eec5db351d) | Sep 27, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [0e614dfffe](https://linux-hardware.org/?probe=0e614dfffe) | Sep 27, 2021 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [3c4378f506](https://linux-hardware.org/?probe=3c4378f506) | Sep 25, 2021 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [9b27471e86](https://linux-hardware.org/?probe=9b27471e86) | Sep 23, 2021 |
| HP            | EliteBook 745 G2            | Notebook    | [2b74c7b1ff](https://linux-hardware.org/?probe=2b74c7b1ff) | Sep 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [2b132c74b6](https://linux-hardware.org/?probe=2b132c74b6) | Sep 16, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [ca2bc77aa5](https://linux-hardware.org/?probe=ca2bc77aa5) | Sep 16, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [31ca803af1](https://linux-hardware.org/?probe=31ca803af1) | Sep 13, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [675a3f37b7](https://linux-hardware.org/?probe=675a3f37b7) | Sep 12, 2021 |
| LG Electro... | RD590-K.ADJCRE6             | Notebook    | [00da9ca38f](https://linux-hardware.org/?probe=00da9ca38f) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [ec0cd5d69b](https://linux-hardware.org/?probe=ec0cd5d69b) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [7797008e19](https://linux-hardware.org/?probe=7797008e19) | Sep 12, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [07d1890920](https://linux-hardware.org/?probe=07d1890920) | Sep 12, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X540... | Notebook    | [a6221df8f8](https://linux-hardware.org/?probe=a6221df8f8) | Sep 10, 2021 |
| ASUSTek       | X540UV                      | Notebook    | [b0a231831a](https://linux-hardware.org/?probe=b0a231831a) | Sep 09, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [d47d63a84f](https://linux-hardware.org/?probe=d47d63a84f) | Sep 07, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [453f65a5e7](https://linux-hardware.org/?probe=453f65a5e7) | Sep 07, 2021 |
| Acer          | Aspire A715-71G             | Notebook    | [b915ae27b7](https://linux-hardware.org/?probe=b915ae27b7) | Sep 06, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [62fc103f71](https://linux-hardware.org/?probe=62fc103f71) | Sep 06, 2021 |
| ECS           | GeForce6100PM-M2            | Desktop     | [016672b182](https://linux-hardware.org/?probe=016672b182) | Sep 03, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [b011298d66](https://linux-hardware.org/?probe=b011298d66) | Sep 01, 2021 |
| MSI           | Prestige 14 A10RB           | Notebook    | [2aaa6d05d2](https://linux-hardware.org/?probe=2aaa6d05d2) | Sep 01, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | Desktop     | [2044660bb8](https://linux-hardware.org/?probe=2044660bb8) | Aug 30, 2021 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [eec643e4e2](https://linux-hardware.org/?probe=eec643e4e2) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0e5100e716](https://linux-hardware.org/?probe=0e5100e716) | Aug 29, 2021 |
| YANYU         | M9F baytrail                | Desktop     | [0bf997753c](https://linux-hardware.org/?probe=0bf997753c) | Aug 29, 2021 |
| Lenovo        | IdeaPad Z410 20292          | Notebook    | [9f01a4629a](https://linux-hardware.org/?probe=9f01a4629a) | Aug 28, 2021 |
| MSI           | H81M-P33                    | Desktop     | [de74046226](https://linux-hardware.org/?probe=de74046226) | Aug 23, 2021 |
| ASUSTek       | X550EA                      | Notebook    | [19a7dfc92a](https://linux-hardware.org/?probe=19a7dfc92a) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [1563940d09](https://linux-hardware.org/?probe=1563940d09) | Aug 22, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [34cd2a9116](https://linux-hardware.org/?probe=34cd2a9116) | Aug 22, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [bfe60273f6](https://linux-hardware.org/?probe=bfe60273f6) | Aug 09, 2021 |
| HP            | ZBook 15                    | Notebook    | [1a67896055](https://linux-hardware.org/?probe=1a67896055) | Aug 09, 2021 |
| Sony          | VPCEH36EG                   | Notebook    | [ec709da453](https://linux-hardware.org/?probe=ec709da453) | Aug 09, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [31891cbc13](https://linux-hardware.org/?probe=31891cbc13) | Aug 08, 2021 |
| ASUSTek       | ROG Strix G712LW_G712LW     | Notebook    | [fe27de6bbc](https://linux-hardware.org/?probe=fe27de6bbc) | Aug 07, 2021 |
| HP            | ENVY Laptop 13-aq0xxx       | Notebook    | [407501f166](https://linux-hardware.org/?probe=407501f166) | Aug 05, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [1e165352ad](https://linux-hardware.org/?probe=1e165352ad) | Aug 04, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [a5c472e082](https://linux-hardware.org/?probe=a5c472e082) | Aug 01, 2021 |
| Acer          | Aspire 5749Z                | Notebook    | [538eb1efa0](https://linux-hardware.org/?probe=538eb1efa0) | Aug 01, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [13e3cf7a5f](https://linux-hardware.org/?probe=13e3cf7a5f) | Jul 29, 2021 |
| Acer          | Aspire E5-475G              | Notebook    | [063facd29a](https://linux-hardware.org/?probe=063facd29a) | Jul 28, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [4b49f7026f](https://linux-hardware.org/?probe=4b49f7026f) | Jul 27, 2021 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [2bd8f0dd2e](https://linux-hardware.org/?probe=2bd8f0dd2e) | Jul 27, 2021 |
| Lenovo        | ThinkPad E15 20RD0086UE     | Notebook    | [afb9cb6674](https://linux-hardware.org/?probe=afb9cb6674) | Jul 27, 2021 |
| Lenovo        | Z50-75 80EC                 | Notebook    | [5d118fd4cc](https://linux-hardware.org/?probe=5d118fd4cc) | Jul 26, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [3f20462c62](https://linux-hardware.org/?probe=3f20462c62) | Jul 25, 2021 |
| HP            | ProBook 4540s               | Notebook    | [719b37c9ac](https://linux-hardware.org/?probe=719b37c9ac) | Jul 20, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [0ae43f5015](https://linux-hardware.org/?probe=0ae43f5015) | Jul 20, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [b26638f586](https://linux-hardware.org/?probe=b26638f586) | Jul 17, 2021 |
| ASUSTek       | K55VD                       | Notebook    | [8a28a4f7f5](https://linux-hardware.org/?probe=8a28a4f7f5) | Jul 17, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [08f5207ee6](https://linux-hardware.org/?probe=08f5207ee6) | Jul 17, 2021 |
| ASUSTek       | X550LD                      | Notebook    | [b3bb7e1295](https://linux-hardware.org/?probe=b3bb7e1295) | Jul 17, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | Desktop     | [01b8cc373f](https://linux-hardware.org/?probe=01b8cc373f) | Jul 13, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [09ec64fc0d](https://linux-hardware.org/?probe=09ec64fc0d) | Jul 10, 2021 |
| HP            | Notebook                    | Notebook    | [3fc4cb2f55](https://linux-hardware.org/?probe=3fc4cb2f55) | Jul 09, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [90a20b185b](https://linux-hardware.org/?probe=90a20b185b) | Jul 03, 2021 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [0301b9707b](https://linux-hardware.org/?probe=0301b9707b) | Jun 29, 2021 |
| Lenovo        | ThinkPad E560 20EV0005AD    | Notebook    | [fab11e73ee](https://linux-hardware.org/?probe=fab11e73ee) | Jun 29, 2021 |
| Acer          | Aspire 4736Z                | Notebook    | [6a5d92699d](https://linux-hardware.org/?probe=6a5d92699d) | Jun 23, 2021 |
| Dell          | Latitude D420               | Notebook    | [5f0d609bef](https://linux-hardware.org/?probe=5f0d609bef) | Jun 21, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [7026c20c97](https://linux-hardware.org/?probe=7026c20c97) | Jun 20, 2021 |
| Supermicro    | X11DPL-i                    | Server      | [f34a1bbe5a](https://linux-hardware.org/?probe=f34a1bbe5a) | Jun 20, 2021 |
| ASUSTek       | ROG Maximus XII HERO        | Desktop     | [1343b5bb5d](https://linux-hardware.org/?probe=1343b5bb5d) | Jun 20, 2021 |
| ASUSTek       | PRIME B460-PLUS             | Desktop     | [5963dd2256](https://linux-hardware.org/?probe=5963dd2256) | Jun 18, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [4af988fc2f](https://linux-hardware.org/?probe=4af988fc2f) | Jun 17, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [1fd8a9e8c8](https://linux-hardware.org/?probe=1fd8a9e8c8) | Jun 16, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [0c47a21c07](https://linux-hardware.org/?probe=0c47a21c07) | Jun 14, 2021 |
| ASUSTek       | Z11PG-D24 Series            | Server      | [e4be3f2344](https://linux-hardware.org/?probe=e4be3f2344) | Jun 12, 2021 |
| ASUSTek       | N53SV                       | Notebook    | [28e717743a](https://linux-hardware.org/?probe=28e717743a) | Jun 06, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [35b68a0b4a](https://linux-hardware.org/?probe=35b68a0b4a) | Jun 06, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4b5debd7a6](https://linux-hardware.org/?probe=4b5debd7a6) | Jun 04, 2021 |
| Gigabyte      | P31-ES3G                    | Desktop     | [4333473e1e](https://linux-hardware.org/?probe=4333473e1e) | Jun 03, 2021 |
| HP            | ProBook 4520s               | Notebook    | [b0a9a196db](https://linux-hardware.org/?probe=b0a9a196db) | Jun 03, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [b3206cba40](https://linux-hardware.org/?probe=b3206cba40) | Jun 03, 2021 |
| HP            | ProLiant DL380p Gen8        | Server      | [043730ad50](https://linux-hardware.org/?probe=043730ad50) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [1023832c74](https://linux-hardware.org/?probe=1023832c74) | Jun 01, 2021 |
| ASRock        | N68-GS4 FX                  | Desktop     | [2ff6c9500b](https://linux-hardware.org/?probe=2ff6c9500b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [07aa0b9e2b](https://linux-hardware.org/?probe=07aa0b9e2b) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [6b0fca64c4](https://linux-hardware.org/?probe=6b0fca64c4) | Jun 01, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [4c650b1991](https://linux-hardware.org/?probe=4c650b1991) | Jun 01, 2021 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [74d1da4b68](https://linux-hardware.org/?probe=74d1da4b68) | May 28, 2021 |
| ASUSTek       | X550MJ                      | Notebook    | [208fc3f30f](https://linux-hardware.org/?probe=208fc3f30f) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [28d19f1a59](https://linux-hardware.org/?probe=28d19f1a59) | May 25, 2021 |
| Acer          | Aspire R3-131T              | Notebook    | [512cc44d82](https://linux-hardware.org/?probe=512cc44d82) | May 21, 2021 |
| ASUSTek       | K53SM                       | Notebook    | [f0199bc53d](https://linux-hardware.org/?probe=f0199bc53d) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [bca3c06314](https://linux-hardware.org/?probe=bca3c06314) | May 20, 2021 |
| ASUSTek       | T100TA                      | Notebook    | [f232d2395d](https://linux-hardware.org/?probe=f232d2395d) | May 19, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [1779bd65f6](https://linux-hardware.org/?probe=1779bd65f6) | May 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [8771b02dfe](https://linux-hardware.org/?probe=8771b02dfe) | May 17, 2021 |
| ASUSTek       | N56VM                       | Notebook    | [1417eccc8b](https://linux-hardware.org/?probe=1417eccc8b) | May 15, 2021 |
| HP            | EliteBook 725 G2            | Notebook    | [5dddeca3e8](https://linux-hardware.org/?probe=5dddeca3e8) | May 09, 2021 |
| MSI           | PH67A-C43                   | Desktop     | [8e818ce79a](https://linux-hardware.org/?probe=8e818ce79a) | May 05, 2021 |
| Acer          | Aspire V3-574G              | Notebook    | [507422ce0b](https://linux-hardware.org/?probe=507422ce0b) | May 05, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [2d12301b1c](https://linux-hardware.org/?probe=2d12301b1c) | May 05, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57540cdfa4](https://linux-hardware.org/?probe=57540cdfa4) | May 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [8f0e9df209](https://linux-hardware.org/?probe=8f0e9df209) | May 01, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [940758b420](https://linux-hardware.org/?probe=940758b420) | Apr 27, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [ced3a1165d](https://linux-hardware.org/?probe=ced3a1165d) | Apr 24, 2021 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [eeb73d1c4a](https://linux-hardware.org/?probe=eeb73d1c4a) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [93671f3ecc](https://linux-hardware.org/?probe=93671f3ecc) | Apr 20, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [9fbf2707b0](https://linux-hardware.org/?probe=9fbf2707b0) | Apr 19, 2021 |
| ASUSTek       | X555LF                      | Notebook    | [eb9637ae4a](https://linux-hardware.org/?probe=eb9637ae4a) | Apr 19, 2021 |
| Lenovo        | ThinkPad E590 20NB0057AD    | Notebook    | [d06cfc6dee](https://linux-hardware.org/?probe=d06cfc6dee) | Apr 18, 2021 |
| Acer          | AOD260                      | Notebook    | [97f6b98307](https://linux-hardware.org/?probe=97f6b98307) | Apr 16, 2021 |
| Lenovo        | ThinkPad T470p 20J6S08M0... | Notebook    | [84619b1b45](https://linux-hardware.org/?probe=84619b1b45) | Apr 15, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [1dcb2a173e](https://linux-hardware.org/?probe=1dcb2a173e) | Apr 14, 2021 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [28d13bbb26](https://linux-hardware.org/?probe=28d13bbb26) | Apr 14, 2021 |
| Gigabyte      | M52S-S3P                    | Desktop     | [494ac8b449](https://linux-hardware.org/?probe=494ac8b449) | Apr 11, 2021 |
| Lenovo        | ThinkBook 14s Yoga ITL 2... | Convertible | [29e4ff83db](https://linux-hardware.org/?probe=29e4ff83db) | Apr 10, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [7713767fa6](https://linux-hardware.org/?probe=7713767fa6) | Apr 10, 2021 |
| HP            | EliteBook 840 G2            | Notebook    | [9c00d55213](https://linux-hardware.org/?probe=9c00d55213) | Apr 10, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [9a9c3c8d26](https://linux-hardware.org/?probe=9a9c3c8d26) | Apr 09, 2021 |
| Lenovo        | V310-15IKB 80T3             | Notebook    | [6e1542aab7](https://linux-hardware.org/?probe=6e1542aab7) | Apr 09, 2021 |
| ASUSTek       | X542UQ                      | Notebook    | [5b0c97ade1](https://linux-hardware.org/?probe=5b0c97ade1) | Apr 09, 2021 |
| MSI           | CR610M                      | Notebook    | [e2e00880a3](https://linux-hardware.org/?probe=e2e00880a3) | Apr 08, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [60168d5b6d](https://linux-hardware.org/?probe=60168d5b6d) | Apr 07, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [fc3756c451](https://linux-hardware.org/?probe=fc3756c451) | Apr 05, 2021 |
| MSI           | CX62 6QL                    | Notebook    | [41b87e1036](https://linux-hardware.org/?probe=41b87e1036) | Apr 05, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [ddda7566c5](https://linux-hardware.org/?probe=ddda7566c5) | Apr 03, 2021 |
| Acer          | Aspire 4741                 | Notebook    | [5fb915669a](https://linux-hardware.org/?probe=5fb915669a) | Apr 03, 2021 |
| ASUSTek       | H61M-C                      | Desktop     | [c39fc169bf](https://linux-hardware.org/?probe=c39fc169bf) | Apr 02, 2021 |
| Acer          | Aspire E1-571G              | Notebook    | [c5e7e65164](https://linux-hardware.org/?probe=c5e7e65164) | Apr 01, 2021 |
| HP            | EliteBook 745 G4            | Notebook    | [a5888bbded](https://linux-hardware.org/?probe=a5888bbded) | Apr 01, 2021 |
| MSI           | GE60 2OC\2OD\2OE            | Notebook    | [9a4a054203](https://linux-hardware.org/?probe=9a4a054203) | Apr 01, 2021 |
| ASUSTek       | Z170-K                      | Desktop     | [9c2661508e](https://linux-hardware.org/?probe=9c2661508e) | Mar 30, 2021 |
| Acer          | Aspire E5-573G              | Notebook    | [bacb9e5030](https://linux-hardware.org/?probe=bacb9e5030) | Mar 30, 2021 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [344eec241a](https://linux-hardware.org/?probe=344eec241a) | Mar 21, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [ca815648fc](https://linux-hardware.org/?probe=ca815648fc) | Mar 17, 2021 |
| Sony          | VGN-CS38GD_B                | Notebook    | [d5d788f2f3](https://linux-hardware.org/?probe=d5d788f2f3) | Mar 15, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [89b0451670](https://linux-hardware.org/?probe=89b0451670) | Mar 14, 2021 |
| ASUSTek       | H81-PLUS                    | Desktop     | [ed8b926f53](https://linux-hardware.org/?probe=ed8b926f53) | Mar 14, 2021 |
| Lenovo        | ThinkPad E560 20EV000HAD    | Notebook    | [75ba14ee94](https://linux-hardware.org/?probe=75ba14ee94) | Mar 14, 2021 |
| HP            | 3397                        | Desktop     | [13a7f8c4c2](https://linux-hardware.org/?probe=13a7f8c4c2) | Mar 08, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [be98339598](https://linux-hardware.org/?probe=be98339598) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [eb31b2ffb6](https://linux-hardware.org/?probe=eb31b2ffb6) | Mar 07, 2021 |
| ASUSTek       | P8H61                       | Desktop     | [fd19b6b1c8](https://linux-hardware.org/?probe=fd19b6b1c8) | Mar 07, 2021 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [502ef11b75](https://linux-hardware.org/?probe=502ef11b75) | Mar 07, 2021 |
| Gigabyte      | GA-M55SLI-S4                | Desktop     | [43d0cb9ac1](https://linux-hardware.org/?probe=43d0cb9ac1) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [b7e39a92a0](https://linux-hardware.org/?probe=b7e39a92a0) | Mar 07, 2021 |
| Lenovo        | ThinkPad E14 20RA0085UE     | Notebook    | [7ca6ad9361](https://linux-hardware.org/?probe=7ca6ad9361) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [5681b93aaf](https://linux-hardware.org/?probe=5681b93aaf) | Mar 06, 2021 |
| ASUSTek       | P5E                         | Desktop     | [9f858aaf27](https://linux-hardware.org/?probe=9f858aaf27) | Mar 05, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [bae11d222f](https://linux-hardware.org/?probe=bae11d222f) | Mar 04, 2021 |
| ASUSTek       | K42JK                       | Notebook    | [3ae670828a](https://linux-hardware.org/?probe=3ae670828a) | Mar 03, 2021 |
| Lenovo        | Legion Y7000P-1060 81LF     | Notebook    | [fd21e67a3c](https://linux-hardware.org/?probe=fd21e67a3c) | Feb 28, 2021 |
| HP            | ProLiant DL360 G6           | Server      | [429c09a059](https://linux-hardware.org/?probe=429c09a059) | Feb 28, 2021 |
| HP            | Pavilion g6                 | Notebook    | [2ce61d58bf](https://linux-hardware.org/?probe=2ce61d58bf) | Feb 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [dda65f86ac](https://linux-hardware.org/?probe=dda65f86ac) | Feb 24, 2021 |
| HP            | ProBook 4540s               | Notebook    | [e3ff93ab0a](https://linux-hardware.org/?probe=e3ff93ab0a) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [ab787a4172](https://linux-hardware.org/?probe=ab787a4172) | Feb 21, 2021 |
| ASUSTek       | ASUS Gaming FX570UD         | Notebook    | [7ba0b6a17d](https://linux-hardware.org/?probe=7ba0b6a17d) | Feb 21, 2021 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [b1b8587cdb](https://linux-hardware.org/?probe=b1b8587cdb) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [d45ed4ad08](https://linux-hardware.org/?probe=d45ed4ad08) | Feb 19, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [b6a8851986](https://linux-hardware.org/?probe=b6a8851986) | Feb 19, 2021 |
| Lenovo        | G580 20150                  | Notebook    | [520780b02d](https://linux-hardware.org/?probe=520780b02d) | Feb 18, 2021 |
| MSI           | Modern 14 A10M              | Notebook    | [62c9e819cd](https://linux-hardware.org/?probe=62c9e819cd) | Feb 17, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | Notebook    | [8070e672a7](https://linux-hardware.org/?probe=8070e672a7) | Feb 15, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [ee986e1fdd](https://linux-hardware.org/?probe=ee986e1fdd) | Feb 11, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [b661aa21f1](https://linux-hardware.org/?probe=b661aa21f1) | Feb 09, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [0c9067579c](https://linux-hardware.org/?probe=0c9067579c) | Feb 09, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [ab4bc22a87](https://linux-hardware.org/?probe=ab4bc22a87) | Feb 06, 2021 |
| Acer          | Aspire E5-553G              | Notebook    | [5e9aa1c3de](https://linux-hardware.org/?probe=5e9aa1c3de) | Feb 06, 2021 |
| ASUSTek       | X456URK                     | Notebook    | [6c3b5bdfb1](https://linux-hardware.org/?probe=6c3b5bdfb1) | Feb 05, 2021 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [9de86c8038](https://linux-hardware.org/?probe=9de86c8038) | Feb 05, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [d383b4a5e7](https://linux-hardware.org/?probe=d383b4a5e7) | Feb 05, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [2bd7b5699d](https://linux-hardware.org/?probe=2bd7b5699d) | Feb 05, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [f1f4fbad09](https://linux-hardware.org/?probe=f1f4fbad09) | Feb 03, 2021 |
| ASUSTek       | Z87-K                       | Desktop     | [0df26493a8](https://linux-hardware.org/?probe=0df26493a8) | Feb 03, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [82920966cf](https://linux-hardware.org/?probe=82920966cf) | Feb 01, 2021 |
| Lenovo        | Flex 2-15 20405             | Notebook    | [d82031935e](https://linux-hardware.org/?probe=d82031935e) | Feb 01, 2021 |
| ASUSTek       | N56JR                       | Notebook    | [29ad612f88](https://linux-hardware.org/?probe=29ad612f88) | Jan 28, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [2960ce1b31](https://linux-hardware.org/?probe=2960ce1b31) | Jan 27, 2021 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b97b822412](https://linux-hardware.org/?probe=b97b822412) | Jan 27, 2021 |
| Lenovo        | ThinkPad E15 20RD001SUE     | Notebook    | [a0eb5fc713](https://linux-hardware.org/?probe=a0eb5fc713) | Jan 20, 2021 |
| Dell          | Vostro 5470                 | Notebook    | [2fa2f12de6](https://linux-hardware.org/?probe=2fa2f12de6) | Jan 19, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [537d05799c](https://linux-hardware.org/?probe=537d05799c) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [66598d3f69](https://linux-hardware.org/?probe=66598d3f69) | Jan 16, 2021 |
| Sony          | VPCZ126GG                   | Notebook    | [113406e67d](https://linux-hardware.org/?probe=113406e67d) | Jan 15, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [703dd398d1](https://linux-hardware.org/?probe=703dd398d1) | Jan 14, 2021 |
| Unknown       | Unknown                     | Desktop     | [85c5454ed1](https://linux-hardware.org/?probe=85c5454ed1) | Jan 14, 2021 |
| ASUSTek       | X542UN                      | Notebook    | [44633c4ff2](https://linux-hardware.org/?probe=44633c4ff2) | Jan 13, 2021 |
| ASUSTek       | H61M-A/USB3                 | Desktop     | [d8aafdef30](https://linux-hardware.org/?probe=d8aafdef30) | Jan 10, 2021 |
| Sony          | SVF15N12SGB                 | Notebook    | [3ff592b868](https://linux-hardware.org/?probe=3ff592b868) | Jan 07, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [a0706cf84a](https://linux-hardware.org/?probe=a0706cf84a) | Jan 06, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [dd100bc162](https://linux-hardware.org/?probe=dd100bc162) | Jan 04, 2021 |
| Lenovo        | ThinkPad X1 Carbon 34483... | Notebook    | [4e6cc9fdc4](https://linux-hardware.org/?probe=4e6cc9fdc4) | Jan 03, 2021 |
| HP            | Laptop 15-bs0xx             | Notebook    | [96280026fb](https://linux-hardware.org/?probe=96280026fb) | Jan 03, 2021 |
| Dell          | Vostro 1015                 | Notebook    | [7243a2df4f](https://linux-hardware.org/?probe=7243a2df4f) | Jan 02, 2021 |
| Acer          | TravelMate P446-M           | Notebook    | [d040cbadcc](https://linux-hardware.org/?probe=d040cbadcc) | Jan 02, 2021 |
| Biostar       | P4M900-M7 FE Ver:1.0        | Desktop     | [4d96f1db71](https://linux-hardware.org/?probe=4d96f1db71) | Dec 31, 2020 |
| ASUSTek       | P5P41T-LE                   | Desktop     | [be00a7c4e5](https://linux-hardware.org/?probe=be00a7c4e5) | Dec 28, 2020 |
| Acer          | Aspire 5755G                | Notebook    | [5577ccef28](https://linux-hardware.org/?probe=5577ccef28) | Dec 28, 2020 |
| HP            | ProBook 4540s               | Notebook    | [86bd405fac](https://linux-hardware.org/?probe=86bd405fac) | Dec 27, 2020 |
| HP            | ProBook 4540s               | Notebook    | [7a93e1b05a](https://linux-hardware.org/?probe=7a93e1b05a) | Dec 27, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [9be1d69693](https://linux-hardware.org/?probe=9be1d69693) | Dec 26, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [9582155494](https://linux-hardware.org/?probe=9582155494) | Dec 25, 2020 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [f7f32358db](https://linux-hardware.org/?probe=f7f32358db) | Dec 24, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [ec5fac5f1d](https://linux-hardware.org/?probe=ec5fac5f1d) | Dec 24, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [3071d9e517](https://linux-hardware.org/?probe=3071d9e517) | Dec 23, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [46af0a2d84](https://linux-hardware.org/?probe=46af0a2d84) | Dec 22, 2020 |
| MSI           | GE60 2PC                    | Notebook    | [c659f6a910](https://linux-hardware.org/?probe=c659f6a910) | Dec 21, 2020 |
| HP            | 3397                        | Desktop     | [1b81310dbf](https://linux-hardware.org/?probe=1b81310dbf) | Dec 20, 2020 |
| HP            | 3397                        | Desktop     | [086227e446](https://linux-hardware.org/?probe=086227e446) | Dec 20, 2020 |
| Lenovo        | ThinkPad T440p 20AWS2T10... | Notebook    | [d5a85767cd](https://linux-hardware.org/?probe=d5a85767cd) | Dec 18, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [a6bf272580](https://linux-hardware.org/?probe=a6bf272580) | Dec 18, 2020 |
| HP            | ProBook 450 G4              | Notebook    | [fe5ef27982](https://linux-hardware.org/?probe=fe5ef27982) | Dec 17, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [ccdd9fbe6b](https://linux-hardware.org/?probe=ccdd9fbe6b) | Dec 16, 2020 |
| ASUSTek       | Z97-K                       | Desktop     | [e7e6ad670b](https://linux-hardware.org/?probe=e7e6ad670b) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [03f5d24d56](https://linux-hardware.org/?probe=03f5d24d56) | Dec 16, 2020 |
| Acer          | Aspire A715-74G             | Notebook    | [886054e929](https://linux-hardware.org/?probe=886054e929) | Dec 15, 2020 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [e39c3e59b5](https://linux-hardware.org/?probe=e39c3e59b5) | Dec 13, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [67aa2554c3](https://linux-hardware.org/?probe=67aa2554c3) | Dec 10, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [90a60a1e78](https://linux-hardware.org/?probe=90a60a1e78) | Dec 06, 2020 |
| MSI           | CX62 6QL                    | Notebook    | [9b4aaf5856](https://linux-hardware.org/?probe=9b4aaf5856) | Dec 06, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [d93fb9ef4a](https://linux-hardware.org/?probe=d93fb9ef4a) | Dec 04, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [47835d66f6](https://linux-hardware.org/?probe=47835d66f6) | Dec 01, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [9f5052c50b](https://linux-hardware.org/?probe=9f5052c50b) | Nov 30, 2020 |
| Gigabyte      | P55A-UD3P                   | Desktop     | [03db05b217](https://linux-hardware.org/?probe=03db05b217) | Nov 30, 2020 |
| ASUSTek       | H110M-A/M.2                 | Desktop     | [c9c25216a4](https://linux-hardware.org/?probe=c9c25216a4) | Nov 25, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [d3ff8db043](https://linux-hardware.org/?probe=d3ff8db043) | Nov 22, 2020 |
| HP            | 2AF3                        | Desktop     | [3c07a68022](https://linux-hardware.org/?probe=3c07a68022) | Nov 21, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [8e0bc13a31](https://linux-hardware.org/?probe=8e0bc13a31) | Nov 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [c099ac62d5](https://linux-hardware.org/?probe=c099ac62d5) | Nov 19, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [7787345258](https://linux-hardware.org/?probe=7787345258) | Nov 17, 2020 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [458ab52080](https://linux-hardware.org/?probe=458ab52080) | Nov 17, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [be124397e2](https://linux-hardware.org/?probe=be124397e2) | Nov 13, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [3bc3e0823a](https://linux-hardware.org/?probe=3bc3e0823a) | Nov 09, 2020 |
| HP            | ProBook 4540s               | Notebook    | [4864704e84](https://linux-hardware.org/?probe=4864704e84) | Nov 09, 2020 |
| ASUSTek       | ROG Zephyrus G14 GA401IU... | Notebook    | [adbb505553](https://linux-hardware.org/?probe=adbb505553) | Nov 08, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [543559dfac](https://linux-hardware.org/?probe=543559dfac) | Nov 07, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [c7b7b29a68](https://linux-hardware.org/?probe=c7b7b29a68) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [3b7111b4a2](https://linux-hardware.org/?probe=3b7111b4a2) | Nov 07, 2020 |
| Lenovo        | E5                          | Notebook    | [cb3bf5a3df](https://linux-hardware.org/?probe=cb3bf5a3df) | Nov 07, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [6a88e646aa](https://linux-hardware.org/?probe=6a88e646aa) | Nov 07, 2020 |
| ASUSTek       | X550VXK                     | Notebook    | [5f95436c09](https://linux-hardware.org/?probe=5f95436c09) | Nov 06, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [42ef7e253c](https://linux-hardware.org/?probe=42ef7e253c) | Nov 01, 2020 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [cba527dd9f](https://linux-hardware.org/?probe=cba527dd9f) | Nov 01, 2020 |
| Acer          | Aspire 5741G                | Notebook    | [75bacf18a7](https://linux-hardware.org/?probe=75bacf18a7) | Oct 31, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f6c5e1d108](https://linux-hardware.org/?probe=f6c5e1d108) | Oct 28, 2020 |
| Foxconn       | A8G-i                       | Desktop     | [b4675cde03](https://linux-hardware.org/?probe=b4675cde03) | Oct 27, 2020 |
| Gigabyte      | EP41-UD3L                   | Desktop     | [c3cd0fcf33](https://linux-hardware.org/?probe=c3cd0fcf33) | Oct 24, 2020 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [11db584122](https://linux-hardware.org/?probe=11db584122) | Oct 24, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [7525ff1dde](https://linux-hardware.org/?probe=7525ff1dde) | Oct 23, 2020 |
| ASUSTek       | N552VW                      | Notebook    | [6893d4927d](https://linux-hardware.org/?probe=6893d4927d) | Oct 20, 2020 |
| Lenovo        | ThinkPad Edge E540 20C6A... | Notebook    | [9565cc6937](https://linux-hardware.org/?probe=9565cc6937) | Oct 20, 2020 |
| Lenovo        | B50-80 80EW                 | Notebook    | [c6bf9e5376](https://linux-hardware.org/?probe=c6bf9e5376) | Oct 17, 2020 |
| ASUSTek       | X505BA                      | Notebook    | [6f5c254a9f](https://linux-hardware.org/?probe=6f5c254a9f) | Oct 15, 2020 |
| Intel         | P61-S3                      | Desktop     | [efee9af681](https://linux-hardware.org/?probe=efee9af681) | Oct 13, 2020 |
| Intel         | P61-S3                      | Desktop     | [36f0f58223](https://linux-hardware.org/?probe=36f0f58223) | Oct 12, 2020 |
| Gigabyte      | 8S648FX-RZ                  | Desktop     | [c00289e6ed](https://linux-hardware.org/?probe=c00289e6ed) | Oct 11, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [2763c330eb](https://linux-hardware.org/?probe=2763c330eb) | Oct 09, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [ef1c17dd39](https://linux-hardware.org/?probe=ef1c17dd39) | Oct 08, 2020 |
| ASUSTek       | UX430UA                     | Notebook    | [d6586b9bb8](https://linux-hardware.org/?probe=d6586b9bb8) | Oct 05, 2020 |
| ASUSTek       | P8Z77-V LK                  | Desktop     | [bbf7ae1125](https://linux-hardware.org/?probe=bbf7ae1125) | Oct 05, 2020 |
| Gigabyte      | P55-USB3                    | Desktop     | [ceeced1246](https://linux-hardware.org/?probe=ceeced1246) | Oct 02, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [5996a3b895](https://linux-hardware.org/?probe=5996a3b895) | Sep 29, 2020 |
| Gigabyte      | AX370-Gaming K7             | Desktop     | [60156a645b](https://linux-hardware.org/?probe=60156a645b) | Sep 29, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [01b67b1979](https://linux-hardware.org/?probe=01b67b1979) | Sep 27, 2020 |
| Sony          | VPCEB1SFX                   | Notebook    | [616d06a0b0](https://linux-hardware.org/?probe=616d06a0b0) | Sep 26, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [6f184c4bc8](https://linux-hardware.org/?probe=6f184c4bc8) | Sep 26, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [9808a6bb0c](https://linux-hardware.org/?probe=9808a6bb0c) | Sep 25, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ea9c0eca9](https://linux-hardware.org/?probe=5ea9c0eca9) | Sep 24, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [59f1e93325](https://linux-hardware.org/?probe=59f1e93325) | Sep 18, 2020 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [a91b502a98](https://linux-hardware.org/?probe=a91b502a98) | Sep 18, 2020 |
| HP            | EliteBook 725 G2            | Notebook    | [9456172087](https://linux-hardware.org/?probe=9456172087) | Sep 18, 2020 |
| Gigabyte      | B75M-D3V                    | Desktop     | [32e15ba2b5](https://linux-hardware.org/?probe=32e15ba2b5) | Sep 18, 2020 |
| ASUSTek       | N501VW                      | Notebook    | [36d0455f5f](https://linux-hardware.org/?probe=36d0455f5f) | Sep 15, 2020 |
| ASUSTek       | PRIME B360M-A               | Desktop     | [7ad450ddd7](https://linux-hardware.org/?probe=7ad450ddd7) | Sep 14, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [5ed2d21f85](https://linux-hardware.org/?probe=5ed2d21f85) | Sep 05, 2020 |
| ASUSTek       | K52F                        | Notebook    | [1658b8903d](https://linux-hardware.org/?probe=1658b8903d) | Sep 04, 2020 |
| ASUSTek       | K52F                        | Notebook    | [b7a5d27a01](https://linux-hardware.org/?probe=b7a5d27a01) | Sep 04, 2020 |
| ASUSTek       | K42Jc                       | Notebook    | [79d7ee2e74](https://linux-hardware.org/?probe=79d7ee2e74) | Sep 04, 2020 |
| Sony          | VPCSB36FG                   | Notebook    | [61bc69e87c](https://linux-hardware.org/?probe=61bc69e87c) | Sep 04, 2020 |
| Dell          | Latitude E6530              | Notebook    | [c026f89bd8](https://linux-hardware.org/?probe=c026f89bd8) | Aug 31, 2020 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [0ab2905b28](https://linux-hardware.org/?probe=0ab2905b28) | Aug 29, 2020 |
| MSI           | Prestige 14 A10RB           | Notebook    | [b7fff5e5cc](https://linux-hardware.org/?probe=b7fff5e5cc) | Aug 28, 2020 |
| HP            | EliteBook 8570w             | Notebook    | [c172701a56](https://linux-hardware.org/?probe=c172701a56) | Aug 11, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [af595ebfde](https://linux-hardware.org/?probe=af595ebfde) | Aug 10, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c03d58914c](https://linux-hardware.org/?probe=c03d58914c) | Aug 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [55c0c83149](https://linux-hardware.org/?probe=55c0c83149) | Aug 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [e97f7b8582](https://linux-hardware.org/?probe=e97f7b8582) | Aug 02, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [f7eff6d78e](https://linux-hardware.org/?probe=f7eff6d78e) | Jul 28, 2020 |
| MSI           | GF63 Thin 9RC               | Notebook    | [7b12eabb3e](https://linux-hardware.org/?probe=7b12eabb3e) | Jul 28, 2020 |
| HP            | 3397                        | Desktop     | [e4e6951a4f](https://linux-hardware.org/?probe=e4e6951a4f) | Jul 25, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [2c268bdb51](https://linux-hardware.org/?probe=2c268bdb51) | Jul 24, 2020 |
| Lenovo        | ThinkCentre M58 8910ASU     | Desktop     | [d29d396ad0](https://linux-hardware.org/?probe=d29d396ad0) | Jul 23, 2020 |
| Lenovo        | ThinkPad E490 20N8000JUE    | Notebook    | [66d2ca1186](https://linux-hardware.org/?probe=66d2ca1186) | Jul 22, 2020 |
| ASUSTek       | N53Jq                       | Notebook    | [4d04d4ee3a](https://linux-hardware.org/?probe=4d04d4ee3a) | Jul 19, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [d7789565b7](https://linux-hardware.org/?probe=d7789565b7) | Jul 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [43c91be0b3](https://linux-hardware.org/?probe=43c91be0b3) | Jul 16, 2020 |
| Gigabyte      | H170-D3H-CF                 | Desktop     | [eb9ea3a7af](https://linux-hardware.org/?probe=eb9ea3a7af) | Jul 12, 2020 |
| Lenovo        | IdeaPad 330-15IGM 81D1      | Notebook    | [e9a3474bde](https://linux-hardware.org/?probe=e9a3474bde) | Jul 09, 2020 |
| HP            | 212B                        | Desktop     | [4a3583e0db](https://linux-hardware.org/?probe=4a3583e0db) | Jul 06, 2020 |
| Acer          | TravelMate 5742Z            | Notebook    | [de25d26410](https://linux-hardware.org/?probe=de25d26410) | Jul 05, 2020 |
| ECS           | G31T-M                      | Desktop     | [614dcd20e7](https://linux-hardware.org/?probe=614dcd20e7) | Jul 05, 2020 |
| Acer          | Aspire V5-561G              | Notebook    | [81b19839f7](https://linux-hardware.org/?probe=81b19839f7) | Jul 02, 2020 |
| ASUSTek       | Z170-K                      | Desktop     | [a35de97ee5](https://linux-hardware.org/?probe=a35de97ee5) | Jun 27, 2020 |
| ASUSTek       | H110M-C                     | Desktop     | [5656016c57](https://linux-hardware.org/?probe=5656016c57) | Jun 27, 2020 |
| ASRock        | P5B-DE                      | Desktop     | [304331fe41](https://linux-hardware.org/?probe=304331fe41) | Jun 24, 2020 |
| Lenovo        | Yoga 710-15IKB 80V5         | Convertible | [d0f33583b0](https://linux-hardware.org/?probe=d0f33583b0) | Jun 21, 2020 |
| ASUSTek       | H81M-C                      | Desktop     | [7554759bac](https://linux-hardware.org/?probe=7554759bac) | Jun 18, 2020 |
| ASUSTek       | N56JN                       | Notebook    | [3f30010f53](https://linux-hardware.org/?probe=3f30010f53) | Jun 14, 2020 |
| ASUSTek       | X580VD                      | Notebook    | [1ad8491ca0](https://linux-hardware.org/?probe=1ad8491ca0) | Jun 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [376ebf1819](https://linux-hardware.org/?probe=376ebf1819) | Jun 14, 2020 |
| Acer          | Aspire F5-573G              | Notebook    | [56a1c895ee](https://linux-hardware.org/?probe=56a1c895ee) | Jun 07, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [4a67c5fabb](https://linux-hardware.org/?probe=4a67c5fabb) | Jun 03, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [8fd66dd600](https://linux-hardware.org/?probe=8fd66dd600) | Jun 01, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [fbd9ae49c7](https://linux-hardware.org/?probe=fbd9ae49c7) | Jun 01, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [d059aa2096](https://linux-hardware.org/?probe=d059aa2096) | May 29, 2020 |
| Sony          | VGN-SR165E                  | Notebook    | [ee7e382325](https://linux-hardware.org/?probe=ee7e382325) | May 27, 2020 |
| Microsoft     | Surface Book 2              | Tablet      | [0ff458cc64](https://linux-hardware.org/?probe=0ff458cc64) | May 23, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [639a8b36be](https://linux-hardware.org/?probe=639a8b36be) | May 23, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [870f5869a0](https://linux-hardware.org/?probe=870f5869a0) | May 22, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [842fbba95c](https://linux-hardware.org/?probe=842fbba95c) | May 22, 2020 |
| Lenovo        | G580 20157                  | Notebook    | [c9967bfff4](https://linux-hardware.org/?probe=c9967bfff4) | May 22, 2020 |
| Fujitsu       | LIFEBOOK NH570              | Notebook    | [58dbbb5f10](https://linux-hardware.org/?probe=58dbbb5f10) | May 22, 2020 |
| Gigabyte      | Z68P-DS3                    | Desktop     | [a82798aea1](https://linux-hardware.org/?probe=a82798aea1) | May 21, 2020 |
| HP            | 3397                        | Desktop     | [6d3acf04fa](https://linux-hardware.org/?probe=6d3acf04fa) | May 18, 2020 |
| Acer          | Aspire V5-572G              | Notebook    | [d919340bf8](https://linux-hardware.org/?probe=d919340bf8) | May 18, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [91908a3d7e](https://linux-hardware.org/?probe=91908a3d7e) | May 15, 2020 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [d064b573d0](https://linux-hardware.org/?probe=d064b573d0) | May 14, 2020 |
| ECS           | G41T-M13                    | Desktop     | [7f8c6dbb44](https://linux-hardware.org/?probe=7f8c6dbb44) | May 14, 2020 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3448fe759e](https://linux-hardware.org/?probe=3448fe759e) | May 13, 2020 |
| ECS           | G41T-M13                    | Desktop     | [b2c5f54483](https://linux-hardware.org/?probe=b2c5f54483) | May 10, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [d27ef604e7](https://linux-hardware.org/?probe=d27ef604e7) | May 10, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [cc84ca4df1](https://linux-hardware.org/?probe=cc84ca4df1) | May 08, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [150b4cbfba](https://linux-hardware.org/?probe=150b4cbfba) | May 08, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [efe32a1257](https://linux-hardware.org/?probe=efe32a1257) | May 07, 2020 |
| Lenovo        | ThinkPad X250 20CM002XUS    | Notebook    | [3cac051446](https://linux-hardware.org/?probe=3cac051446) | May 07, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [543fb035d1](https://linux-hardware.org/?probe=543fb035d1) | May 07, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [7d8b34f96f](https://linux-hardware.org/?probe=7d8b34f96f) | May 03, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a214d8fa2f](https://linux-hardware.org/?probe=a214d8fa2f) | May 02, 2020 |
| ASUSTek       | H97-PRO                     | Desktop     | [a6f251843f](https://linux-hardware.org/?probe=a6f251843f) | May 01, 2020 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [96005fbb6f](https://linux-hardware.org/?probe=96005fbb6f) | Apr 28, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3405972303](https://linux-hardware.org/?probe=3405972303) | Apr 27, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2950c5ee7f](https://linux-hardware.org/?probe=2950c5ee7f) | Apr 27, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [f82980ac2c](https://linux-hardware.org/?probe=f82980ac2c) | Apr 26, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [86e4dd0977](https://linux-hardware.org/?probe=86e4dd0977) | Apr 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [abfe333fb8](https://linux-hardware.org/?probe=abfe333fb8) | Apr 25, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [9e8575f75a](https://linux-hardware.org/?probe=9e8575f75a) | Apr 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [5ec8b8b3b7](https://linux-hardware.org/?probe=5ec8b8b3b7) | Apr 25, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [c194d8e6be](https://linux-hardware.org/?probe=c194d8e6be) | Apr 24, 2020 |
| Apple         | MacBookAir7,2               | Notebook    | [680bbeabad](https://linux-hardware.org/?probe=680bbeabad) | Apr 24, 2020 |
| HP            | Pavilion g6                 | Notebook    | [66ba3bc59b](https://linux-hardware.org/?probe=66ba3bc59b) | Apr 23, 2020 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [82f761db09](https://linux-hardware.org/?probe=82f761db09) | Apr 23, 2020 |
| ASUSTek       | Z10PE-D16 WS                | Desktop     | [409a40b72d](https://linux-hardware.org/?probe=409a40b72d) | Apr 20, 2020 |
| Lenovo        | ThinkPad E480 20KN007XAD    | Notebook    | [8310d15c91](https://linux-hardware.org/?probe=8310d15c91) | Apr 18, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [74699b5097](https://linux-hardware.org/?probe=74699b5097) | Apr 16, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [93a89841fd](https://linux-hardware.org/?probe=93a89841fd) | Apr 12, 2020 |
| ASUSTek       | X550IU                      | Notebook    | [943b36ee80](https://linux-hardware.org/?probe=943b36ee80) | Apr 10, 2020 |
| Sony          | VPCEH11FX                   | Notebook    | [e0ef96682b](https://linux-hardware.org/?probe=e0ef96682b) | Apr 09, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [45a70fa311](https://linux-hardware.org/?probe=45a70fa311) | Apr 08, 2020 |
| ASUSTek       | G750JH                      | Notebook    | [3314aa590e](https://linux-hardware.org/?probe=3314aa590e) | Apr 08, 2020 |
| ASUSTek       | Z97-C                       | Desktop     | [53462bc3ec](https://linux-hardware.org/?probe=53462bc3ec) | Apr 07, 2020 |
| Dell          | Latitude D630               | Notebook    | [98199f8421](https://linux-hardware.org/?probe=98199f8421) | Apr 07, 2020 |
| Lenovo        | Z50-70 20354                | Notebook    | [839c8344be](https://linux-hardware.org/?probe=839c8344be) | Apr 07, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [c98f5bcee3](https://linux-hardware.org/?probe=c98f5bcee3) | Apr 05, 2020 |
| ASUSTek       | 1015CX                      | Notebook    | [216b680d21](https://linux-hardware.org/?probe=216b680d21) | Apr 05, 2020 |
| Dell          | Latitude 7350               | Notebook    | [3ecdea8fcc](https://linux-hardware.org/?probe=3ecdea8fcc) | Apr 03, 2020 |
| Toshiba       | PORTEGE R930                | Notebook    | [0dbe97d54b](https://linux-hardware.org/?probe=0dbe97d54b) | Mar 30, 2020 |
| HP            | 3397                        | Desktop     | [f2d1e62e57](https://linux-hardware.org/?probe=f2d1e62e57) | Mar 29, 2020 |
| HP            | 3646h                       | Desktop     | [63c3bf2b90](https://linux-hardware.org/?probe=63c3bf2b90) | Mar 28, 2020 |
| Dell          | Inspiron 1545               | Notebook    | [ffeee579db](https://linux-hardware.org/?probe=ffeee579db) | Mar 28, 2020 |
| Dell          | Inspiron 3443               | Notebook    | [0a21a54858](https://linux-hardware.org/?probe=0a21a54858) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [aa94d9ab9b](https://linux-hardware.org/?probe=aa94d9ab9b) | Mar 28, 2020 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [96f26b673c](https://linux-hardware.org/?probe=96f26b673c) | Mar 28, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [21b92f29e5](https://linux-hardware.org/?probe=21b92f29e5) | Mar 28, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [e7effd8e19](https://linux-hardware.org/?probe=e7effd8e19) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [ec35befc4a](https://linux-hardware.org/?probe=ec35befc4a) | Mar 23, 2020 |
| Gigabyte      | G31M-S2L                    | Desktop     | [6f1f96e7fc](https://linux-hardware.org/?probe=6f1f96e7fc) | Mar 23, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [aa7093b56c](https://linux-hardware.org/?probe=aa7093b56c) | Mar 23, 2020 |
| Gigabyte      | H61M-S2V-B3                 | Desktop     | [b7d3805ba6](https://linux-hardware.org/?probe=b7d3805ba6) | Mar 23, 2020 |
| Dell          | Inspiron 5570               | Notebook    | [a79912cfdf](https://linux-hardware.org/?probe=a79912cfdf) | Mar 22, 2020 |
| HP            | Pavilion Sleekbook 15 PC    | Notebook    | [409951a0dd](https://linux-hardware.org/?probe=409951a0dd) | Mar 20, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [e849d8b11f](https://linux-hardware.org/?probe=e849d8b11f) | Mar 15, 2020 |
| Dell          | Studio 1558                 | Notebook    | [06b0f26f6a](https://linux-hardware.org/?probe=06b0f26f6a) | Mar 12, 2020 |
| ASRock        | ConRoe865GV                 | Desktop     | [2f52f8c106](https://linux-hardware.org/?probe=2f52f8c106) | Mar 12, 2020 |
| Dell          | Studio 1558                 | Notebook    | [57fddb1856](https://linux-hardware.org/?probe=57fddb1856) | Mar 12, 2020 |
| MSI           | B250M PRO-VH                | Desktop     | [1eb2d76730](https://linux-hardware.org/?probe=1eb2d76730) | Mar 10, 2020 |
| ECS           | 945GCT-M                    | Desktop     | [069450c325](https://linux-hardware.org/?probe=069450c325) | Mar 08, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [9f48604ff2](https://linux-hardware.org/?probe=9f48604ff2) | Mar 07, 2020 |
| Gigabyte      | M1689D                      | Desktop     | [43f9f0167a](https://linux-hardware.org/?probe=43f9f0167a) | Mar 07, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [c3d3d42413](https://linux-hardware.org/?probe=c3d3d42413) | Mar 05, 2020 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [b224a48803](https://linux-hardware.org/?probe=b224a48803) | Mar 04, 2020 |
| ASUSTek       | N82JQ                       | Notebook    | [b1b698b060](https://linux-hardware.org/?probe=b1b698b060) | Mar 02, 2020 |
| ASUSTek       | M4A78T-E                    | Desktop     | [80b614b253](https://linux-hardware.org/?probe=80b614b253) | Mar 02, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [910ec05246](https://linux-hardware.org/?probe=910ec05246) | Feb 29, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [ddb0fad848](https://linux-hardware.org/?probe=ddb0fad848) | Feb 29, 2020 |
| Lenovo        | ThinkCentre M58 7360EHU     | Desktop     | [7067a56ae2](https://linux-hardware.org/?probe=7067a56ae2) | Feb 27, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [e378eda49c](https://linux-hardware.org/?probe=e378eda49c) | Feb 21, 2020 |
| ASUSTek       | UX360UAK                    | Convertible | [8063e9ef93](https://linux-hardware.org/?probe=8063e9ef93) | Feb 21, 2020 |
| Dell          | Vostro 1015                 | Notebook    | [091443df09](https://linux-hardware.org/?probe=091443df09) | Feb 20, 2020 |
| ASUSTek       | PRIME Z270-K                | Desktop     | [98cee968eb](https://linux-hardware.org/?probe=98cee968eb) | Feb 18, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [c04cf86240](https://linux-hardware.org/?probe=c04cf86240) | Feb 15, 2020 |
| Toshiba       | Satellite L655              | Notebook    | [00e7d3f0b6](https://linux-hardware.org/?probe=00e7d3f0b6) | Feb 15, 2020 |
| Lenovo        | V580c 20160                 | Notebook    | [7e02c8c738](https://linux-hardware.org/?probe=7e02c8c738) | Feb 11, 2020 |
| Unknown       | Unknown                     | Desktop     | [0061763167](https://linux-hardware.org/?probe=0061763167) | Feb 11, 2020 |
| Sony          | VPCSB19GG                   | Notebook    | [cc8806b4ec](https://linux-hardware.org/?probe=cc8806b4ec) | Feb 04, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [759e13afc4](https://linux-hardware.org/?probe=759e13afc4) | Feb 02, 2020 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [32f19ab04d](https://linux-hardware.org/?probe=32f19ab04d) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [dccdce5101](https://linux-hardware.org/?probe=dccdce5101) | Jan 23, 2020 |
| Dell          | Vostro 1510                 | Notebook    | [51fbe1ce5b](https://linux-hardware.org/?probe=51fbe1ce5b) | Jan 23, 2020 |
| ASUSTek       | GL503VS                     | Notebook    | [664116ebbf](https://linux-hardware.org/?probe=664116ebbf) | Jan 22, 2020 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [f77d00b6ce](https://linux-hardware.org/?probe=f77d00b6ce) | Jan 10, 2020 |
| Dell          | Precision M4800             | Notebook    | [cc63357309](https://linux-hardware.org/?probe=cc63357309) | Jan 09, 2020 |
| Lenovo        | ThinkPad X131e 33711T4      | Notebook    | [f06e98b417](https://linux-hardware.org/?probe=f06e98b417) | Jan 08, 2020 |
| HP            | 8054                        | Desktop     | [b9f8081fe1](https://linux-hardware.org/?probe=b9f8081fe1) | Jan 06, 2020 |
| ASUSTek       | P8Z68-V LE                  | Desktop     | [9d6c061d8b](https://linux-hardware.org/?probe=9d6c061d8b) | Jan 04, 2020 |
| HP            | ProBook 4540s               | Notebook    | [9ef64f7487](https://linux-hardware.org/?probe=9ef64f7487) | Jan 03, 2020 |
| Lenovo        | G510 20238                  | Notebook    | [63fd9a500f](https://linux-hardware.org/?probe=63fd9a500f) | Dec 27, 2019 |
| Lenovo        | G510 20238                  | Notebook    | [8543221f24](https://linux-hardware.org/?probe=8543221f24) | Dec 27, 2019 |
| HP            | EliteBook 2740p             | Notebook    | [82cb2d5e90](https://linux-hardware.org/?probe=82cb2d5e90) | Dec 26, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [61d0162de0](https://linux-hardware.org/?probe=61d0162de0) | Dec 21, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [493965d4d4](https://linux-hardware.org/?probe=493965d4d4) | Dec 19, 2019 |
| Dell          | Inspiron N5040              | Notebook    | [ac12864629](https://linux-hardware.org/?probe=ac12864629) | Dec 19, 2019 |
| ASUSTek       | X542UN                      | Notebook    | [4b7f71d936](https://linux-hardware.org/?probe=4b7f71d936) | Dec 14, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [f30b5e8075](https://linux-hardware.org/?probe=f30b5e8075) | Dec 09, 2019 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [130e16c2b6](https://linux-hardware.org/?probe=130e16c2b6) | Dec 08, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [a68627d7eb](https://linux-hardware.org/?probe=a68627d7eb) | Nov 28, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [15babe41d0](https://linux-hardware.org/?probe=15babe41d0) | Nov 26, 2019 |
| HP            | 18E7                        | Desktop     | [f728a63212](https://linux-hardware.org/?probe=f728a63212) | Nov 26, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [ed7fb8cbb9](https://linux-hardware.org/?probe=ed7fb8cbb9) | Nov 15, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [5e184acc59](https://linux-hardware.org/?probe=5e184acc59) | Nov 15, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [f13de25d56](https://linux-hardware.org/?probe=f13de25d56) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [dda0a53712](https://linux-hardware.org/?probe=dda0a53712) | Nov 14, 2019 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [b86e3d7141](https://linux-hardware.org/?probe=b86e3d7141) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [7f6afd4c6b](https://linux-hardware.org/?probe=7f6afd4c6b) | Nov 13, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [370c185f25](https://linux-hardware.org/?probe=370c185f25) | Nov 13, 2019 |
| HP            | Pavilion 15                 | Notebook    | [57540edaa7](https://linux-hardware.org/?probe=57540edaa7) | Nov 12, 2019 |
| ASUSTek       | B9440UA                     | Notebook    | [79c10ef42c](https://linux-hardware.org/?probe=79c10ef42c) | Nov 11, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [380140eb8d](https://linux-hardware.org/?probe=380140eb8d) | Nov 06, 2019 |
| Dell          | Vostro 1520                 | Notebook    | [247d9e9c2f](https://linux-hardware.org/?probe=247d9e9c2f) | Nov 01, 2019 |
| ECS           | 945GCT-M                    | Desktop     | [89e9d28a32](https://linux-hardware.org/?probe=89e9d28a32) | Nov 01, 2019 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [797965c573](https://linux-hardware.org/?probe=797965c573) | Oct 30, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [63dc09b54e](https://linux-hardware.org/?probe=63dc09b54e) | Oct 28, 2019 |
| ASUSTek       | P7P55 LX                    | Desktop     | [cf9411c533](https://linux-hardware.org/?probe=cf9411c533) | Oct 28, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [400532e714](https://linux-hardware.org/?probe=400532e714) | Oct 24, 2019 |
| Dell          | Vostro 1015                 | Notebook    | [df8815e747](https://linux-hardware.org/?probe=df8815e747) | Oct 24, 2019 |
| ASUSTek       | N501VW                      | Notebook    | [4d2a1a9add](https://linux-hardware.org/?probe=4d2a1a9add) | Oct 16, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [d1394d6252](https://linux-hardware.org/?probe=d1394d6252) | Oct 11, 2019 |
| Lenovo        | IdeaPad 120S-11IAP 81A4     | Notebook    | [c4f25ea846](https://linux-hardware.org/?probe=c4f25ea846) | Oct 07, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c8223df556](https://linux-hardware.org/?probe=c8223df556) | Oct 03, 2019 |
| Dell          | Inspiron N4050              | Notebook    | [153db5ae1b](https://linux-hardware.org/?probe=153db5ae1b) | Oct 01, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [a814f0be14](https://linux-hardware.org/?probe=a814f0be14) | Sep 26, 2019 |
| Lenovo        | G50-45 80E3                 | Notebook    | [4c39be72b3](https://linux-hardware.org/?probe=4c39be72b3) | Sep 26, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [fbbabc5836](https://linux-hardware.org/?probe=fbbabc5836) | Sep 23, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [0143228659](https://linux-hardware.org/?probe=0143228659) | Sep 20, 2019 |
| Lenovo        | G50-70 20351                | Notebook    | [6e13970f68](https://linux-hardware.org/?probe=6e13970f68) | Sep 18, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [22d2f0f13e](https://linux-hardware.org/?probe=22d2f0f13e) | Sep 12, 2019 |
| ASUSTek       | X556UQK                     | Notebook    | [cd4ce4d624](https://linux-hardware.org/?probe=cd4ce4d624) | Sep 12, 2019 |
| ASUSTek       | B85-PLUS                    | Desktop     | [2665a9b231](https://linux-hardware.org/?probe=2665a9b231) | Sep 11, 2019 |
| ECS           | 945PT-A2                    | Desktop     | [e73a14a3e7](https://linux-hardware.org/?probe=e73a14a3e7) | Sep 10, 2019 |
| HP            | Pavilion 15                 | Notebook    | [c56817e0e4](https://linux-hardware.org/?probe=c56817e0e4) | Sep 10, 2019 |
| ASUSTek       | M3N78-EH                    | Desktop     | [0ded7435b9](https://linux-hardware.org/?probe=0ded7435b9) | Sep 04, 2019 |
| HP            | Pavilion g6                 | Notebook    | [81b3b2667e](https://linux-hardware.org/?probe=81b3b2667e) | Sep 03, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [a4f33fd40a](https://linux-hardware.org/?probe=a4f33fd40a) | Sep 03, 2019 |
| HP            | ProBook 4540s               | Notebook    | [1349a15c0f](https://linux-hardware.org/?probe=1349a15c0f) | Sep 01, 2019 |
| ASRock        | ConRoeXFire-eSATA2          | Desktop     | [eaf9b72412](https://linux-hardware.org/?probe=eaf9b72412) | Aug 31, 2019 |
| Lenovo        | ThinkPad E470 20H1002DAD    | Notebook    | [75804928d2](https://linux-hardware.org/?probe=75804928d2) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [579809b8b0](https://linux-hardware.org/?probe=579809b8b0) | Aug 30, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [81e015523a](https://linux-hardware.org/?probe=81e015523a) | Aug 30, 2019 |
| HP            | EliteBook 2540p             | Notebook    | [72437e888c](https://linux-hardware.org/?probe=72437e888c) | Aug 29, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [8365a8b9d6](https://linux-hardware.org/?probe=8365a8b9d6) | Aug 27, 2019 |
| ASUSTek       | X102BA                      | Notebook    | [43b9931c92](https://linux-hardware.org/?probe=43b9931c92) | Aug 26, 2019 |
| ASUSTek       | PRIME H310-PLUS             | Desktop     | [be649fc45f](https://linux-hardware.org/?probe=be649fc45f) | Aug 25, 2019 |
| MSI           | MS-1454                     | Notebook    | [b03f58cc28](https://linux-hardware.org/?probe=b03f58cc28) | Aug 23, 2019 |
| MSI           | MS-1454                     | Notebook    | [94bfc26599](https://linux-hardware.org/?probe=94bfc26599) | Aug 23, 2019 |
| ASUSTek       | X540UPR                     | Notebook    | [2f40c492db](https://linux-hardware.org/?probe=2f40c492db) | Aug 12, 2019 |
| Lenovo        | ThinkPad X201 3249CTO       | Notebook    | [24c83ab728](https://linux-hardware.org/?probe=24c83ab728) | Aug 09, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [2507713bd4](https://linux-hardware.org/?probe=2507713bd4) | Aug 06, 2019 |
| Lenovo        | ThinkPad X220 4291B25       | Notebook    | [0ad209e005](https://linux-hardware.org/?probe=0ad209e005) | Aug 06, 2019 |
| ASUSTek       | X555LJ                      | Notebook    | [541fb4f240](https://linux-hardware.org/?probe=541fb4f240) | Aug 06, 2019 |
| Gigabyte      | H110M-S2PV-CF               | Desktop     | [d0ac33919a](https://linux-hardware.org/?probe=d0ac33919a) | Aug 05, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [2ab556fd2e](https://linux-hardware.org/?probe=2ab556fd2e) | Aug 03, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [3ff8ae9e18](https://linux-hardware.org/?probe=3ff8ae9e18) | Aug 01, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9518b70a0d](https://linux-hardware.org/?probe=9518b70a0d) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [9c80796306](https://linux-hardware.org/?probe=9c80796306) | Jul 31, 2019 |
| Lenovo        | ThinkPad SL400 2743A14      | Notebook    | [66cc9aa111](https://linux-hardware.org/?probe=66cc9aa111) | Jul 31, 2019 |
| HP            | Pavilion dv6                | Notebook    | [38f37f78c5](https://linux-hardware.org/?probe=38f37f78c5) | Jul 29, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [c53df5f083](https://linux-hardware.org/?probe=c53df5f083) | Jul 27, 2019 |
| ASUSTek       | FX503VD                     | Notebook    | [051b4df60a](https://linux-hardware.org/?probe=051b4df60a) | Jul 27, 2019 |
| ASUSTek       | VivoBook 15 ASUS Laptop ... | Notebook    | [b6b40de397](https://linux-hardware.org/?probe=b6b40de397) | Jul 26, 2019 |
| ASUSTek       | GL553VD                     | Notebook    | [1a816e6ebb](https://linux-hardware.org/?probe=1a816e6ebb) | Jul 23, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [6478022b75](https://linux-hardware.org/?probe=6478022b75) | Jul 21, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [22e01f3d1f](https://linux-hardware.org/?probe=22e01f3d1f) | Jul 21, 2019 |
| ASUSTek       | X542UN                      | Notebook    | [0120b3a78b](https://linux-hardware.org/?probe=0120b3a78b) | Jul 19, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [ce6df77b4c](https://linux-hardware.org/?probe=ce6df77b4c) | Jul 18, 2019 |
| HP            | ProBook 450 G1              | Notebook    | [997a4ec1c4](https://linux-hardware.org/?probe=997a4ec1c4) | Jul 18, 2019 |
| ASUSTek       | X411UNV                     | Notebook    | [ca77267e34](https://linux-hardware.org/?probe=ca77267e34) | Jul 17, 2019 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [46408abbb6](https://linux-hardware.org/?probe=46408abbb6) | Jul 12, 2019 |
| Lenovo        | AILZx                       | Notebook    | [3673023593](https://linux-hardware.org/?probe=3673023593) | Jun 27, 2019 |
| Lenovo        | AILZx                       | Notebook    | [e4c012a605](https://linux-hardware.org/?probe=e4c012a605) | Jun 27, 2019 |
| ASUSTek       | All Series                  | Desktop     | [383d32f068](https://linux-hardware.org/?probe=383d32f068) | Jun 27, 2019 |
| ASUSTek       | UX550VD                     | Notebook    | [b4ed65654c](https://linux-hardware.org/?probe=b4ed65654c) | Jun 26, 2019 |
| ASUSTek       | UX550VD                     | Notebook    | [dfc972293d](https://linux-hardware.org/?probe=dfc972293d) | Jun 25, 2019 |
| Dell          | Latitude E6500              | Notebook    | [5d172397d7](https://linux-hardware.org/?probe=5d172397d7) | Jun 10, 2019 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [b974503bc3](https://linux-hardware.org/?probe=b974503bc3) | Jun 07, 2019 |
| ASUSTek       | X556URK                     | Notebook    | [1ac09da8a9](https://linux-hardware.org/?probe=1ac09da8a9) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [586a6a9f8a](https://linux-hardware.org/?probe=586a6a9f8a) | Jun 07, 2019 |
| Dell          | Inspiron MM061              | Notebook    | [3633557547](https://linux-hardware.org/?probe=3633557547) | Jun 06, 2019 |
| Acer          | Aspire V3-571G              | Notebook    | [116b742db8](https://linux-hardware.org/?probe=116b742db8) | Jun 05, 2019 |
| ASUSTek       | P9X79 LE                    | Desktop     | [7cb5494874](https://linux-hardware.org/?probe=7cb5494874) | Jun 03, 2019 |
| ASUSTek       | P9X79 LE                    | Desktop     | [77dc13fea3](https://linux-hardware.org/?probe=77dc13fea3) | Jun 03, 2019 |
| Dell          | Latitude E6410              | Notebook    | [91ff183bf0](https://linux-hardware.org/?probe=91ff183bf0) | Jun 02, 2019 |
| Dell          | Latitude E6410              | Notebook    | [3029853366](https://linux-hardware.org/?probe=3029853366) | Jun 02, 2019 |
| ASUSTek       | 1005PX                      | Notebook    | [33f338599d](https://linux-hardware.org/?probe=33f338599d) | May 29, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [b8a49028c8](https://linux-hardware.org/?probe=b8a49028c8) | May 27, 2019 |
| ASUSTek       | H81-PLUS                    | Desktop     | [7ce9462b77](https://linux-hardware.org/?probe=7ce9462b77) | May 25, 2019 |
| ASUSTek       | H81-PLUS                    | Desktop     | [4f2a9b31b5](https://linux-hardware.org/?probe=4f2a9b31b5) | May 19, 2019 |
| HP            | ProLiant DL360 G6           | Server      | [b4ad542a11](https://linux-hardware.org/?probe=b4ad542a11) | May 17, 2019 |
| ASUSTek       | N550JV                      | Notebook    | [1f0902bced](https://linux-hardware.org/?probe=1f0902bced) | May 17, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [89b4ae088c](https://linux-hardware.org/?probe=89b4ae088c) | May 16, 2019 |
| Lenovo        | IdeaPad 320-15IKB 81BG      | Notebook    | [4626315623](https://linux-hardware.org/?probe=4626315623) | May 14, 2019 |
| Dell          | Vostro 1500                 | Notebook    | [7008fbfa25](https://linux-hardware.org/?probe=7008fbfa25) | May 13, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [80e0cb37ad](https://linux-hardware.org/?probe=80e0cb37ad) | May 08, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [af7b263534](https://linux-hardware.org/?probe=af7b263534) | May 08, 2019 |
| HP            | EliteBook 8460w             | Notebook    | [2e2a41395d](https://linux-hardware.org/?probe=2e2a41395d) | May 07, 2019 |
| Gigabyte      | P75-D3                      | Desktop     | [341ae19874](https://linux-hardware.org/?probe=341ae19874) | May 07, 2019 |
| ASUSTek       | P7H57D-V EVO                | Desktop     | [8083f1c192](https://linux-hardware.org/?probe=8083f1c192) | May 02, 2019 |
| HP            | EliteBook Revolve 810 G3    | Notebook    | [e50b27ba1a](https://linux-hardware.org/?probe=e50b27ba1a) | Apr 27, 2019 |
| ASUSTek       | N501VW                      | Notebook    | [976a879300](https://linux-hardware.org/?probe=976a879300) | Apr 27, 2019 |
| HP            | 18E7                        | Desktop     | [314a0e2775](https://linux-hardware.org/?probe=314a0e2775) | Apr 24, 2019 |
| Acer          | Aspire 5738                 | Notebook    | [9b6046b160](https://linux-hardware.org/?probe=9b6046b160) | Apr 22, 2019 |
| Fujitsu       | LIFEBOOK AH530/HD6          | Notebook    | [7c65853191](https://linux-hardware.org/?probe=7c65853191) | Apr 21, 2019 |
| Dell          | Inspiron 5567               | Notebook    | [cc9157e4bd](https://linux-hardware.org/?probe=cc9157e4bd) | Apr 14, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [1218f381aa](https://linux-hardware.org/?probe=1218f381aa) | Apr 11, 2019 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [b9f44fe73b](https://linux-hardware.org/?probe=b9f44fe73b) | Apr 11, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [ea6eec5a29](https://linux-hardware.org/?probe=ea6eec5a29) | Apr 03, 2019 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [f7854f2bb7](https://linux-hardware.org/?probe=f7854f2bb7) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [2dd89e3983](https://linux-hardware.org/?probe=2dd89e3983) | Apr 03, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [9e505ea7e9](https://linux-hardware.org/?probe=9e505ea7e9) | Apr 03, 2019 |
| HP            | EliteBook 8470p             | Notebook    | [2d5727bd09](https://linux-hardware.org/?probe=2d5727bd09) | Apr 02, 2019 |
| HP            | EliteBook 8570p             | Notebook    | [fd1396f058](https://linux-hardware.org/?probe=fd1396f058) | Mar 29, 2019 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [ec89277577](https://linux-hardware.org/?probe=ec89277577) | Mar 09, 2019 |
| HP            | 18E7                        | Desktop     | [74ff68d1e2](https://linux-hardware.org/?probe=74ff68d1e2) | Feb 28, 2019 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [078ded72a8](https://linux-hardware.org/?probe=078ded72a8) | Dec 10, 2018 |
| ASUSTek       | B85-PRO GAMER               | Desktop     | [7ee24f399a](https://linux-hardware.org/?probe=7ee24f399a) | Dec 10, 2018 |
| Gigabyte      | H61M-S2P                    | Desktop     | [bdd9f59ab7](https://linux-hardware.org/?probe=bdd9f59ab7) | Dec 09, 2018 |
| Gigabyte      | H61M-S2P                    | Desktop     | [3e29d905ef](https://linux-hardware.org/?probe=3e29d905ef) | Dec 09, 2018 |
| ECS           | 945GZ/CT-M                  | Desktop     | [86754f87d7](https://linux-hardware.org/?probe=86754f87d7) | Dec 07, 2018 |
| ECS           | 945GZ/CT-M                  | Desktop     | [0c8259eea0](https://linux-hardware.org/?probe=0c8259eea0) | Dec 07, 2018 |
| Acer          | Aspire A715-71G             | Notebook    | [b01e1626a7](https://linux-hardware.org/?probe=b01e1626a7) | Oct 31, 2018 |
| ASUSTek       | GL553VE                     | Notebook    | [3cdb244ea4](https://linux-hardware.org/?probe=3cdb244ea4) | Mar 31, 2018 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [504bfb59ec](https://linux-hardware.org/?probe=504bfb59ec) | Jan 08, 2018 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [6976c096dc](https://linux-hardware.org/?probe=6976c096dc) | Jan 08, 2018 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Iran/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Ubuntu 20.04        | 107       | 17.89%  |
| Ubuntu 18.04        | 83        | 13.88%  |
| Ubuntu 22.04        | 36        | 6.02%   |
| Arch                | 19        | 3.18%   |
| Arch Rolling        | 17        | 2.84%   |
| Ubuntu 19.04        | 16        | 2.68%   |
| Fedora 33           | 14        | 2.34%   |
| Ubuntu 21.10        | 10        | 1.67%   |
| Ubuntu 20.10        | 10        | 1.67%   |
| KDE neon 20.04      | 10        | 1.67%   |
| Xubuntu 18.04       | 9         | 1.51%   |
| Fedora 34           | 9         | 1.51%   |
| Debian 11           | 9         | 1.51%   |
| Ubuntu 19.10        | 8         | 1.34%   |
| OpenMandriva 4.2    | 8         | 1.34%   |
| Manjaro             | 7         | 1.17%   |
| Ubuntu 21.04        | 6         | 1%      |
| Linux Mint 20.3     | 6         | 1%      |
| Fedora 37           | 6         | 1%      |
| OpenMandriva 4.3    | 5         | 0.84%   |
| Fedora 35           | 5         | 0.84%   |
| ArcoLinux Rolling   | 5         | 0.84%   |
| Zorin 15            | 4         | 0.67%   |
| Xubuntu 22.04       | 4         | 0.67%   |
| Xubuntu 20.04       | 4         | 0.67%   |
| Ubuntu 23.04        | 4         | 0.67%   |
| Ubuntu 22.10        | 4         | 0.67%   |
| Ubuntu 18.10        | 4         | 0.67%   |
| Kali 2021.2         | 4         | 0.67%   |
| Fedora 31           | 4         | 0.67%   |
| Ubuntu Unity 16.04  | 3         | 0.5%    |
| Ubuntu Budgie 20.04 | 3         | 0.5%    |
| Pop!_OS 20.04       | 3         | 0.5%    |
| OpenMandriva 23.03  | 3         | 0.5%    |
| Linux Mint 20.2     | 3         | 0.5%    |
| Linux Mint 20       | 3         | 0.5%    |
| Linux Mint 19.3     | 3         | 0.5%    |
| Kubuntu 20.04       | 3         | 0.5%    |
| KDE neon 22.04      | 3         | 0.5%    |
| Kali 2022.2         | 3         | 0.5%    |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 284       | 49.05%  |
| Fedora        | 44        | 7.6%    |
| Arch          | 34        | 5.87%   |
| Manjaro       | 24        | 4.15%   |
| Linux Mint    | 22        | 3.8%    |
| OpenMandriva  | 18        | 3.11%   |
| Xubuntu       | 17        | 2.94%   |
| Endless       | 16        | 2.76%   |
| KDE neon      | 15        | 2.59%   |
| Kali          | 15        | 2.59%   |
| Debian        | 13        | 2.25%   |
| Kubuntu       | 11        | 1.9%    |
| Pop!_OS       | 10        | 1.73%   |
| Zorin         | 7         | 1.21%   |
| Ubuntu Unity  | 5         | 0.86%   |
| ROSA          | 5         | 0.86%   |
| ArcoLinux     | 5         | 0.86%   |
| Lubuntu       | 4         | 0.69%   |
| Elementary    | 4         | 0.69%   |
| Ubuntu Budgie | 3         | 0.52%   |
| openSUSE      | 3         | 0.52%   |
| CentOS        | 3         | 0.52%   |
| Solus         | 2         | 0.35%   |
| Gentoo        | 2         | 0.35%   |
| Clear Linux   | 2         | 0.35%   |
| Artix         | 2         | 0.35%   |
| Ubuntu MATE   | 1         | 0.17%   |
| Sabayon       | 1         | 0.17%   |
| Raspbian      | 1         | 0.17%   |
| PureOS        | 1         | 0.17%   |
| NixOS         | 1         | 0.17%   |
| MX            | 1         | 0.17%   |
| Linux Lite    | 1         | 0.17%   |
| GNOME OS      | 1         | 0.17%   |
| Deepin        | 1         | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 15        | 2.39%   |
| 5.4.0-26-generic         | 9         | 1.43%   |
| 5.3.0-46-generic         | 8         | 1.27%   |
| 5.15.0-47-generic        | 8         | 1.27%   |
| 5.10.14-desktop-1omv4002 | 8         | 1.27%   |
| 5.4.0-58-generic         | 7         | 1.11%   |
| 5.4.0-52-generic         | 7         | 1.11%   |
| 5.3.0-40-generic         | 7         | 1.11%   |
| 5.15.0-56-generic        | 7         | 1.11%   |
| 5.11.0-27-generic        | 7         | 1.11%   |
| 5.4.0-48-generic         | 6         | 0.96%   |
| 5.11.0-41-generic        | 6         | 0.96%   |
| 5.0.0-23-generic         | 6         | 0.96%   |
| 5.8.0-63-generic         | 5         | 0.8%    |
| 5.8.0-48-generic         | 5         | 0.8%    |
| 5.16.7-desktop-1omv4003  | 5         | 0.8%    |
| 5.15.0-58-generic        | 5         | 0.8%    |
| 5.0.0-37-generic         | 5         | 0.8%    |
| 5.0.0-25-generic         | 5         | 0.8%    |
| 5.0.0-13-generic         | 5         | 0.8%    |
| 4.18.0-15-generic        | 5         | 0.8%    |
| 5.8.0-50-generic         | 4         | 0.64%   |
| 5.3.0-51-generic         | 4         | 0.64%   |
| 5.19.0-35-generic        | 4         | 0.64%   |
| 5.13.0-30-generic        | 4         | 0.64%   |
| 4.18.0-25-generic        | 4         | 0.64%   |
| 4.18.0-18-generic        | 4         | 0.64%   |
| 4.15.0-29-generic        | 4         | 0.64%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.48%   |
| 6.2.0-20-generic         | 3         | 0.48%   |
| 5.8.0-59-generic         | 3         | 0.48%   |
| 5.8.0-44-generic         | 3         | 0.48%   |
| 5.8.0-43-generic         | 3         | 0.48%   |
| 5.4.0-91-generic         | 3         | 0.48%   |
| 5.4.0-65-generic         | 3         | 0.48%   |
| 5.4.0-59-generic         | 3         | 0.48%   |
| 5.4.0-54-generic         | 3         | 0.48%   |
| 5.4.0-40-generic         | 3         | 0.48%   |
| 5.4.0-37-generic         | 3         | 0.48%   |
| 5.4.0-29-generic         | 3         | 0.48%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 105       | 17.3%   |
| 5.15.0  | 47        | 7.74%   |
| 5.0.0   | 38        | 6.26%   |
| 4.15.0  | 38        | 6.26%   |
| 5.11.0  | 35        | 5.77%   |
| 5.8.0   | 34        | 5.6%    |
| 5.3.0   | 33        | 5.44%   |
| 5.13.0  | 29        | 4.78%   |
| 4.18.0  | 25        | 4.12%   |
| 5.19.0  | 15        | 2.47%   |
| 5.10.0  | 14        | 2.31%   |
| 5.10.14 | 8         | 1.32%   |
| 5.16.7  | 6         | 0.99%   |
| 4.13.0  | 6         | 0.99%   |
| 5.8.18  | 4         | 0.66%   |
| 5.11.11 | 4         | 0.66%   |
| 6.2.6   | 3         | 0.49%   |
| 6.2.0   | 3         | 0.49%   |
| 6.0.9   | 3         | 0.49%   |
| 5.9.16  | 3         | 0.49%   |
| 5.6.0   | 3         | 0.49%   |
| 5.18.0  | 3         | 0.49%   |
| 5.16.15 | 3         | 0.49%   |
| 5.16.0  | 3         | 0.49%   |
| 5.14.16 | 3         | 0.49%   |
| 5.13.19 | 3         | 0.49%   |
| 6.2.8   | 2         | 0.33%   |
| 6.2.12  | 2         | 0.33%   |
| 6.2.11  | 2         | 0.33%   |
| 6.0.0   | 2         | 0.33%   |
| 5.9.14  | 2         | 0.33%   |
| 5.7.6   | 2         | 0.33%   |
| 5.7.0   | 2         | 0.33%   |
| 5.17.0  | 2         | 0.33%   |
| 5.15.4  | 2         | 0.33%   |
| 5.13.7  | 2         | 0.33%   |
| 5.13.13 | 2         | 0.33%   |
| 5.12.8  | 2         | 0.33%   |
| 5.10.13 | 2         | 0.33%   |
| 4.9.60  | 2         | 0.33%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 111       | 18.44%  |
| 5.15    | 60        | 9.97%   |
| 5.8     | 46        | 7.64%   |
| 5.11    | 43        | 7.14%   |
| 5.0     | 41        | 6.81%   |
| 5.13    | 38        | 6.31%   |
| 4.15    | 38        | 6.31%   |
| 5.3     | 34        | 5.65%   |
| 5.10    | 33        | 5.48%   |
| 4.18    | 25        | 4.15%   |
| 5.19    | 17        | 2.82%   |
| 5.16    | 17        | 2.82%   |
| 6.2     | 12        | 1.99%   |
| 5.14    | 11        | 1.83%   |
| 5.9     | 8         | 1.33%   |
| 5.18    | 8         | 1.33%   |
| 6.0     | 7         | 1.16%   |
| 5.6     | 7         | 1.16%   |
| 5.12    | 7         | 1.16%   |
| 6.1     | 6         | 1%      |
| 4.13    | 6         | 1%      |
| 5.7     | 5         | 0.83%   |
| 4.19    | 5         | 0.83%   |
| 5.17    | 3         | 0.5%    |
| 4.9     | 3         | 0.5%    |
| 6.3     | 2         | 0.33%   |
| 5.5     | 2         | 0.33%   |
| 4.14    | 2         | 0.33%   |
| 5.2     | 1         | 0.17%   |
| 4.5     | 1         | 0.17%   |
| 4.20    | 1         | 0.17%   |
| 4.12    | 1         | 0.17%   |
| 3.10    | 1         | 0.17%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 551       | 97.01%  |
| i686    | 15        | 2.64%   |
| aarch64 | 2         | 0.35%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 318       | 54.36%  |
| Unknown         | 94        | 16.07%  |
| KDE5            | 55        | 9.4%    |
| XFCE            | 45        | 7.69%   |
| KDE             | 17        | 2.91%   |
| X-Cinnamon      | 15        | 2.56%   |
| i3              | 9         | 1.54%   |
| Unity           | 5         | 0.85%   |
| MATE            | 5         | 0.85%   |
| LXQt            | 5         | 0.85%   |
| Pantheon        | 4         | 0.68%   |
| Budgie          | 4         | 0.68%   |
| KDE4            | 2         | 0.34%   |
| Cinnamon        | 2         | 0.34%   |
| Trinity         | 1         | 0.17%   |
| sway            | 1         | 0.17%   |
| LXDE            | 1         | 0.17%   |
| GNOME Flashback | 1         | 0.17%   |
| bspwm           | 1         | 0.17%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 427       | 73.12%  |
| Wayland | 87        | 14.9%   |
| Unknown | 65        | 11.13%  |
| Tty     | 5         | 0.86%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 315       | 53.57%  |
| GDM     | 89        | 15.14%  |
| GDM3    | 69        | 11.73%  |
| SDDM    | 53        | 9.01%   |
| LightDM | 43        | 7.31%   |
| TDM     | 14        | 2.38%   |
| Ly      | 2         | 0.34%   |
| KDM     | 2         | 0.34%   |
| XDM     | 1         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 440       | 76.26%  |
| Unknown | 91        | 15.77%  |
| en_GB   | 15        | 2.6%    |
| fa_IR   | 13        | 2.25%   |
| C       | 8         | 1.39%   |
| en_CA   | 5         | 0.87%   |
| POSIX   | 1         | 0.17%   |
| ja_JP   | 1         | 0.17%   |
| en_AG   | 1         | 0.17%   |
| de_DE   | 1         | 0.17%   |
| az_IR   | 1         | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 317       | 54.75%  |
| EFI  | 262       | 45.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 479       | 83.16%  |
| Btrfs   | 35        | 6.08%   |
| Overlay | 28        | 4.86%   |
| Unknown | 18        | 3.13%   |
| Zfs     | 6         | 1.04%   |
| Xfs     | 6         | 1.04%   |
| Tmpfs   | 2         | 0.35%   |
| Ext3    | 1         | 0.17%   |
| Ext2    | 1         | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 353       | 61.39%  |
| GPT     | 175       | 30.43%  |
| MBR     | 47        | 8.17%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 489       | 84.75%  |
| Yes       | 88        | 15.25%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 307       | 53.48%  |
| Yes       | 267       | 46.52%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 197       | 34.68%  |
| Lenovo                  | 109       | 19.19%  |
| Hewlett-Packard         | 76        | 13.38%  |
| Dell                    | 38        | 6.69%   |
| Acer                    | 38        | 6.69%   |
| Gigabyte Technology     | 35        | 6.16%   |
| MSI                     | 19        | 3.35%   |
| Sony                    | 12        | 2.11%   |
| Toshiba                 | 7         | 1.23%   |
| ECS                     | 6         | 1.06%   |
| ASRock                  | 5         | 0.88%   |
| Fujitsu                 | 3         | 0.53%   |
| Unknown                 | 3         | 0.53%   |
| YANYU                   | 2         | 0.35%   |
| Raspberry Pi Foundation | 2         | 0.35%   |
| Microsoft               | 2         | 0.35%   |
| Biostar                 | 2         | 0.35%   |
| Apple                   | 2         | 0.35%   |
| Timi                    | 1         | 0.18%   |
| Supermicro              | 1         | 0.18%   |
| Razer                   | 1         | 0.18%   |
| Packard Bell            | 1         | 0.18%   |
| LG Electronics          | 1         | 0.18%   |
| Intel                   | 1         | 0.18%   |
| HPE                     | 1         | 0.18%   |
| HIGRADED                | 1         | 0.18%   |
| Foxconn                 | 1         | 0.18%   |
| Alienware               | 1         | 0.18%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| ASUS All Series                       | 13        | 2.29%   |
| HP Compaq Elite 8300 SFF              | 7         | 1.23%   |
| Lenovo IdeaPad 330-15IKB 81DE         | 6         | 1.06%   |
| HP ProBook 4540s                      | 6         | 1.06%   |
| Acer Aspire V3-571G                   | 6         | 1.06%   |
| Lenovo IdeaPad Z510 20287             | 4         | 0.7%    |
| HP Pavilion g6                        | 4         | 0.7%    |
| HP EliteBook 8470p                    | 4         | 0.7%    |
| ASUS VivoBook 15_ASUS Laptop X540UBR  | 4         | 0.7%    |
| Lenovo Z50-70 20354                   | 3         | 0.53%   |
| Lenovo IdeaPad 5 15ITL05 82FG         | 3         | 0.53%   |
| Lenovo G50-70 20351                   | 3         | 0.53%   |
| HP EliteBook 840 G2                   | 3         | 0.53%   |
| ASUS X580VD                           | 3         | 0.53%   |
| ASUS P5P41T-LE                        | 3         | 0.53%   |
| ASUS K55VD                            | 3         | 0.53%   |
| Unknown                               | 3         | 0.53%   |
| Toshiba PORTEGE X30-D                 | 2         | 0.35%   |
| MSI Prestige 14 A10RB                 | 2         | 0.35%   |
| Microsoft Surface Book 2              | 2         | 0.35%   |
| Lenovo ThinkPad X250 20CM002XUS       | 2         | 0.35%   |
| Lenovo Legion 5 15IMH05H 81Y6         | 2         | 0.35%   |
| Lenovo Legion 5 15ARH05H 82B1         | 2         | 0.35%   |
| Lenovo IdeaPad S540-15IWL GTX 81SW    | 2         | 0.35%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK | 2         | 0.35%   |
| Lenovo IdeaPad 520-15IKB 81BF         | 2         | 0.35%   |
| Lenovo IdeaPad 5 14ALC05 82LM         | 2         | 0.35%   |
| Lenovo IdeaPad 330-15IGM 81D1         | 2         | 0.35%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 2         | 0.35%   |
| Lenovo G50-80 80E5                    | 2         | 0.35%   |
| Lenovo Flex 2-15 20405                | 2         | 0.35%   |
| Lenovo B570e HuronRiver Platform      | 2         | 0.35%   |
| HP ZBook 15                           | 2         | 0.35%   |
| HP ProLiant DL360 G6                  | 2         | 0.35%   |
| HP ProBook 450 G4                     | 2         | 0.35%   |
| HP Pavilion dv6                       | 2         | 0.35%   |
| HP Laptop 15-bs0xx                    | 2         | 0.35%   |
| HP EliteDesk 800 G2 SFF               | 2         | 0.35%   |
| HP EliteBook Revolve 810 G3           | 2         | 0.35%   |
| HP EliteBook 8570p                    | 2         | 0.35%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 41        | 7.22%   |
| ASUS VivoBook      | 33        | 5.81%   |
| Acer Aspire        | 32        | 5.63%   |
| Lenovo ThinkPad    | 29        | 5.11%   |
| HP EliteBook       | 22        | 3.87%   |
| ASUS PRIME         | 18        | 3.17%   |
| Dell Inspiron      | 14        | 2.46%   |
| HP ProBook         | 13        | 2.29%   |
| ASUS All           | 13        | 2.29%   |
| Dell Latitude      | 12        | 2.11%   |
| HP Pavilion        | 10        | 1.76%   |
| HP Compaq          | 9         | 1.58%   |
| Dell Vostro        | 8         | 1.41%   |
| Lenovo Legion      | 7         | 1.23%   |
| ASUS ROG           | 7         | 1.23%   |
| ASUS ASUS          | 6         | 1.06%   |
| Toshiba Satellite  | 4         | 0.7%    |
| Toshiba PORTEGE    | 3         | 0.53%   |
| MSI Modern         | 3         | 0.53%   |
| Lenovo Z50-70      | 3         | 0.53%   |
| Lenovo ThinkBook   | 3         | 0.53%   |
| Lenovo G50-70      | 3         | 0.53%   |
| HP ZBook           | 3         | 0.53%   |
| HP ProLiant        | 3         | 0.53%   |
| HP EliteDesk       | 3         | 0.53%   |
| Fujitsu LIFEBOOK   | 3         | 0.53%   |
| ASUS X580VD        | 3         | 0.53%   |
| ASUS TUF           | 3         | 0.53%   |
| ASUS P5P41T-LE     | 3         | 0.53%   |
| ASUS K55VD         | 3         | 0.53%   |
| Acer TravelMate    | 3         | 0.53%   |
| Unknown            | 3         | 0.53%   |
| RPi Raspberry      | 2         | 0.35%   |
| MSI Prestige       | 2         | 0.35%   |
| MSI GE60           | 2         | 0.35%   |
| Microsoft Surface  | 2         | 0.35%   |
| Lenovo ThinkCentre | 2         | 0.35%   |
| Lenovo G580        | 2         | 0.35%   |
| Lenovo G50-80      | 2         | 0.35%   |
| Lenovo Flex        | 2         | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2013    | 60        | 10.56%  |
| 2012    | 52        | 9.15%   |
| 2017    | 46        | 8.1%    |
| 2011    | 44        | 7.75%   |
| 2020    | 39        | 6.87%   |
| 2019    | 39        | 6.87%   |
| 2018    | 39        | 6.87%   |
| 2010    | 39        | 6.87%   |
| 2015    | 38        | 6.69%   |
| 2016    | 37        | 6.51%   |
| 2014    | 33        | 5.81%   |
| 2009    | 28        | 4.93%   |
| 2021    | 24        | 4.23%   |
| 2008    | 16        | 2.82%   |
| 2022    | 12        | 2.11%   |
| 2007    | 9         | 1.58%   |
| 2006    | 8         | 1.41%   |
| 2005    | 2         | 0.35%   |
| Unknown | 2         | 0.35%   |
| 2004    | 1         | 0.18%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 403       | 70.95%  |
| Desktop        | 148       | 26.06%  |
| Server         | 6         | 1.06%   |
| Tablet         | 5         | 0.88%   |
| Convertible    | 4         | 0.7%    |
| System on chip | 2         | 0.35%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 534       | 93.85%  |
| Enabled  | 35        | 6.15%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 568       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 175       | 30.65%  |
| 8.01-16.0       | 121       | 21.19%  |
| 3.01-4.0        | 112       | 19.61%  |
| 16.01-24.0      | 103       | 18.04%  |
| 32.01-64.0      | 21        | 3.68%   |
| 1.01-2.0        | 17        | 2.98%   |
| 2.01-3.0        | 10        | 1.75%   |
| 64.01-256.0     | 5         | 0.88%   |
| 0.51-1.0        | 4         | 0.7%    |
| 24.01-32.0      | 2         | 0.35%   |
| More than 256.0 | 1         | 0.18%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 214       | 34.97%  |
| 2.01-3.0   | 177       | 28.92%  |
| 3.01-4.0   | 99        | 16.18%  |
| 4.01-8.0   | 70        | 11.44%  |
| 0.51-1.0   | 31        | 5.07%   |
| 8.01-16.0  | 14        | 2.29%   |
| 0.01-0.5   | 5         | 0.82%   |
| 24.01-32.0 | 1         | 0.16%   |
| 16.01-24.0 | 1         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 368       | 63.67%  |
| 2       | 172       | 29.76%  |
| 3       | 25        | 4.33%   |
| 4       | 7         | 1.21%   |
| 0       | 3         | 0.52%   |
| 5       | 2         | 0.35%   |
| Unknown | 1         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 310       | 54.01%  |
| Yes       | 264       | 45.99%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 496       | 87.17%  |
| No        | 73        | 12.83%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 82.72%  |
| No        | 99        | 17.28%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 62.59%  |
| No        | 214       | 37.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Iran    | 568       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Tehran                         | 327       | 54.96%  |
| TehrДЃn                      | 46        | 7.73%   |
| Mashhad                        | 25        | 4.2%    |
| Isfahan                        | 18        | 3.03%   |
| Tajrish                        | 9         | 1.51%   |
| Shiraz                         | 9         | 1.51%   |
| Karaj                          | 9         | 1.51%   |
| Qom                            | 7         | 1.18%   |
| Tabriz                         | 6         | 1.01%   |
| Rasht                          | 6         | 1.01%   |
| Khorramshahr                   | 6         | 1.01%   |
| Sanandij                       | 5         | 0.84%   |
| Kerman                         | 5         | 0.84%   |
| Babol                          | 5         | 0.84%   |
| Ahvaz                          | 4         | 0.67%   |
| Yazd                           | 3         | 0.5%    |
| TajrД«sh                     | 3         | 0.5%    |
| Rey                            | 3         | 0.5%    |
| Gorgan                         | 3         | 0.5%    |
| Arak                           | 3         | 0.5%    |
| Zanjan                         | 2         | 0.34%   |
| Shahre Jadide Andisheh         | 2         | 0.34%   |
| Shahr-e Qods                   | 2         | 0.34%   |
| Rehnān                        | 2         | 0.34%   |
| Qazvin                         | 2         | 0.34%   |
| Kermanshah                     | 2         | 0.34%   |
| Hamadan                        | 2         | 0.34%   |
| Gachsaran                      | 2         | 0.34%   |
| DamДЃvand                    | 2         | 0.34%   |
| BorЕ«jerd                    | 2         | 0.34%   |
| Behshahr                       | 2         | 0.34%   |
| ДЂstДЃneh-ye AshrafД«yeh | 1         | 0.17%   |
| Varamin                        | 1         | 0.17%   |
| Tīrān                        | 1         | 0.17%   |
| Şowmeeh Sarā                 | 1         | 0.17%   |
| Siakhdekhan                    | 1         | 0.17%   |
| ShДЃhД«n Shahr             | 1         | 0.17%   |
| Shirvan                        | 1         | 0.17%   |
| ShahrД«ДЃr                 | 1         | 0.17%   |
| Shahrak-e KÅ«lÅ«rÄ«      | 1         | 0.17%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                  | Computers | Drives | Percent |
|-------------------------|-----------|--------|---------|
| WDC                     | 157       | 195    | 20.91%  |
| Seagate                 | 134       | 160    | 17.84%  |
| Toshiba                 | 95        | 109    | 12.65%  |
| Samsung Electronics     | 90        | 110    | 11.98%  |
| A-DATA Technology       | 33        | 40     | 4.39%   |
| Micron Technology       | 24        | 26     | 3.2%    |
| SanDisk                 | 23        | 27     | 3.06%   |
| Maxtor                  | 20        | 27     | 2.66%   |
| HGST                    | 20        | 24     | 2.66%   |
| Intel                   | 16        | 16     | 2.13%   |
| Unknown                 | 15        | 16     | 2%      |
| Kingston                | 14        | 19     | 1.86%   |
| Lexar                   | 13        | 14     | 1.73%   |
| SK hynix                | 12        | 13     | 1.6%    |
| Hitachi                 | 11        | 12     | 1.46%   |
| SPCC                    | 6         | 7      | 0.8%    |
| Plextor                 | 4         | 4      | 0.53%   |
| Kingmax                 | 4         | 4      | 0.53%   |
| Gigabyte Technology     | 4         | 4      | 0.53%   |
| Apacer                  | 4         | 4      | 0.53%   |
| Silicon Motion          | 3         | 3      | 0.4%    |
| PNY                     | 3         | 4      | 0.4%    |
| Unknown                 | 3         | 3      | 0.4%    |
| Union Memory            | 2         | 2      | 0.27%   |
| Team                    | 2         | 2      | 0.27%   |
| Realtek Semiconductor   | 2         | 3      | 0.27%   |
| OCZ                     | 2         | 2      | 0.27%   |
| LITEONIT                | 2         | 3      | 0.27%   |
| LITEON                  | 2         | 3      | 0.27%   |
| Biostar                 | 2         | 3      | 0.27%   |
| Apple                   | 2         | 2      | 0.27%   |
| XPG                     | 1         | 1      | 0.13%   |
| VC-500                  | 1         | 1      | 0.13%   |
| ValueTech               | 1         | 2      | 0.13%   |
| USB3.0                  | 1         | 1      | 0.13%   |
| Union Memory (Shenzhen) | 1         | 1      | 0.13%   |
| UMIS                    | 1         | 1      | 0.13%   |
| TwinMOS                 | 1         | 1      | 0.13%   |
| Transcend               | 1         | 1      | 0.13%   |
| Pioneer                 | 1         | 1      | 0.13%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 36        | 4.62%   |
| Toshiba MQ01ABD100 1TB              | 20        | 2.57%   |
| Toshiba MQ04ABF100 1TB              | 17        | 2.18%   |
| WDC WD10EZEX-08WN4A0 1TB            | 13        | 1.67%   |
| Seagate ST9500325AS 500GB           | 11        | 1.41%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 11        | 1.41%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 10        | 1.28%   |
| WDC WD10SPZX-08Z10 1TB              | 9         | 1.16%   |
| Toshiba MQ01ABF050 500GB            | 9         | 1.16%   |
| Samsung SSD 860 EVO 500GB           | 9         | 1.16%   |
| Samsung SSD 860 EVO 250GB           | 9         | 1.16%   |
| WDC WD10SPZX-24Z10 1TB              | 8         | 1.03%   |
| WDC WD10JPCX-24UE4T0 1TB            | 7         | 0.9%    |
| A-DATA SU650 120GB SSD              | 7         | 0.9%    |
| Seagate ST500DM002-1BD142 500GB     | 6         | 0.77%   |
| Micron 2210_MTFDHBA512QFD 512GB     | 6         | 0.77%   |
| Maxtor STM3250310AS 250GB           | 6         | 0.77%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5         | 0.64%   |
| Toshiba MQ01ABD050V 500GB           | 5         | 0.64%   |
| Seagate ST9500420AS 500GB           | 5         | 0.64%   |
| Seagate ST2000LM007-1R8174 2TB      | 5         | 0.64%   |
| Samsung SSD 850 EVO 250GB           | 5         | 0.64%   |
| Lexar 128GB SSD                     | 5         | 0.64%   |
| Toshiba MQ01ABD075 752GB            | 4         | 0.51%   |
| Toshiba MQ01ABD050 500GB            | 4         | 0.51%   |
| Seagate ST500LT012-1DG142 500GB     | 4         | 0.51%   |
| Seagate ST2000LM003 HN-M201RAD 2TB  | 4         | 0.51%   |
| Samsung NVMe SSD Drive 256GB        | 4         | 0.51%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 4         | 0.51%   |
| Lexar 256GB SSD                     | 4         | 0.51%   |
| Intel NVMe SSD Drive 512GB          | 4         | 0.51%   |
| HGST HTS721010A9E630 1TB            | 4         | 0.51%   |
| HGST HTS541010B7E610 1TB            | 4         | 0.51%   |
| HGST HTS541010A9E680 1TB            | 4         | 0.51%   |
| WDC WDS480G2G0A-00JH30 480GB SSD    | 3         | 0.39%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD    | 3         | 0.39%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 3         | 0.39%   |
| WDC WD10SPZX-80Z10T2 1TB            | 3         | 0.39%   |
| WDC WD10EZRX-00L4HB0 1TB            | 3         | 0.39%   |
| WDC WD10EARS-00MVWB0 1TB            | 3         | 0.39%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 134       | 162    | 31.98%  |
| Seagate             | 134       | 160    | 31.98%  |
| Toshiba             | 87        | 97     | 20.76%  |
| Maxtor              | 20        | 27     | 4.77%   |
| HGST                | 20        | 24     | 4.77%   |
| Hitachi             | 11        | 12     | 2.63%   |
| Samsung Electronics | 7         | 11     | 1.67%   |
| Unknown             | 2         | 2      | 0.48%   |
| USB3.0              | 1         | 1      | 0.24%   |
| HPE                 | 1         | 1      | 0.24%   |
| Fujitsu             | 1         | 1      | 0.24%   |
| Apple               | 1         | 1      | 0.24%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 55        | 66     | 24.66%  |
| A-DATA Technology   | 33        | 40     | 14.8%   |
| WDC                 | 25        | 28     | 11.21%  |
| SanDisk             | 15        | 18     | 6.73%   |
| Micron Technology   | 11        | 11     | 4.93%   |
| Lexar               | 11        | 12     | 4.93%   |
| Kingston            | 11        | 15     | 4.93%   |
| SPCC                | 6         | 7      | 2.69%   |
| SK hynix            | 6         | 6      | 2.69%   |
| Toshiba             | 5         | 9      | 2.24%   |
| Plextor             | 4         | 4      | 1.79%   |
| Intel               | 4         | 4      | 1.79%   |
| Gigabyte Technology | 4         | 4      | 1.79%   |
| Apacer              | 4         | 4      | 1.79%   |
| Team                | 2         | 2      | 0.9%    |
| PNY                 | 2         | 2      | 0.9%    |
| OCZ                 | 2         | 2      | 0.9%    |
| LITEONIT            | 2         | 3      | 0.9%    |
| LITEON              | 2         | 3      | 0.9%    |
| Kingmax             | 2         | 2      | 0.9%    |
| Biostar             | 2         | 3      | 0.9%    |
| ValueTech           | 1         | 2      | 0.45%   |
| TwinMOS             | 1         | 1      | 0.45%   |
| Transcend           | 1         | 1      | 0.45%   |
| Pioneer             | 1         | 1      | 0.45%   |
| Patriot             | 1         | 1      | 0.45%   |
| OSCOO               | 1         | 2      | 0.45%   |
| MSI                 | 1         | 1      | 0.45%   |
| KODAK               | 1         | 1      | 0.45%   |
| GeIL                | 1         | 1      | 0.45%   |
| Crucial             | 1         | 1      | 0.45%   |
| China               | 1         | 1      | 0.45%   |
| BR                  | 1         | 1      | 0.45%   |
| Apple               | 1         | 1      | 0.45%   |
| AMD                 | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 394       | 499    | 54.72%  |
| SSD     | 214       | 262    | 29.72%  |
| NVMe    | 96        | 112    | 13.33%  |
| MMC     | 11        | 12     | 1.53%   |
| Unknown | 5         | 6      | 0.69%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 501       | 755    | 81.07%  |
| NVMe | 96        | 112    | 15.53%  |
| MMC  | 11        | 12     | 1.78%   |
| SAS  | 10        | 12     | 1.62%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 327       | 439    | 55.24%  |
| 0.51-1.0   | 232       | 283    | 39.19%  |
| 1.01-2.0   | 20        | 23     | 3.38%   |
| 3.01-4.0   | 5         | 5      | 0.84%   |
| 2.01-3.0   | 4         | 5      | 0.68%   |
| 4.01-10.0  | 3         | 3      | 0.51%   |
| 10.01-20.0 | 1         | 3      | 0.17%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 166       | 28.04%  |
| 251-500        | 114       | 19.26%  |
| 501-1000       | 108       | 18.24%  |
| 51-100         | 54        | 9.12%   |
| 1001-2000      | 47        | 7.94%   |
| 1-20           | 36        | 6.08%   |
| 21-50          | 34        | 5.74%   |
| Unknown        | 13        | 2.2%    |
| More than 3000 | 10        | 1.69%   |
| 2001-3000      | 10        | 1.69%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 227       | 37.46%  |
| 21-50          | 102       | 16.83%  |
| 51-100         | 76        | 12.54%  |
| 101-250        | 74        | 12.21%  |
| 251-500        | 48        | 7.92%   |
| 501-1000       | 48        | 7.92%   |
| Unknown        | 13        | 2.15%   |
| 1001-2000      | 8         | 1.32%   |
| More than 3000 | 6         | 0.99%   |
| 2001-3000      | 4         | 0.66%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| Seagate ST1000LM035-1RK172 1TB                 | 4         | 5      | 7.14%   |
| Toshiba MQ01ABD100 1TB                         | 3         | 3      | 5.36%   |
| Seagate ST9500420AS 500GB                      | 3         | 3      | 5.36%   |
| Seagate ST9500325AS 500GB                      | 3         | 3      | 5.36%   |
| Toshiba MQ01ABF050 500GB                       | 2         | 2      | 3.57%   |
| Toshiba MQ01ABD075 752GB                       | 2         | 2      | 3.57%   |
| Toshiba MQ01ABD050 500GB                       | 2         | 2      | 3.57%   |
| HGST HTS541075A9E680 752GB                     | 2         | 2      | 3.57%   |
| WDC WDS120G2G0A-00JH30 120GB SSD               | 1         | 1      | 1.79%   |
| WDC WD5000LPVX-80V0TT0 500GB                   | 1         | 1      | 1.79%   |
| WDC WD5000AAKX-22ERMA0 500GB                   | 1         | 2      | 1.79%   |
| WDC WD3200BPVT-75ZEST0 320GB                   | 1         | 1      | 1.79%   |
| WDC WD3200AVVS-62L2B0 320GB                    | 1         | 1      | 1.79%   |
| WDC WD10SPZX-24Z10 1TB                         | 1         | 1      | 1.79%   |
| WDC WD10SPZX-08Z10 1TB                         | 1         | 1      | 1.79%   |
| WDC WD10PURZ-85U8XY0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD10JPCX-24UE4T0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD10EZEX-00WN4A0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD10EARX-00N0YB0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD10EARS-00MVWB0 1TB                       | 1         | 1      | 1.79%   |
| WDC WD1002FBYS-18A6B0 1TB                      | 1         | 1      | 1.79%   |
| Toshiba MQ04ABF100 1TB                         | 1         | 1      | 1.79%   |
| Toshiba MK3265GSXN 320GB                       | 1         | 1      | 1.79%   |
| Toshiba MK3263GSX 320GB                        | 1         | 1      | 1.79%   |
| Toshiba HDWD105 500GB                          | 1         | 1      | 1.79%   |
| SK hynix SC308 SATA 256GB SSD                  | 1         | 1      | 1.79%   |
| Seagate ST9250315AS 250GB                      | 1         | 2      | 1.79%   |
| Seagate ST3500413AS 500GB                      | 1         | 1      | 1.79%   |
| Seagate ST3320613AS 320GB                      | 1         | 1      | 1.79%   |
| Seagate ST320LT020-9YG142 320GB                | 1         | 1      | 1.79%   |
| Seagate ST1000LM014-SSHD-8GB                   | 1         | 1      | 1.79%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 1.79%   |
| Samsung Electronics SSD 870 EVO 1TB            | 1         | 2      | 1.79%   |
| Samsung Electronics HD502HI 500GB              | 1         | 2      | 1.79%   |
| Micron Technology 1100_MTFDDAV512TBN 512GB SSD | 1         | 1      | 1.79%   |
| Maxtor 6Y080M0 80GB                            | 1         | 1      | 1.79%   |
| Hitachi HTS547575A9E384 752GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS545025B9A300 250GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS542512K9SA00 120GB                  | 1         | 1      | 1.79%   |
| Hitachi HTS541080G9SA00 80GB                   | 1         | 1      | 1.79%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 28.57%  |
| WDC                 | 13        | 14     | 23.21%  |
| Toshiba             | 13        | 13     | 23.21%  |
| Hitachi             | 6         | 7      | 10.71%  |
| HGST                | 3         | 3      | 5.36%   |
| Samsung Electronics | 2         | 4      | 3.57%   |
| SK hynix            | 1         | 1      | 1.79%   |
| Micron Technology   | 1         | 1      | 1.79%   |
| Maxtor              | 1         | 1      | 1.79%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 16        | 18     | 30.77%  |
| Toshiba             | 13        | 13     | 25%     |
| WDC                 | 12        | 13     | 23.08%  |
| Hitachi             | 6         | 7      | 11.54%  |
| HGST                | 3         | 3      | 5.77%   |
| Samsung Electronics | 1         | 2      | 1.92%   |
| Maxtor              | 1         | 1      | 1.92%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 49        | 57     | 92.45%  |
| SSD  | 4         | 5      | 7.55%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22A0RT0 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 371       | 585    | 62.25%  |
| Works    | 172       | 243    | 28.86%  |
| Malfunc  | 52        | 62     | 8.72%   |
| Failed   | 1         | 1      | 0.17%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 481       | 74.69%  |
| AMD                              | 47        | 7.3%    |
| Samsung Electronics              | 32        | 4.97%   |
| SanDisk                          | 13        | 2.02%   |
| Micron Technology                | 13        | 2.02%   |
| SK hynix                         | 6         | 0.93%   |
| Nvidia                           | 6         | 0.93%   |
| Union Memory (Shenzhen)          | 5         | 0.78%   |
| Phison Electronics               | 5         | 0.78%   |
| Silicon Motion                   | 4         | 0.62%   |
| Marvell Technology Group         | 4         | 0.62%   |
| VIA Technologies                 | 3         | 0.47%   |
| Kingston Technology Company      | 3         | 0.47%   |
| Hewlett-Packard                  | 3         | 0.47%   |
| ASMedia Technology               | 3         | 0.47%   |
| Toshiba America Info Systems     | 2         | 0.31%   |
| Shenzhen Longsys Electronics     | 2         | 0.31%   |
| Realtek Semiconductor            | 2         | 0.31%   |
| JMicron Technology               | 2         | 0.31%   |
| ADATA Technology                 | 2         | 0.31%   |
| ULi Electronics                  | 1         | 0.16%   |
| Silicon Integrated Systems [SiS] | 1         | 0.16%   |
| Micron/Crucial Technology        | 1         | 0.16%   |
| MAXIO Technology (Hangzhou)      | 1         | 0.16%   |
| KIOXIA                           | 1         | 0.16%   |
| Adaptec                          | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 53        | 7.22%   |
| AMD FCH SATA Controller [AHCI mode]                                                     | 44        | 5.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 39        | 5.31%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 38        | 5.18%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 30        | 4.09%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 23        | 3.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 22        | 3%      |
| Intel Volume Management Device NVMe RAID Controller                                     | 22        | 3%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 21        | 2.86%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 21        | 2.86%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 20        | 2.72%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 18        | 2.45%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 14        | 1.91%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 14        | 1.91%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 14        | 1.91%   |
| Micron NVMe Storage Controller                                                          | 13        | 1.77%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 11        | 1.5%    |
| Samsung NVMe SSD Controller 980                                                         | 10        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.36%   |
| Intel SSD 660P Series                                                                   | 9         | 1.23%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 1.23%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 8         | 1.09%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 8         | 1.09%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 7         | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 7         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 7         | 0.95%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 7         | 0.95%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6         | 0.82%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 0.82%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 6         | 0.82%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 6         | 0.82%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 6         | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 6         | 0.82%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 5         | 0.68%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 0.68%   |
| Intel SATA Controller [RAID mode]                                                       | 5         | 0.68%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 5         | 0.68%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 5         | 0.68%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 5         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 421       | 63.98%  |
| NVMe | 97        | 14.74%  |
| IDE  | 79        | 12.01%  |
| RAID | 60        | 9.12%   |
| SAS  | 1         | 0.15%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 507       | 89.26%  |
| AMD    | 59        | 10.39%  |
| ARM    | 2         | 0.35%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz           | 21        | 3.7%    |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 14        | 2.46%   |
| Intel Core i7-7500U CPU @ 2.70GHz           | 13        | 2.29%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 11        | 1.94%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 9         | 1.58%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 9         | 1.58%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 9         | 1.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 9         | 1.58%   |
| Intel Core i7-10510U CPU @ 1.80GHz          | 8         | 1.41%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 8         | 1.41%   |
| Intel Core i7-8565U CPU @ 1.80GHz           | 7         | 1.23%   |
| Intel Core i7-4702MQ CPU @ 2.20GHz          | 7         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 7         | 1.23%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 7         | 1.23%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 6         | 1.06%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 6         | 1.06%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 5         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 5         | 0.88%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 5         | 0.88%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 5         | 0.88%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 5         | 0.88%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 5         | 0.88%   |
| Intel Core i5-2430M CPU @ 2.40GHz           | 5         | 0.88%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz     | 5         | 0.88%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 5         | 0.88%   |
| Intel Pentium Dual-Core CPU E5700 @ 3.00GHz | 4         | 0.7%    |
| Intel Core i7-5500U CPU @ 2.40GHz           | 4         | 0.7%    |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 4         | 0.7%    |
| Intel Core i5-8400 CPU @ 2.80GHz            | 4         | 0.7%    |
| Intel Core i5-5300U CPU @ 2.30GHz           | 4         | 0.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4         | 0.7%    |
| Intel Core i5 CPU M 480 @ 2.67GHz           | 4         | 0.7%    |
| Intel Celeron N4000 CPU @ 1.10GHz           | 4         | 0.7%    |
| Intel 12th Gen Core i7-12700H               | 4         | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 4         | 0.7%    |
| Intel Core i7-8750H CPU @ 2.20GHz           | 3         | 0.53%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 3         | 0.53%   |
| Intel Core i7-4770K CPU @ 3.50GHz           | 3         | 0.53%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 3         | 0.53%   |
| Intel Core i7-2620M CPU @ 2.70GHz           | 3         | 0.53%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 174       | 30.63%  |
| Intel Core i5           | 149       | 26.23%  |
| Intel Core i3           | 40        | 7.04%   |
| Other                   | 33        | 5.81%   |
| Intel Core 2 Duo        | 29        | 5.11%   |
| Intel Pentium           | 26        | 4.58%   |
| AMD Ryzen 7             | 17        | 2.99%   |
| Intel Celeron           | 14        | 2.46%   |
| Intel Pentium Dual-Core | 9         | 1.58%   |
| AMD Ryzen 5             | 8         | 1.41%   |
| Intel Atom              | 7         | 1.23%   |
| Intel Xeon              | 6         | 1.06%   |
| Intel Core 2 Quad       | 6         | 1.06%   |
| AMD FX                  | 5         | 0.88%   |
| AMD E1                  | 4         | 0.7%    |
| Intel Xeon Gold         | 3         | 0.53%   |
| Intel Pentium Dual      | 3         | 0.53%   |
| Intel Genuine           | 3         | 0.53%   |
| AMD Ryzen 3             | 3         | 0.53%   |
| AMD A4                  | 3         | 0.53%   |
| AMD A10                 | 3         | 0.53%   |
| Intel Pentium Silver    | 2         | 0.35%   |
| Intel Pentium 4         | 2         | 0.35%   |
| AMD PRO A10             | 2         | 0.35%   |
| AMD Athlon 64 X2        | 2         | 0.35%   |
| AMD Athlon 64           | 2         | 0.35%   |
| Intel Pentium D         | 1         | 0.18%   |
| Intel Core M            | 1         | 0.18%   |
| Intel Core i9           | 1         | 0.18%   |
| Intel Core Duo          | 1         | 0.18%   |
| ARM BCM                 | 1         | 0.18%   |
| AMD Ryzen 9             | 1         | 0.18%   |
| AMD PRO A8              | 1         | 0.18%   |
| AMD Phenom II X4        | 1         | 0.18%   |
| AMD E2                  | 1         | 0.18%   |
| AMD Athlon II X3        | 1         | 0.18%   |
| AMD Athlon II X2        | 1         | 0.18%   |
| AMD Athlon              | 1         | 0.18%   |
| AMD A6                  | 1         | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 286       | 50.35%  |
| 4      | 200       | 35.21%  |
| 8      | 30        | 5.28%   |
| 6      | 28        | 4.93%   |
| 1      | 10        | 1.76%   |
| 14     | 7         | 1.23%   |
| 24     | 2         | 0.35%   |
| 3      | 2         | 0.35%   |
| 52     | 1         | 0.18%   |
| 44     | 1         | 0.18%   |
| 12     | 1         | 0.18%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 561       | 98.77%  |
| 2      | 7         | 1.23%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 409       | 71.88%  |
| 1      | 160       | 28.12%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 551       | 96.67%  |
| Unknown        | 13        | 2.28%   |
| 32-bit         | 6         | 1.05%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 116       | 20%     |
| 0x306a9    | 50        | 8.62%   |
| 0x306c3    | 34        | 5.86%   |
| 0x206a7    | 32        | 5.52%   |
| 0x806ea    | 27        | 4.66%   |
| 0x1067a    | 25        | 4.31%   |
| 0x306d4    | 23        | 3.97%   |
| 0x20655    | 22        | 3.79%   |
| 0x806e9    | 17        | 2.93%   |
| 0x906e9    | 16        | 2.76%   |
| 0x506e3    | 16        | 2.76%   |
| 0x806ec    | 14        | 2.41%   |
| 0x40651    | 13        | 2.24%   |
| 0x906ea    | 12        | 2.07%   |
| 0x806c1    | 10        | 1.72%   |
| 0x406e3    | 9         | 1.55%   |
| 0x906a3    | 7         | 1.21%   |
| 0x6fd      | 7         | 1.21%   |
| 0x20652    | 7         | 1.21%   |
| 0xa0652    | 6         | 1.03%   |
| 0x106e5    | 6         | 1.03%   |
| 0x706e5    | 5         | 0.86%   |
| 0x10676    | 5         | 0.86%   |
| 0x706a1    | 4         | 0.69%   |
| 0x6fb      | 4         | 0.69%   |
| 0x08608103 | 4         | 0.69%   |
| 0x0700010f | 4         | 0.69%   |
| 0x906ed    | 3         | 0.52%   |
| 0x806d1    | 3         | 0.52%   |
| 0x30678    | 3         | 0.52%   |
| 0x106ca    | 3         | 0.52%   |
| 0x08108109 | 3         | 0.52%   |
| 0x0600611a | 3         | 0.52%   |
| 0x06003106 | 3         | 0.52%   |
| 0xa0653    | 2         | 0.34%   |
| 0x906eb    | 2         | 0.34%   |
| 0x90672    | 2         | 0.34%   |
| 0x6e8      | 2         | 0.34%   |
| 0x50654    | 2         | 0.34%   |
| 0x406c4    | 2         | 0.34%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 117       | 20.6%   |
| Haswell          | 67        | 11.8%   |
| IvyBridge        | 63        | 11.09%  |
| Skylake          | 36        | 6.34%   |
| SandyBridge      | 35        | 6.16%   |
| Penryn           | 35        | 6.16%   |
| Westmere         | 32        | 5.63%   |
| Broadwell        | 24        | 4.23%   |
| TigerLake        | 14        | 2.46%   |
| Core             | 14        | 2.46%   |
| CometLake        | 12        | 2.11%   |
| Unknown          | 12        | 2.11%   |
| Alderlake Hybrid | 10        | 1.76%   |
| Zen+             | 8         | 1.41%   |
| Nehalem          | 8         | 1.41%   |
| IceLake          | 8         | 1.41%   |
| Excavator        | 8         | 1.41%   |
| Silvermont       | 7         | 1.23%   |
| Goldmont plus    | 7         | 1.23%   |
| Zen 3            | 6         | 1.06%   |
| Zen 2            | 5         | 0.88%   |
| Steamroller      | 5         | 0.88%   |
| NetBurst         | 5         | 0.88%   |
| Bonnell          | 5         | 0.88%   |
| K8 Hammer        | 4         | 0.7%    |
| K10              | 4         | 0.7%    |
| Jaguar           | 4         | 0.7%    |
| Zen              | 3         | 0.53%   |
| P6               | 3         | 0.53%   |
| Puma             | 2         | 0.35%   |
| Goldmont         | 2         | 0.35%   |
| K10 Llano        | 1         | 0.18%   |
| Bulldozer        | 1         | 0.18%   |
| Bobcat           | 1         | 0.18%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 396       | 48.12%  |
| Nvidia                     | 278       | 33.78%  |
| AMD                        | 141       | 17.13%  |
| ASPEED Technology          | 3         | 0.36%   |
| Matrox Electronics Systems | 2         | 0.24%   |
| VIA Technologies           | 1         | 0.12%   |
| Trident Microsystems       | 1         | 0.12%   |
| ATI Technologies           | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                      | 40        | 4.78%   |
| Intel UHD Graphics 620                                                                | 31        | 3.7%    |
| Intel HD Graphics 620                                                                 | 24        | 2.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 24        | 2.87%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 23        | 2.75%   |
| Intel HD Graphics 5500                                                                | 21        | 2.51%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 18        | 2.15%   |
| Intel Core Processor Integrated Graphics Controller                                   | 18        | 2.15%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 15        | 1.79%   |
| Intel HD Graphics 630                                                                 | 15        | 1.79%   |
| Intel HD Graphics 530                                                                 | 15        | 1.79%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 14        | 1.67%   |
| Nvidia GP108M [GeForce MX150]                                                         | 12        | 1.43%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                  | 12        | 1.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 12        | 1.43%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 11        | 1.31%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 11        | 1.31%   |
| Nvidia GP107M [GeForce MX350]                                                         | 9         | 1.08%   |
| Nvidia GM108M [GeForce MX110]                                                         | 9         | 1.08%   |
| Nvidia GK208M [GeForce GT 740M]                                                       | 9         | 1.08%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 9         | 1.08%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 9         | 1.08%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 9         | 1.08%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 9         | 1.08%   |
| AMD Thames [Radeon HD 7550M/7570M/7650M]                                              | 9         | 1.08%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                       | 8         | 0.96%   |
| Nvidia GT218 [GeForce 210]                                                            | 8         | 0.96%   |
| Nvidia GM108M [GeForce 940MX]                                                         | 8         | 0.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 8         | 0.96%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 8         | 0.96%   |
| Nvidia GM108M [GeForce 840M]                                                          | 7         | 0.84%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                  | 7         | 0.84%   |
| Intel Alder Lake-P Integrated Graphics Controller                                     | 7         | 0.84%   |
| AMD Lucienne                                                                          | 7         | 0.84%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                      | 7         | 0.84%   |
| Nvidia GM107M [GeForce GTX 950M]                                                      | 6         | 0.72%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                 | 6         | 0.72%   |
| AMD Sun LE [Radeon HD 8550M / R5 M230]                                                | 6         | 0.72%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                            | 6         | 0.72%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 6         | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| Intel + Nvidia           | 187       | 32.86%  |
| 1 x Intel                | 153       | 26.89%  |
| 1 x Nvidia               | 77        | 13.53%  |
| 1 x AMD                  | 67        | 11.78%  |
| Intel + AMD              | 54        | 9.49%   |
| AMD + Nvidia             | 12        | 2.11%   |
| 2 x AMD                  | 9         | 1.58%   |
| Other                    | 2         | 0.35%   |
| 1 x Matrox               | 2         | 0.35%   |
| 2 x Nvidia + 1 x ASPEED  | 1         | 0.18%   |
| 2 x Intel                | 1         | 0.18%   |
| 1 x VIA                  | 1         | 0.18%   |
| 1 x Trident Microsystems | 1         | 0.18%   |
| Nvidia + ASPEED          | 1         | 0.18%   |
| 1 x ASPEED               | 1         | 0.18%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 430       | 74.78%  |
| Proprietary | 127       | 22.09%  |
| Unknown     | 18        | 3.13%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 273       | 47.23%  |
| 1.01-2.0   | 115       | 19.9%   |
| 3.01-4.0   | 62        | 10.73%  |
| 0.51-1.0   | 60        | 10.38%  |
| 0.01-0.5   | 47        | 8.13%   |
| 7.01-8.0   | 9         | 1.56%   |
| 5.01-6.0   | 9         | 1.56%   |
| 8.01-16.0  | 2         | 0.35%   |
| 2.01-3.0   | 1         | 0.17%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 84        | 15.11%  |
| LG Display              | 80        | 14.39%  |
| AU Optronics            | 80        | 14.39%  |
| BOE                     | 68        | 12.23%  |
| Chimei Innolux          | 63        | 11.33%  |
| Goldstar                | 60        | 10.79%  |
| Chi Mei Optoelectronics | 11        | 1.98%   |
| PANDA                   | 10        | 1.8%    |
| Hewlett-Packard         | 10        | 1.8%    |
| Ancor Communications    | 9         | 1.62%   |
| BenQ                    | 7         | 1.26%   |
| AOC                     | 7         | 1.26%   |
| CHD                     | 6         | 1.08%   |
| Sony                    | 5         | 0.9%    |
| LG Electronics          | 5         | 0.9%    |
| Lenovo                  | 5         | 0.9%    |
| HannStar                | 5         | 0.9%    |
| Dell                    | 4         | 0.72%   |
| Unknown                 | 3         | 0.54%   |
| RTK                     | 3         | 0.54%   |
| LG Philips              | 3         | 0.54%   |
| Apple                   | 3         | 0.54%   |
| Sharp                   | 2         | 0.36%   |
| MSI                     | 2         | 0.36%   |
| InnoLux Display         | 2         | 0.36%   |
| InfoVision              | 2         | 0.36%   |
| XVision                 | 1         | 0.18%   |
| Xiaomi                  | 1         | 0.18%   |
| ViewSonic               | 1         | 0.18%   |
| Unknown (ADA)           | 1         | 0.18%   |
| TMX                     | 1         | 0.18%   |
| Seiko/Epson             | 1         | 0.18%   |
| SEEYOO                  | 1         | 0.18%   |
| Quanta Display          | 1         | 0.18%   |
| PAR                     | 1         | 0.18%   |
| Nvidia                  | 1         | 0.18%   |
| LGD                     | 1         | 0.18%   |
| KDC                     | 1         | 0.18%   |
| cPATH                   | 1         | 0.18%   |
| CHI                     | 1         | 0.18%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 12        | 2.12%   |
| BOE LCD Monitor BOE069C 1920x1080 344x193mm 15.5-inch                    | 8         | 1.41%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 8         | 1.41%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 7         | 1.24%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 6         | 1.06%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 5         | 0.88%   |
| Goldstar W2053 GSM4E9F 1600x900 443x249mm 20.0-inch                      | 5         | 0.88%   |
| Goldstar IPS WSXGA GSM5B01 1440x900 419x262mm 19.5-inch                  | 5         | 0.88%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch                | 5         | 0.88%   |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 5         | 0.88%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 5         | 0.88%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch           | 5         | 0.88%   |
| Samsung Electronics S22B300 SAM08A9 1600x900 443x249mm 20.0-inch         | 4         | 0.71%   |
| LG Display LCD Monitor LGD04D4 3840x2160 344x194mm 15.5-inch             | 4         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 4         | 0.71%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 4         | 0.71%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 4         | 0.71%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 4         | 0.71%   |
| Samsung Electronics S22F350 SAM0D1B 1920x1080 477x268mm 21.5-inch        | 3         | 0.53%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch        | 3         | 0.53%   |
| Samsung Electronics S20B300 SAM08A8 1600x900 440x250mm 19.9-inch         | 3         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 3         | 0.53%   |
| Samsung Electronics LCD Monitor SDC434B 3840x2160 344x194mm 15.5-inch    | 3         | 0.53%   |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                   | 3         | 0.53%   |
| PANDA LCD Monitor NCP003B 1920x1080 344x194mm 15.5-inch                  | 3         | 0.53%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 3         | 0.53%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch              | 3         | 0.53%   |
| LG Display LCD Monitor LGD044F 1920x1080 345x194mm 15.6-inch             | 3         | 0.53%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 3         | 0.53%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 3         | 0.53%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                   | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 3         | 0.53%   |
| Chimei Innolux LCD Monitor CMN15BD 1366x768 344x193mm 15.5-inch          | 3         | 0.53%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 3         | 0.53%   |
| CHD 24VCF CHD0240 1920x1080 368x207mm 16.6-inch                          | 3         | 0.53%   |
| BOE LCD Monitor BOE08E2 1920x1080 344x194mm 15.5-inch                    | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 3         | 0.53%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch            | 3         | 0.53%   |
| Samsung Electronics LS27A70 SAM71A0 3840x2160 597x336mm 27.0-inch        | 2         | 0.35%   |
| Samsung Electronics LCD Monitor SEC4252 1366x768 344x194mm 15.5-inch     | 2         | 0.35%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 236       | 43.3%   |
| 1366x768 (WXGA)    | 171       | 31.38%  |
| 1600x900 (HD+)     | 31        | 5.69%   |
| 1440x900 (WXGA+)   | 21        | 3.85%   |
| 3840x2160 (4K)     | 20        | 3.67%   |
| 1280x800 (WXGA)    | 13        | 2.39%   |
| 1680x1050 (WSXGA+) | 8         | 1.47%   |
| 1280x1024 (SXGA)   | 8         | 1.47%   |
| 1360x768           | 7         | 1.28%   |
| Unknown            | 5         | 0.92%   |
| 2560x1440 (QHD)    | 4         | 0.73%   |
| 1024x600           | 4         | 0.73%   |
| 3240x2160          | 2         | 0.37%   |
| 2560x1080          | 2         | 0.37%   |
| 1920x1200 (WUXGA)  | 2         | 0.37%   |
| 1280x960           | 2         | 0.37%   |
| 5760x2160          | 1         | 0.18%   |
| 3840x2400          | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 3200x1800 (QHD+)   | 1         | 0.18%   |
| 2944x1080          | 1         | 0.18%   |
| 2880x1620          | 1         | 0.18%   |
| 2720x768           | 1         | 0.18%   |
| 2560x1600          | 1         | 0.18%   |
| 1680x945           | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 266       | 48.01%  |
| 14      | 42        | 7.58%   |
| 21      | 39        | 7.04%   |
| 13      | 38        | 6.86%   |
| Unknown | 21        | 3.79%   |
| 20      | 19        | 3.43%   |
| 18      | 18        | 3.25%   |
| 23      | 14        | 2.53%   |
| 19      | 14        | 2.53%   |
| 17      | 11        | 1.99%   |
| 12      | 11        | 1.99%   |
| 27      | 10        | 1.81%   |
| 24      | 9         | 1.62%   |
| 22      | 7         | 1.26%   |
| 16      | 7         | 1.26%   |
| 11      | 6         | 1.08%   |
| 10      | 5         | 0.9%    |
| 46      | 3         | 0.54%   |
| 72      | 2         | 0.36%   |
| 65      | 2         | 0.36%   |
| 32      | 2         | 0.36%   |
| 29      | 2         | 0.36%   |
| 84      | 1         | 0.18%   |
| 47      | 1         | 0.18%   |
| 40      | 1         | 0.18%   |
| 31      | 1         | 0.18%   |
| 26      | 1         | 0.18%   |
| 7       | 1         | 0.18%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 342       | 61.96%  |
| 401-500     | 95        | 17.21%  |
| 501-600     | 33        | 5.98%   |
| 201-300     | 31        | 5.62%   |
| Unknown     | 21        | 3.8%    |
| 351-400     | 13        | 2.36%   |
| 1001-1500   | 6         | 1.09%   |
| 601-700     | 4         | 0.72%   |
| 1501-2000   | 3         | 0.54%   |
| 701-800     | 2         | 0.36%   |
| 801-900     | 1         | 0.18%   |
| 101-200     | 1         | 0.18%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 448       | 86.49%  |
| 16/10   | 38        | 7.34%   |
| Unknown | 19        | 3.67%   |
| 4/3     | 5         | 0.97%   |
| 3/2     | 4         | 0.77%   |
| 5/4     | 3         | 0.58%   |
| 21/9    | 1         | 0.19%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 266       | 48.01%  |
| 81-90          | 71        | 12.82%  |
| 201-250        | 63        | 11.37%  |
| 151-200        | 39        | 7.04%   |
| Unknown        | 21        | 3.79%   |
| 141-150        | 20        | 3.61%   |
| 61-70          | 11        | 1.99%   |
| 301-350        | 11        | 1.99%   |
| 121-130        | 8         | 1.44%   |
| 71-80          | 7         | 1.26%   |
| 51-60          | 6         | 1.08%   |
| More than 1000 | 5         | 0.9%    |
| 41-50          | 5         | 0.9%    |
| 501-1000       | 5         | 0.9%    |
| 351-500        | 4         | 0.72%   |
| 131-140        | 4         | 0.72%   |
| 91-100         | 3         | 0.54%   |
| 251-300        | 2         | 0.36%   |
| 111-120        | 2         | 0.36%   |
| 1-40           | 1         | 0.18%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 187       | 34.31%  |
| 101-120       | 178       | 32.66%  |
| 51-100        | 129       | 23.67%  |
| Unknown       | 21        | 3.85%   |
| More than 240 | 13        | 2.39%   |
| 161-240       | 11        | 2.02%   |
| 1-50          | 6         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 489       | 85.19%  |
| 2     | 57        | 9.93%   |
| 0     | 27        | 4.7%    |
| 3     | 1         | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 337       | 36.71%  |
| Intel                            | 228       | 24.84%  |
| Qualcomm Atheros                 | 124       | 13.51%  |
| Broadcom                         | 51        | 5.56%   |
| Ralink Technology                | 21        | 2.29%   |
| Ralink                           | 20        | 2.18%   |
| Samsung Electronics              | 19        | 2.07%   |
| Broadcom Limited                 | 16        | 1.74%   |
| D-Link                           | 12        | 1.31%   |
| Xiaomi                           | 11        | 1.2%    |
| MediaTek                         | 10        | 1.09%   |
| Marvell Technology Group         | 9         | 0.98%   |
| TP-Link                          | 8         | 0.87%   |
| VIA Technologies                 | 6         | 0.65%   |
| Huawei Technologies              | 5         | 0.54%   |
| D-Link System                    | 5         | 0.54%   |
| Nvidia                           | 4         | 0.44%   |
| Hewlett-Packard                  | 4         | 0.44%   |
| Qualcomm Atheros Communications  | 3         | 0.33%   |
| JMicron Technology               | 3         | 0.33%   |
| HTC (High Tech Computer)         | 3         | 0.33%   |
| Qualcomm                         | 2         | 0.22%   |
| Microsoft                        | 2         | 0.22%   |
| ASUSTek Computer                 | 2         | 0.22%   |
| ASIX Electronics                 | 2         | 0.22%   |
| ZyDAS                            | 1         | 0.11%   |
| Silicon Integrated Systems [SiS] | 1         | 0.11%   |
| Sierra Wireless                  | 1         | 0.11%   |
| LG Electronics                   | 1         | 0.11%   |
| Lenovo                           | 1         | 0.11%   |
| ICS Advent                       | 1         | 0.11%   |
| BUFFALO                          | 1         | 0.11%   |
| Attansic Technology              | 1         | 0.11%   |
| Aquantia                         | 1         | 0.11%   |
| Apple                            | 1         | 0.11%   |
| AboCom Systems                   | 1         | 0.11%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 24.81%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 3.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 2.21%   |
| Intel Wireless 7265                                               | 22        | 2.12%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 21        | 2.02%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 17        | 1.63%   |
| Ralink MT7601U Wireless Adapter                                   | 15        | 1.44%   |
| Intel Wireless 8265 / 8275                                        | 15        | 1.44%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 14        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 1.35%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 14        | 1.35%   |
| Intel Wireless 7260                                               | 14        | 1.35%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 12        | 1.15%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 12        | 1.15%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 1.06%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 11        | 1.06%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 11        | 1.06%   |
| Intel Wi-Fi 6 AX201                                               | 10        | 0.96%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 9         | 0.87%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 9         | 0.87%   |
| Intel Wireless 8260                                               | 9         | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                     | 9         | 0.87%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 8         | 0.77%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 0.77%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 8         | 0.77%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 0.77%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 7         | 0.67%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.58%   |
| Ralink RT5370 Wireless Adapter                                    | 6         | 0.58%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 6         | 0.58%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.58%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 0.58%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.58%   |
| Intel Centrino Advanced-N 6200                                    | 6         | 0.58%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                    | 6         | 0.58%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.48%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5         | 0.48%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 190       | 38.78%  |
| Qualcomm Atheros                | 94        | 19.18%  |
| Realtek Semiconductor           | 78        | 15.92%  |
| Broadcom                        | 32        | 6.53%   |
| Ralink Technology               | 21        | 4.29%   |
| Ralink                          | 20        | 4.08%   |
| Broadcom Limited                | 13        | 2.65%   |
| D-Link                          | 11        | 2.24%   |
| MediaTek                        | 9         | 1.84%   |
| TP-Link                         | 7         | 1.43%   |
| Qualcomm Atheros Communications | 3         | 0.61%   |
| Hewlett-Packard                 | 3         | 0.61%   |
| D-Link System                   | 3         | 0.61%   |
| ZyDAS                           | 1         | 0.2%    |
| Xiaomi                          | 1         | 0.2%    |
| Sierra Wireless                 | 1         | 0.2%    |
| Marvell Technology Group        | 1         | 0.2%    |
| BUFFALO                         | 1         | 0.2%    |
| AboCom Systems                  | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 4.67%   |
| Intel Wireless 7265                                            | 22        | 4.47%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 21        | 4.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 17        | 3.46%   |
| Ralink MT7601U Wireless Adapter                                | 15        | 3.05%   |
| Intel Wireless 8265 / 8275                                     | 15        | 3.05%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 14        | 2.85%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 14        | 2.85%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 14        | 2.85%   |
| Intel Wireless 7260                                            | 14        | 2.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 12        | 2.44%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 12        | 2.44%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 11        | 2.24%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 11        | 2.24%   |
| Intel Wi-Fi 6 AX201                                            | 10        | 2.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 9         | 1.83%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 9         | 1.83%   |
| Intel Wireless 8260                                            | 9         | 1.83%   |
| Broadcom BCM43142 802.11b/g/n                                  | 9         | 1.83%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 8         | 1.63%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 7         | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 7         | 1.42%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 6         | 1.22%   |
| Ralink RT5370 Wireless Adapter                                 | 6         | 1.22%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 6         | 1.22%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 6         | 1.22%   |
| Intel Wi-Fi 6 AX200                                            | 6         | 1.22%   |
| Intel Centrino Advanced-N 6200                                 | 6         | 1.22%   |
| D-Link DWA-123 Wireless N 150 Adapter (rev.D1)                 | 6         | 1.22%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 5         | 1.02%   |
| Intel Centrino Ultimate-N 6300                                 | 5         | 1.02%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 5         | 1.02%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 4         | 0.81%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 4         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 4         | 0.81%   |
| Intel Wireless 3165                                            | 4         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 0.81%   |
| Intel Centrino Wireless-N 2230                                 | 4         | 0.81%   |
| Intel Centrino Wireless-N 1000 [Condor Peak]                   | 4         | 0.81%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 4         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 307       | 57.38%  |
| Intel                            | 81        | 15.14%  |
| Qualcomm Atheros                 | 47        | 8.79%   |
| Broadcom                         | 27        | 5.05%   |
| Samsung Electronics              | 11        | 2.06%   |
| Xiaomi                           | 10        | 1.87%   |
| Marvell Technology Group         | 8         | 1.5%    |
| VIA Technologies                 | 6         | 1.12%   |
| Huawei Technologies              | 5         | 0.93%   |
| Nvidia                           | 4         | 0.75%   |
| JMicron Technology               | 3         | 0.56%   |
| HTC (High Tech Computer)         | 3         | 0.56%   |
| Broadcom Limited                 | 3         | 0.56%   |
| Qualcomm                         | 2         | 0.37%   |
| Microsoft                        | 2         | 0.37%   |
| D-Link System                    | 2         | 0.37%   |
| ASIX Electronics                 | 2         | 0.37%   |
| TP-Link                          | 1         | 0.19%   |
| Silicon Integrated Systems [SiS] | 1         | 0.19%   |
| MediaTek                         | 1         | 0.19%   |
| LG Electronics                   | 1         | 0.19%   |
| Lenovo                           | 1         | 0.19%   |
| ICS Advent                       | 1         | 0.19%   |
| Hewlett-Packard                  | 1         | 0.19%   |
| D-Link                           | 1         | 0.19%   |
| Attansic Technology              | 1         | 0.19%   |
| ASUSTek Computer                 | 1         | 0.19%   |
| Aquantia                         | 1         | 0.19%   |
| Apple                            | 1         | 0.19%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 258       | 47.87%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 37        | 6.86%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 22        | 4.08%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 11        | 2.04%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 8         | 1.48%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 8         | 1.48%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.11%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 0.93%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 5         | 0.93%   |
| VIA VT6105/VT6106S [Rhine-III]                                    | 5         | 0.93%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 5         | 0.93%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 5         | 0.93%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 5         | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 5         | 0.93%   |
| Intel 82577LM Gigabit Network Connection                          | 5         | 0.93%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 5         | 0.93%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.74%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 4         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.74%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 4         | 0.74%   |
| Huawei ANE-LX1                                                    | 4         | 0.74%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 3         | 0.56%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                        | 3         | 0.56%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 3         | 0.56%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 3         | 0.56%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 3         | 0.56%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.56%   |
| Intel Ethernet Connection (7) I219-V                              | 3         | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.56%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.56%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.37%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.37%   |
| Qualcomm Redmi Note 9 Pro                                         | 2         | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.37%   |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.37%   |
| Qualcomm Atheros AR8151 v1.0 Gigabit Ethernet                     | 2         | 0.37%   |
| Microsoft RTL8153 GigE [Surface Ethernet Adapter]                 | 2         | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 493       | 50.51%  |
| WiFi     | 474       | 48.57%  |
| Modem    | 8         | 0.82%   |
| Unknown  | 1         | 0.1%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 397       | 71.79%  |
| Ethernet | 155       | 28.03%  |
| Unknown  | 1         | 0.18%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 355       | 62.5%   |
| 1     | 201       | 35.39%  |
| 0     | 6         | 1.06%   |
| 3     | 4         | 0.7%    |
| 4     | 2         | 0.35%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 535       | 93.53%  |
| Yes  | 37        | 6.47%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 140       | 38.89%  |
| IMC Networks                    | 50        | 13.89%  |
| Realtek Semiconductor           | 33        | 9.17%   |
| Qualcomm Atheros Communications | 27        | 7.5%    |
| Broadcom                        | 17        | 4.72%   |
| Lite-On Technology              | 15        | 4.17%   |
| Foxconn / Hon Hai               | 15        | 4.17%   |
| Cambridge Silicon Radio         | 15        | 4.17%   |
| Ralink                          | 9         | 2.5%    |
| Dell                            | 9         | 2.5%    |
| ASUSTek Computer                | 9         | 2.5%    |
| Foxconn International           | 4         | 1.11%   |
| Ralink Technology               | 3         | 0.83%   |
| Realtek                         | 2         | 0.56%   |
| Hewlett-Packard                 | 2         | 0.56%   |
| Askey Computer                  | 2         | 0.56%   |
| Apple                           | 2         | 0.56%   |
| Micro Star International        | 1         | 0.28%   |
| MediaTek                        | 1         | 0.28%   |
| Marvell Semiconductor           | 1         | 0.28%   |
| ISSC                            | 1         | 0.28%   |
| Integrated System Solution      | 1         | 0.28%   |
| Alps Electric                   | 1         | 0.28%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 70        | 19.44%  |
| Intel AX201 Bluetooth                                                               | 25        | 6.94%   |
| IMC Networks Bluetooth Radio                                                        | 23        | 6.39%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 21        | 5.83%   |
| Realtek Bluetooth Radio                                                             | 20        | 5.56%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 15        | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 14        | 3.89%   |
| IMC Networks Bluetooth Device                                                       | 11        | 3.06%   |
| Ralink RT3290 Bluetooth                                                             | 9         | 2.5%    |
| Intel Bluetooth Device                                                              | 8         | 2.22%   |
| Realtek RTL8723B Bluetooth                                                          | 7         | 1.94%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.94%   |
| Intel AX200 Bluetooth                                                               | 6         | 1.67%   |
| IMC Networks Wireless_Device                                                        | 6         | 1.67%   |
| ASUS BT-270 Bluetooth Adapter                                                       | 6         | 1.67%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 1.39%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 5         | 1.39%   |
| Lite-On Bluetooth Device                                                            | 5         | 1.39%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 1.39%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 1.11%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 4         | 1.11%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 4         | 1.11%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.11%   |
| Broadcom BCM20702A0                                                                 | 4         | 1.11%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 3         | 0.83%   |
| IMC Networks Bluetooth USB Host Controller                                          | 3         | 0.83%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 3         | 0.83%   |
| Broadcom HP Portable SoftSailing                                                    | 3         | 0.83%   |
| Broadcom BCM43142 Bluetooth 4.0                                                     | 3         | 0.83%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 3         | 0.83%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 0.56%   |
| Realtek Bluetooth Radio                                                             | 2         | 0.56%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 2         | 0.56%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 2         | 0.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.56%   |
| IMC Networks Bluetooth                                                              | 2         | 0.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 0.56%   |
| Foxconn / Hon Hai BT                                                                | 2         | 0.56%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.56%   |
| Dell Wireless 360 Bluetooth                                                         | 2         | 0.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 492       | 67.68%  |
| Nvidia                           | 119       | 16.37%  |
| AMD                              | 93        | 12.79%  |
| C-Media Electronics              | 6         | 0.83%   |
| Generalplus Technology           | 4         | 0.55%   |
| Focusrite-Novation               | 2         | 0.28%   |
| Creative Labs                    | 2         | 0.28%   |
| ASUSTek Computer                 | 2         | 0.28%   |
| Yamaha                           | 1         | 0.14%   |
| VIA Technologies                 | 1         | 0.14%   |
| ULi Electronics                  | 1         | 0.14%   |
| Silicon Integrated Systems [SiS] | 1         | 0.14%   |
| Native Instruments               | 1         | 0.14%   |
| ESS Technology                   | 1         | 0.14%   |
| CMX Systems                      | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 67        | 7.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 55        | 6.51%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 41        | 4.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 40        | 4.73%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 37        | 4.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31        | 3.67%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 30        | 3.55%   |
| AMD Family 17h/19h HD Audio Controller                                     | 24        | 2.84%   |
| Intel Broadwell-U Audio Controller                                         | 23        | 2.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 23        | 2.72%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 22        | 2.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 18        | 2.13%   |
| Intel Haswell-ULT HD Audio Controller                                      | 18        | 2.13%   |
| Intel Cannon Lake PCH cAVS                                                 | 18        | 2.13%   |
| Intel 8 Series HD Audio Controller                                         | 18        | 2.13%   |
| Intel CM238 HD Audio Controller                                            | 15        | 1.78%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 14        | 1.66%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 1.66%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 14        | 1.66%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 13        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 13        | 1.54%   |
| Intel Comet Lake PCH-LP cAVS                                               | 12        | 1.42%   |
| Nvidia High Definition Audio Controller                                    | 11        | 1.3%    |
| AMD Kabini HDMI/DP Audio                                                   | 11        | 1.3%    |
| Nvidia GF119 HDMI Audio Controller                                         | 9         | 1.07%   |
| Intel Comet Lake PCH cAVS                                                  | 9         | 1.07%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 9         | 1.07%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 8         | 0.95%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 0.95%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 8         | 0.95%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 7         | 0.83%   |
| Nvidia Audio device                                                        | 7         | 0.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 7         | 0.83%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.83%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 6         | 0.71%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 6         | 0.71%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6         | 0.71%   |
| Nvidia TU116 High Definition Audio Controller                              | 5         | 0.59%   |
| Nvidia GT216 HDMI Audio Controller                                         | 5         | 0.59%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 90        | 27.61%  |
| SK hynix            | 59        | 18.1%   |
| Micron Technology   | 41        | 12.58%  |
| Unknown             | 28        | 8.59%   |
| Kingston            | 25        | 7.67%   |
| Crucial             | 22        | 6.75%   |
| Ramaxel Technology  | 14        | 4.29%   |
| Elpida              | 10        | 3.07%   |
| A-DATA Technology   | 7         | 2.15%   |
| Corsair             | 6         | 1.84%   |
| GeIL                | 5         | 1.53%   |
| Apacer              | 4         | 1.23%   |
| Kingmax             | 3         | 0.92%   |
| G.Skill             | 3         | 0.92%   |
| Ramos Technology    | 2         | 0.61%   |
| Nanya Technology    | 2         | 0.61%   |
| TwinMOS             | 1         | 0.31%   |
| Transcend           | 1         | 0.31%   |
| Neo Forza           | 1         | 0.31%   |
| ASint Technology    | 1         | 0.31%   |
| Unknown             | 1         | 0.31%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s        | 8         | 2.28%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s       | 6         | 1.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s        | 6         | 1.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.71%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s        | 6         | 1.71%   |
| Crucial RAM CB16GS2666.C8ET 16GB SODIMM DDR4 2667MT/s        | 6         | 1.71%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s       | 5         | 1.42%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s        | 5         | 1.42%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s        | 5         | 1.42%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s        | 4         | 1.14%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s       | 4         | 1.14%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s         | 4         | 1.14%   |
| Micron RAM 8ATF1G64HZ-2G3B1 8GB SODIMM DDR4 2400MT/s         | 4         | 1.14%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s        | 4         | 1.14%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 3         | 0.85%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s       | 3         | 0.85%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s       | 3         | 0.85%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s        | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s        | 3         | 0.85%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s        | 3         | 0.85%   |
| Samsung RAM M425R1GB4BB0-CQKOL 8GB SODIMM DDR5 4800MT/s      | 3         | 0.85%   |
| Micron RAM 16KTF51264HZ-1G6M1 4GB SODIMM DDR3 1600MT/s       | 3         | 0.85%   |
| GeIL RAM CL17-17-17 D4-2400 8GB DIMM DDR4 2400MT/s           | 3         | 0.85%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                   | 2         | 0.57%   |
| Unknown RAM Module 2GB DIMM 800MT/s                          | 2         | 0.57%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                   | 2         | 0.57%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.57%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s         | 2         | 0.57%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.57%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s       | 2         | 0.57%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1334MT/s       | 2         | 0.57%   |
| SK hynix RAM HMT325S6CFR8C-PB 2GB SODIMM DDR3 1600MT/s       | 2         | 0.57%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s       | 2         | 0.57%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB Row Of Chips DDR4 3200MT/s | 2         | 0.57%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s       | 2         | 0.57%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s        | 2         | 0.57%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s        | 2         | 0.57%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s        | 2         | 0.57%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s        | 2         | 0.57%   |
| Samsung RAM M471B5173BH0-YK0 4GB SODIMM DDR3 1600MT/s        | 2         | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 121       | 45.66%  |
| DDR3    | 107       | 40.38%  |
| DDR2    | 10        | 3.77%   |
| Unknown | 8         | 3.02%   |
| DDR5    | 6         | 2.26%   |
| SDRAM   | 5         | 1.89%   |
| LPDDR4  | 3         | 1.13%   |
| LPDDR5  | 2         | 0.75%   |
| LPDDR3  | 2         | 0.75%   |
| DDR     | 1         | 0.38%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 195       | 74.43%  |
| DIMM         | 55        | 20.99%  |
| Row Of Chips | 11        | 4.2%    |
| Chip         | 1         | 0.38%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 115       | 37.95%  |
| 8192  | 103       | 33.99%  |
| 2048  | 38        | 12.54%  |
| 16384 | 33        | 10.89%  |
| 1024  | 9         | 2.97%   |
| 32768 | 4         | 1.32%   |
| 65536 | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 73        | 24.83%  |
| 2667    | 51        | 17.35%  |
| 3200    | 33        | 11.22%  |
| 2400    | 26        | 8.84%   |
| 1334    | 21        | 7.14%   |
| 2133    | 15        | 5.1%    |
| 1333    | 15        | 5.1%    |
| 3266    | 8         | 2.72%   |
| 667     | 7         | 2.38%   |
| Unknown | 7         | 2.38%   |
| 4800    | 6         | 2.04%   |
| 4199    | 5         | 1.7%    |
| 800     | 5         | 1.7%    |
| 1067    | 3         | 1.02%   |
| 8400    | 2         | 0.68%   |
| 6400    | 2         | 0.68%   |
| 1867    | 2         | 0.68%   |
| 533     | 2         | 0.68%   |
| 4266    | 1         | 0.34%   |
| 3600    | 1         | 0.34%   |
| 3066    | 1         | 0.34%   |
| 2933    | 1         | 0.34%   |
| 2800    | 1         | 0.34%   |
| 2448    | 1         | 0.34%   |
| 1866    | 1         | 0.34%   |
| 1800    | 1         | 0.34%   |
| 1400    | 1         | 0.34%   |
| 1328    | 1         | 0.34%   |
| 400     | 1         | 0.34%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 3         | 50%     |
| Canon           | 3         | 50%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| HP LaserJet P1102          | 1         | 16.67%  |
| HP LaserJet 1018           | 1         | 16.67%  |
| HP DeskJet 2130 series     | 1         | 16.67%  |
| Canon MG5600 series        | 1         | 16.67%  |
| Canon LBP6300              | 1         | 16.67%  |
| Canon iR2004/2204 UFRII LT | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 3         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 120            | 1         | 33.33%  |
| Canon CanoScan 4400F               | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 87        | 22.25%  |
| IMC Networks                           | 86        | 21.99%  |
| Realtek Semiconductor                  | 31        | 7.93%   |
| Microdia                               | 26        | 6.65%   |
| Bison Electronics                      | 21        | 5.37%   |
| Syntek                                 | 18        | 4.6%    |
| Sunplus Innovation Technology          | 17        | 4.35%   |
| Acer                                   | 16        | 4.09%   |
| Cheng Uei Precision Industry (Foxlink) | 14        | 3.58%   |
| Apple                                  | 10        | 2.56%   |
| Suyin                                  | 9         | 2.3%    |
| Quanta                                 | 8         | 2.05%   |
| Lite-On Technology                     | 8         | 2.05%   |
| Sonix Technology                       | 7         | 1.79%   |
| Ricoh                                  | 6         | 1.53%   |
| Samsung Electronics                    | 5         | 1.28%   |
| Pixart Imaging                         | 3         | 0.77%   |
| Lenovo                                 | 3         | 0.77%   |
| ALi                                    | 3         | 0.77%   |
| Alcor Micro                            | 3         | 0.77%   |
| Importek                               | 2         | 0.51%   |
| Primax Electronics                     | 1         | 0.26%   |
| OmniVision Technologies                | 1         | 0.26%   |
| MacroSilicon                           | 1         | 0.26%   |
| Luxvisions Innotech Limited            | 1         | 0.26%   |
| LG Electronics                         | 1         | 0.26%   |
| KYE Systems (Mouse Systems)            | 1         | 0.26%   |
| Goertek Electronics                    | 1         | 0.26%   |
| Generalplus Technology                 | 1         | 0.26%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                  | 33        | 8.44%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 19        | 4.86%   |
| IMC Networks Integrated Camera                      | 14        | 3.58%   |
| Chicony integrated camera                           | 13        | 3.32%   |
| Chicony USB2.0 HD UVC WebCam                        | 9         | 2.3%    |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 9         | 2.3%    |
| Chicony HD WebCam                                   | 8         | 2.05%   |
| Chicony EasyCamera                                  | 8         | 2.05%   |
| IMC Networks Lenovo EasyCamera                      | 7         | 1.79%   |
| Syntek Integrated Camera                            | 6         | 1.53%   |
| Syntek EasyCamera                                   | 6         | 1.53%   |
| Sunplus HD WebCam                                   | 6         | 1.53%   |
| Realtek USB2.0 VGA UVC WebCam                       | 6         | 1.53%   |
| Realtek USB Camera                                  | 6         | 1.53%   |
| Bison Lenovo EasyCamera                             | 6         | 1.53%   |
| Acer Lenovo EasyCamera                              | 6         | 1.53%   |
| Syntek Lenovo EasyCamera                            | 5         | 1.28%   |
| Sunplus Asus Webcam                                 | 5         | 1.28%   |
| Sonix USB2.0 HD UVC WebCam                          | 5         | 1.28%   |
| Samsung Galaxy series, misc. (MTP mode)             | 5         | 1.28%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 1.28%   |
| Chicony HP HD Webcam [Fixed]                        | 5         | 1.28%   |
| Chicony HP HD Webcam                                | 5         | 1.28%   |
| Microdia USB 2.0 Camera                             | 4         | 1.02%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.02%   |
| Lite-On Integrated Camera                           | 4         | 1.02%   |
| Chicony Integrated HP HD Webcam                     | 4         | 1.02%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 4         | 1.02%   |
| Bison Integrated Camera                             | 4         | 1.02%   |
| Microdia Sonix Integrated Webcam                    | 3         | 0.77%   |
| Microdia Laptop_Integrated_Webcam_HD                | 3         | 0.77%   |
| Microdia Integrated Webcam                          | 3         | 0.77%   |
| Lite-On HP HD Camera                                | 3         | 0.77%   |
| IMC Networks VGA UVC WebCam                         | 3         | 0.77%   |
| IMC Networks Integrated Webcam                      | 3         | 0.77%   |
| Chicony USB2.0 VGA UVC WebCam                       | 3         | 0.77%   |
| Chicony TOSHIBA Web Camera - HD                     | 3         | 0.77%   |
| Chicony HP Truevision HD                            | 3         | 0.77%   |
| Chicony HP HD Camera                                | 3         | 0.77%   |
| Chicony 1.3M HD WebCam                              | 3         | 0.77%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 37        | 38.95%  |
| Shenzhen Goodix Technology         | 15        | 15.79%  |
| Upek                               | 12        | 12.63%  |
| Elan Microelectronics              | 12        | 12.63%  |
| Synaptics                          | 9         | 9.47%   |
| AuthenTec                          | 4         | 4.21%   |
| LighTuning Technology              | 3         | 3.16%   |
| Suprema                            | 1         | 1.05%   |
| STMicroelectronics                 | 1         | 1.05%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 1.05%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 15        | 15.79%  |
| Elan ELAN:Fingerprint                                           | 12        | 12.63%  |
| Validity Sensors VFS491                                         | 11        | 11.58%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor          | 11        | 11.58%  |
| Shenzhen Goodix  FingerPrint Device                             | 11        | 11.58%  |
| Validity Sensors VFS 5011 fingerprint sensor                    | 4         | 4.21%   |
| Synaptics  WBDI                                                 | 3         | 3.16%   |
| Shenzhen Goodix Fingerprint Reader                              | 3         | 3.16%   |
| Validity Sensors VFS451 Fingerprint Reader                      | 2         | 2.11%   |
| Synaptics WBDI Fingerprint Reader USB 086                       | 2         | 2.11%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                | 2         | 2.11%   |
| LighTuning ES603 Swipe Fingerprint Sensor                       | 2         | 2.11%   |
| AuthenTec AES1660 Fingerprint Sensor                            | 2         | 2.11%   |
| Validity Sensors VFS5011 Fingerprint Reader                     | 1         | 1.05%   |
| Validity Sensors VFS471 Fingerprint Reader                      | 1         | 1.05%   |
| Validity Sensors VFS301 Fingerprint Reader                      | 1         | 1.05%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 1.05%   |
| Validity Sensors Fingerprint scanner                            | 1         | 1.05%   |
| Upek TCS5B Fingerprint sensor                                   | 1         | 1.05%   |
| Synaptics UWP WBDI                                              | 1         | 1.05%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 1         | 1.05%   |
| Suprema SUP-SFR400(A) BioMini Fingerprint Reader                | 1         | 1.05%   |
| STMicroelectronics Fingerprint Reader                           | 1         | 1.05%   |
| Shenzhen Goodix FingerPrint                                     | 1         | 1.05%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 1         | 1.05%   |
| LighTuning EgisTec Touch Fingerprint Sensor                     | 1         | 1.05%   |
| AuthenTec Fingerprint Sensor                                    | 1         | 1.05%   |
| AuthenTec AES2550 Fingerprint Sensor                            | 1         | 1.05%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 6         | 40%     |
| Alcor Micro           | 4         | 26.67%  |
| Upek                  | 2         | 13.33%  |
| O2 Micro              | 2         | 13.33%  |
| Gemalto (was Gemplus) | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 13.33%  |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 13.33%  |
| Broadcom 5880                                                                | 2         | 13.33%  |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 6.67%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 362       | 62.41%  |
| 1     | 165       | 28.45%  |
| 2     | 40        | 6.9%    |
| 3     | 9         | 1.55%   |
| 4     | 2         | 0.34%   |
| 7     | 1         | 0.17%   |
| 5     | 1         | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 95        | 34.67%  |
| Graphics card            | 83        | 30.29%  |
| Net/wireless             | 20        | 7.3%    |
| Communication controller | 18        | 6.57%   |
| Bluetooth                | 15        | 5.47%   |
| Chipcard                 | 13        | 4.74%   |
| Camera                   | 7         | 2.55%   |
| Unassigned class         | 6         | 2.19%   |
| Storage                  | 4         | 1.46%   |
| Multimedia controller    | 4         | 1.46%   |
| Sound                    | 3         | 1.09%   |
| Network                  | 2         | 0.73%   |
| Card reader              | 2         | 0.73%   |
| Wireless                 | 1         | 0.36%   |
| Net/ethernet             | 1         | 0.36%   |


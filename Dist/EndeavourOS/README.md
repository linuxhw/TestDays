EndeavourOS - Tested Hardware & Statistics
------------------------------------------

A project to collect tested hardware configurations for EndeavourOS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/EndeavourOS/Desktop/README.md) and [notebooks](/Dist/EndeavourOS/Notebook/README.md).

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

Total: 1661

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | AERO 15-X9                  | Notebook    | [35830807d4](https://linux-hardware.org/?probe=35830807d4) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [1c4b1aa68d](https://linux-hardware.org/?probe=1c4b1aa68d) | Sep 30, 2023 |
| Timi          | Mi NoteBook Ultra           | Notebook    | [988f015a89](https://linux-hardware.org/?probe=988f015a89) | Sep 30, 2023 |
| Lenovo        | ThinkPad E495 20NES07V00    | Notebook    | [935dc10f6b](https://linux-hardware.org/?probe=935dc10f6b) | Sep 30, 2023 |
| Dell          | Latitude 5410               | Notebook    | [d13c5769a3](https://linux-hardware.org/?probe=d13c5769a3) | Sep 30, 2023 |
| Positivo      | POS-PIH81DI                 | Desktop     | [0e67f3a0f3](https://linux-hardware.org/?probe=0e67f3a0f3) | Sep 29, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [670f7351b5](https://linux-hardware.org/?probe=670f7351b5) | Sep 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1543bac588](https://linux-hardware.org/?probe=1543bac588) | Sep 27, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ed68f904fe](https://linux-hardware.org/?probe=ed68f904fe) | Sep 26, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [e24beff974](https://linux-hardware.org/?probe=e24beff974) | Sep 26, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [b8b2b3ff7e](https://linux-hardware.org/?probe=b8b2b3ff7e) | Sep 26, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6677b81417](https://linux-hardware.org/?probe=6677b81417) | Sep 26, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0dca41ca4e](https://linux-hardware.org/?probe=0dca41ca4e) | Sep 25, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [94ce4b6306](https://linux-hardware.org/?probe=94ce4b6306) | Sep 25, 2023 |
| MSI           | GS63VR 6RF                  | Notebook    | [03a9aed3c9](https://linux-hardware.org/?probe=03a9aed3c9) | Sep 25, 2023 |
| Lenovo        | IdeaPad 720S-13IKB 81BV     | Notebook    | [7ea3152d65](https://linux-hardware.org/?probe=7ea3152d65) | Sep 25, 2023 |
| Dell          | G5 5505                     | Notebook    | [e9c461d44d](https://linux-hardware.org/?probe=e9c461d44d) | Sep 25, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21HF... | Notebook    | [cada97becf](https://linux-hardware.org/?probe=cada97becf) | Sep 25, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [2b371179db](https://linux-hardware.org/?probe=2b371179db) | Sep 25, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2bb252778b](https://linux-hardware.org/?probe=2bb252778b) | Sep 25, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [f6369d0be5](https://linux-hardware.org/?probe=f6369d0be5) | Sep 23, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [2d1e14cb66](https://linux-hardware.org/?probe=2d1e14cb66) | Sep 23, 2023 |
| Acer          | Switch SW312-31             | Tablet      | [0f276cde5a](https://linux-hardware.org/?probe=0f276cde5a) | Sep 23, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c6211ac3aa](https://linux-hardware.org/?probe=c6211ac3aa) | Sep 22, 2023 |
| Gigabyte      | B250M-D3H-CF                | Desktop     | [3a965cb7e3](https://linux-hardware.org/?probe=3a965cb7e3) | Sep 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [90c9ffe2e0](https://linux-hardware.org/?probe=90c9ffe2e0) | Sep 22, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [45f00aaf92](https://linux-hardware.org/?probe=45f00aaf92) | Sep 21, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [7f327aca42](https://linux-hardware.org/?probe=7f327aca42) | Sep 21, 2023 |
| HP            | 212B                        | Desktop     | [f961d48c51](https://linux-hardware.org/?probe=f961d48c51) | Sep 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [9fdc142c76](https://linux-hardware.org/?probe=9fdc142c76) | Sep 19, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d940deb0df](https://linux-hardware.org/?probe=d940deb0df) | Sep 19, 2023 |
| ASUSTek       | Z170M-PLUS                  | Desktop     | [2b913a2e83](https://linux-hardware.org/?probe=2b913a2e83) | Sep 19, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5cab8957eb](https://linux-hardware.org/?probe=5cab8957eb) | Sep 18, 2023 |
| HP            | Dragonfly Pro               | Notebook    | [0c5d439504](https://linux-hardware.org/?probe=0c5d439504) | Sep 18, 2023 |
| Dell          | 0M6C7G A00                  | Desktop     | [a93d60a237](https://linux-hardware.org/?probe=a93d60a237) | Sep 17, 2023 |
| ASUSTek       | PRIME H770-PLUS             | Desktop     | [c58fea9225](https://linux-hardware.org/?probe=c58fea9225) | Sep 16, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0602c2deb2](https://linux-hardware.org/?probe=0602c2deb2) | Sep 16, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [aea37f693f](https://linux-hardware.org/?probe=aea37f693f) | Sep 15, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [804b890928](https://linux-hardware.org/?probe=804b890928) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [ef63882e50](https://linux-hardware.org/?probe=ef63882e50) | Sep 15, 2023 |
| MSI           | MEG Z790 GODLIKE            | Desktop     | [688462f949](https://linux-hardware.org/?probe=688462f949) | Sep 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [c954042e8b](https://linux-hardware.org/?probe=c954042e8b) | Sep 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [452d16c55c](https://linux-hardware.org/?probe=452d16c55c) | Sep 13, 2023 |
| Lenovo        | IdeaPad 3 15IIL05 81WE      | Notebook    | [2260bcd7af](https://linux-hardware.org/?probe=2260bcd7af) | Sep 12, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2284d8a2dd](https://linux-hardware.org/?probe=2284d8a2dd) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [dca28b0d09](https://linux-hardware.org/?probe=dca28b0d09) | Sep 12, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6c6c4a19ec](https://linux-hardware.org/?probe=6c6c4a19ec) | Sep 12, 2023 |
| HP            | 245 14 inch G9 Notebook ... | Notebook    | [e72c31a6fc](https://linux-hardware.org/?probe=e72c31a6fc) | Sep 11, 2023 |
| Acer          | Swift SF314-512             | Notebook    | [4628c4e630](https://linux-hardware.org/?probe=4628c4e630) | Sep 11, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [6d8ac2101a](https://linux-hardware.org/?probe=6d8ac2101a) | Sep 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RJ... | Notebook    | [16b6bd1d3d](https://linux-hardware.org/?probe=16b6bd1d3d) | Sep 09, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [bdd270eddd](https://linux-hardware.org/?probe=bdd270eddd) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [37efc0526e](https://linux-hardware.org/?probe=37efc0526e) | Sep 09, 2023 |
| ASUSTek       | ROG Maximus XI EXTREME      | Desktop     | [035446631a](https://linux-hardware.org/?probe=035446631a) | Sep 09, 2023 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [5b0ce3438c](https://linux-hardware.org/?probe=5b0ce3438c) | Sep 08, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [178d6df21a](https://linux-hardware.org/?probe=178d6df21a) | Sep 08, 2023 |
| HP            | Elite Dragonfly 13.5 inc... | Notebook    | [6870581b7c](https://linux-hardware.org/?probe=6870581b7c) | Sep 08, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [872f12f24c](https://linux-hardware.org/?probe=872f12f24c) | Sep 08, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [d5430e9279](https://linux-hardware.org/?probe=d5430e9279) | Sep 08, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [5b22cd283b](https://linux-hardware.org/?probe=5b22cd283b) | Sep 08, 2023 |
| ASRock        | B450M/ac R2.0               | Desktop     | [82266958be](https://linux-hardware.org/?probe=82266958be) | Sep 07, 2023 |
| HP            | Pavilion Laptop 15-eg3xx... | Notebook    | [003d136012](https://linux-hardware.org/?probe=003d136012) | Sep 07, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [79ddc77f63](https://linux-hardware.org/?probe=79ddc77f63) | Sep 07, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [a5506bdc30](https://linux-hardware.org/?probe=a5506bdc30) | Sep 07, 2023 |
| Acer          | Aspire GX-785               | Desktop     | [e33b7b35bf](https://linux-hardware.org/?probe=e33b7b35bf) | Sep 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fafd1b4cf2](https://linux-hardware.org/?probe=fafd1b4cf2) | Sep 06, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [38aad324f2](https://linux-hardware.org/?probe=38aad324f2) | Sep 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | Notebook    | [cd1be324d4](https://linux-hardware.org/?probe=cd1be324d4) | Sep 05, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [82fd19c99e](https://linux-hardware.org/?probe=82fd19c99e) | Sep 05, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [08dd85e58d](https://linux-hardware.org/?probe=08dd85e58d) | Sep 05, 2023 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [fc603fc196](https://linux-hardware.org/?probe=fc603fc196) | Sep 05, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [13b7789482](https://linux-hardware.org/?probe=13b7789482) | Sep 04, 2023 |
| HP            | EliteBook 845 14 inch G1... | Notebook    | [8a4af58adc](https://linux-hardware.org/?probe=8a4af58adc) | Sep 04, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3ee4e0f848](https://linux-hardware.org/?probe=3ee4e0f848) | Sep 02, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [f23cf01c1c](https://linux-hardware.org/?probe=f23cf01c1c) | Sep 02, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [db2e607ae6](https://linux-hardware.org/?probe=db2e607ae6) | Sep 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [d8e4c2da1e](https://linux-hardware.org/?probe=d8e4c2da1e) | Sep 01, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [b652970974](https://linux-hardware.org/?probe=b652970974) | Sep 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [4725c2be8e](https://linux-hardware.org/?probe=4725c2be8e) | Sep 01, 2023 |
| HP            | Pavilion Aero Laptop 13z... | Notebook    | [afa88a8a6a](https://linux-hardware.org/?probe=afa88a8a6a) | Sep 01, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [ce1e538f59](https://linux-hardware.org/?probe=ce1e538f59) | Sep 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [a6619c179c](https://linux-hardware.org/?probe=a6619c179c) | Aug 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [578f5e581e](https://linux-hardware.org/?probe=578f5e581e) | Aug 31, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [0bf7d37cc9](https://linux-hardware.org/?probe=0bf7d37cc9) | Aug 30, 2023 |
| Fujitsu       | LIFEBOOK U904               | Notebook    | [7cf4986142](https://linux-hardware.org/?probe=7cf4986142) | Aug 29, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [320e8d218f](https://linux-hardware.org/?probe=320e8d218f) | Aug 28, 2023 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [d238cd036a](https://linux-hardware.org/?probe=d238cd036a) | Aug 27, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [01a0f80107](https://linux-hardware.org/?probe=01a0f80107) | Aug 27, 2023 |
| ASUSTek       | X550VXK                     | Notebook    | [897e4f89ec](https://linux-hardware.org/?probe=897e4f89ec) | Aug 27, 2023 |
| Samsung       | 930QCG                      | Convertible | [3fb44943e6](https://linux-hardware.org/?probe=3fb44943e6) | Aug 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [95d23ba555](https://linux-hardware.org/?probe=95d23ba555) | Aug 27, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [657c08f61f](https://linux-hardware.org/?probe=657c08f61f) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Unknown       | V00                         | Mini pc     | [81085cf18b](https://linux-hardware.org/?probe=81085cf18b) | Aug 26, 2023 |
| Google        | Madoo                       | Notebook    | [6644bab363](https://linux-hardware.org/?probe=6644bab363) | Aug 26, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [2bbc495ee5](https://linux-hardware.org/?probe=2bbc495ee5) | Aug 25, 2023 |
| HP            | EliteBook 645 14 inch G9... | Notebook    | [d02a7851a6](https://linux-hardware.org/?probe=d02a7851a6) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| HP            | 1589                        | Desktop     | [982f4f1442](https://linux-hardware.org/?probe=982f4f1442) | Aug 24, 2023 |
| Dell          | Latitude E5470              | Notebook    | [637ccef7bd](https://linux-hardware.org/?probe=637ccef7bd) | Aug 24, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [34a96cbdc8](https://linux-hardware.org/?probe=34a96cbdc8) | Aug 24, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [816f3ce721](https://linux-hardware.org/?probe=816f3ce721) | Aug 24, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [ef3454780b](https://linux-hardware.org/?probe=ef3454780b) | Aug 23, 2023 |
| HP            | 250 G4                      | Notebook    | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | 18E4                        | Desktop     | [0235c76e04](https://linux-hardware.org/?probe=0235c76e04) | Aug 23, 2023 |
| Lenovo        | ThinkPad E495 20NES0KM00    | Notebook    | [783db5b84d](https://linux-hardware.org/?probe=783db5b84d) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [26d59e1060](https://linux-hardware.org/?probe=26d59e1060) | Aug 23, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [d10b0c4ca0](https://linux-hardware.org/?probe=d10b0c4ca0) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [c6a3274c8f](https://linux-hardware.org/?probe=c6a3274c8f) | Aug 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6cee16ebd6](https://linux-hardware.org/?probe=6cee16ebd6) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| MSI           | Katana 15 B13VGK            | Notebook    | [c21afd5e9f](https://linux-hardware.org/?probe=c21afd5e9f) | Aug 21, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b6aa75cb80](https://linux-hardware.org/?probe=b6aa75cb80) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [71853f1c36](https://linux-hardware.org/?probe=71853f1c36) | Aug 20, 2023 |
| Packard Be... | EasyNote TJ66               | Notebook    | [7e5e1655a6](https://linux-hardware.org/?probe=7e5e1655a6) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [d6df464cc7](https://linux-hardware.org/?probe=d6df464cc7) | Aug 20, 2023 |
| ASUSTek       | Zenbook UX3402ZA_Q409ZA     | Notebook    | [471f5f6132](https://linux-hardware.org/?probe=471f5f6132) | Aug 20, 2023 |
| Lenovo        | IdeaPad 110-15AST 80TR      | Notebook    | [60385dd9f0](https://linux-hardware.org/?probe=60385dd9f0) | Aug 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [e797880ede](https://linux-hardware.org/?probe=e797880ede) | Aug 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8bb2d02e4d](https://linux-hardware.org/?probe=8bb2d02e4d) | Aug 18, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [867105e269](https://linux-hardware.org/?probe=867105e269) | Aug 18, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [f99d3dca93](https://linux-hardware.org/?probe=f99d3dca93) | Aug 17, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [5ed6b3612a](https://linux-hardware.org/?probe=5ed6b3612a) | Aug 17, 2023 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [6e6a7171bf](https://linux-hardware.org/?probe=6e6a7171bf) | Aug 16, 2023 |
| HP            | 18E4                        | Desktop     | [4fd89c22ae](https://linux-hardware.org/?probe=4fd89c22ae) | Aug 14, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [1632c89b98](https://linux-hardware.org/?probe=1632c89b98) | Aug 13, 2023 |
| HP            | 8055                        | Desktop     | [a4c4208546](https://linux-hardware.org/?probe=a4c4208546) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [6cbef2a38d](https://linux-hardware.org/?probe=6cbef2a38d) | Aug 13, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d760e3f4c4](https://linux-hardware.org/?probe=d760e3f4c4) | Aug 13, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [17dacd99a6](https://linux-hardware.org/?probe=17dacd99a6) | Aug 12, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [083e25221d](https://linux-hardware.org/?probe=083e25221d) | Aug 10, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f6040edeb0](https://linux-hardware.org/?probe=f6040edeb0) | Aug 09, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [5a2d81b438](https://linux-hardware.org/?probe=5a2d81b438) | Aug 09, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3b02fcaeb7](https://linux-hardware.org/?probe=3b02fcaeb7) | Aug 09, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [bdc11616d7](https://linux-hardware.org/?probe=bdc11616d7) | Aug 08, 2023 |
| ASUSTek       | ROG Flow X16 GV601VI_GV6... | Convertible | [99ffb28c11](https://linux-hardware.org/?probe=99ffb28c11) | Aug 08, 2023 |
| ASRock        | B650 PG Lightning           | Desktop     | [bc55c09547](https://linux-hardware.org/?probe=bc55c09547) | Aug 06, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [0e79a19ed6](https://linux-hardware.org/?probe=0e79a19ed6) | Aug 06, 2023 |
| Dell          | Latitude E5570              | Notebook    | [cbcea81a37](https://linux-hardware.org/?probe=cbcea81a37) | Aug 06, 2023 |
| ASRock        | X570 Taichi                 | Desktop     | [34e27f60e0](https://linux-hardware.org/?probe=34e27f60e0) | Aug 05, 2023 |
| Toshiba       | PORTEGE R700                | Notebook    | [f0df061bb2](https://linux-hardware.org/?probe=f0df061bb2) | Aug 04, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [5f63621af2](https://linux-hardware.org/?probe=5f63621af2) | Aug 04, 2023 |
| Gigabyte      | H77-DS3H                    | Desktop     | [4c677637c2](https://linux-hardware.org/?probe=4c677637c2) | Aug 04, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [731ae84313](https://linux-hardware.org/?probe=731ae84313) | Aug 04, 2023 |
| Acer          | TravelMate P614-51-G2       | Notebook    | [33dd52a94f](https://linux-hardware.org/?probe=33dd52a94f) | Aug 03, 2023 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [7372322587](https://linux-hardware.org/?probe=7372322587) | Aug 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [a08886d394](https://linux-hardware.org/?probe=a08886d394) | Aug 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [fc2f2f7f45](https://linux-hardware.org/?probe=fc2f2f7f45) | Aug 02, 2023 |
| Sony          | VPCSB1V9R                   | Notebook    | [8d809c3877](https://linux-hardware.org/?probe=8d809c3877) | Aug 02, 2023 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [46ca3ef1f4](https://linux-hardware.org/?probe=46ca3ef1f4) | Aug 01, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [fd9503645f](https://linux-hardware.org/?probe=fd9503645f) | Aug 01, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [9e892c6bc7](https://linux-hardware.org/?probe=9e892c6bc7) | Aug 01, 2023 |
| Acer          | Aspire A317-53              | Notebook    | [3f1af34e1b](https://linux-hardware.org/?probe=3f1af34e1b) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [e24869945e](https://linux-hardware.org/?probe=e24869945e) | Aug 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [a2148fe49f](https://linux-hardware.org/?probe=a2148fe49f) | Aug 01, 2023 |
| ASUSTek       | PRIME Z790-A WIFI           | Desktop     | [13a4427208](https://linux-hardware.org/?probe=13a4427208) | Jul 31, 2023 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [5d12cf34ca](https://linux-hardware.org/?probe=5d12cf34ca) | Jul 31, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [ae14da63f3](https://linux-hardware.org/?probe=ae14da63f3) | Jul 30, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [4f94bdf300](https://linux-hardware.org/?probe=4f94bdf300) | Jul 30, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [f1db906c7c](https://linux-hardware.org/?probe=f1db906c7c) | Jul 30, 2023 |
| Samsung       | 960QFG                      | Convertible | [c14544a7ff](https://linux-hardware.org/?probe=c14544a7ff) | Jul 30, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [963eb3c0a8](https://linux-hardware.org/?probe=963eb3c0a8) | Jul 29, 2023 |
| HP            | EliteBook 2540p             | Notebook    | [cb13e61bae](https://linux-hardware.org/?probe=cb13e61bae) | Jul 28, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e08f65110d](https://linux-hardware.org/?probe=e08f65110d) | Jul 27, 2023 |
| Google        | Fleex                       | Notebook    | [977fa266d3](https://linux-hardware.org/?probe=977fa266d3) | Jul 27, 2023 |
| Lenovo        | ThinkPad E14 20RAS04C00     | Notebook    | [045470ba6d](https://linux-hardware.org/?probe=045470ba6d) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [24f65961ef](https://linux-hardware.org/?probe=24f65961ef) | Jul 26, 2023 |
| ASUSTek       | K53SD                       | Notebook    | [2cd6047230](https://linux-hardware.org/?probe=2cd6047230) | Jul 25, 2023 |
| HP            | ProBook 440 G2              | Notebook    | [85168259e3](https://linux-hardware.org/?probe=85168259e3) | Jul 25, 2023 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [0b4b6b015b](https://linux-hardware.org/?probe=0b4b6b015b) | Jul 24, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [351ebe5f4f](https://linux-hardware.org/?probe=351ebe5f4f) | Jul 24, 2023 |
| HP            | 250 G3                      | Notebook    | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [8b89c63576](https://linux-hardware.org/?probe=8b89c63576) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a179c222ea](https://linux-hardware.org/?probe=a179c222ea) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| Apple         | MacBookPro16,1              | Notebook    | [7f3a5aa8cd](https://linux-hardware.org/?probe=7f3a5aa8cd) | Jul 22, 2023 |
| HP            | 86F3 00100                  | All in one  | [26504c2968](https://linux-hardware.org/?probe=26504c2968) | Jul 22, 2023 |
| ASUSTek       | ROG Flow Z13 GZ301VU_GZ3... | Tablet      | [7387b87abf](https://linux-hardware.org/?probe=7387b87abf) | Jul 21, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [2a3971e2fc](https://linux-hardware.org/?probe=2a3971e2fc) | Jul 21, 2023 |
| HP            | 245 G8 Notebook PC          | Notebook    | [788fc0bfc9](https://linux-hardware.org/?probe=788fc0bfc9) | Jul 21, 2023 |
| ASUSTek       | G551JK                      | Notebook    | [fed0cf1fce](https://linux-hardware.org/?probe=fed0cf1fce) | Jul 20, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [9a705d5047](https://linux-hardware.org/?probe=9a705d5047) | Jul 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [cc73a658d1](https://linux-hardware.org/?probe=cc73a658d1) | Jul 19, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [7733ed8a40](https://linux-hardware.org/?probe=7733ed8a40) | Jul 19, 2023 |
| Lenovo        | ThinkPad L14 Gen 2a 20X5... | Notebook    | [4bba49b11c](https://linux-hardware.org/?probe=4bba49b11c) | Jul 19, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e6cf0622b0](https://linux-hardware.org/?probe=e6cf0622b0) | Jul 19, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [91f1d1f94f](https://linux-hardware.org/?probe=91f1d1f94f) | Jul 19, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [69a47b22c4](https://linux-hardware.org/?probe=69a47b22c4) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [32fbe34ce0](https://linux-hardware.org/?probe=32fbe34ce0) | Jul 18, 2023 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | Desktop     | [25aef4eda4](https://linux-hardware.org/?probe=25aef4eda4) | Jul 18, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [ef2395800e](https://linux-hardware.org/?probe=ef2395800e) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [d589d40102](https://linux-hardware.org/?probe=d589d40102) | Jul 15, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7e0ff09c1f](https://linux-hardware.org/?probe=7e0ff09c1f) | Jul 15, 2023 |
| Maibenben     | MaiBook M                   | Notebook    | [44a9f08c5e](https://linux-hardware.org/?probe=44a9f08c5e) | Jul 15, 2023 |
| Notebook      | NH5x_7xRCx,RDx              | Notebook    | [9e8ab59ea8](https://linux-hardware.org/?probe=9e8ab59ea8) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [2d03b5f0b6](https://linux-hardware.org/?probe=2d03b5f0b6) | Jul 14, 2023 |
| HP            | ENVY x360 Convertible       | Convertible | [13961b824f](https://linux-hardware.org/?probe=13961b824f) | Jul 14, 2023 |
| MSI           | B150M ECO                   | Desktop     | [84601cd9dc](https://linux-hardware.org/?probe=84601cd9dc) | Jul 14, 2023 |
| Lenovo        | ThinkPad T490s 20NYS4HL0... | Notebook    | [2213337296](https://linux-hardware.org/?probe=2213337296) | Jul 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [093938a09b](https://linux-hardware.org/?probe=093938a09b) | Jul 13, 2023 |
| OriginPC      | EVO16-S                     | Notebook    | [f3b1c85a1a](https://linux-hardware.org/?probe=f3b1c85a1a) | Jul 11, 2023 |
| Lenovo        | IdeaPad 5 14ITL05 82FE      | Notebook    | [fddf95e5c8](https://linux-hardware.org/?probe=fddf95e5c8) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4347661295](https://linux-hardware.org/?probe=4347661295) | Jul 11, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [94555c5887](https://linux-hardware.org/?probe=94555c5887) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [a497806f86](https://linux-hardware.org/?probe=a497806f86) | Jul 10, 2023 |
| Lenovo        | Yoga 730-15IWL 81JS         | Convertible | [93fcbdf5d5](https://linux-hardware.org/?probe=93fcbdf5d5) | Jul 10, 2023 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [160af9ddfb](https://linux-hardware.org/?probe=160af9ddfb) | Jul 09, 2023 |
| Lenovo        | ThinkPad A275 20KCS08C0K    | Notebook    | [9857dab3ab](https://linux-hardware.org/?probe=9857dab3ab) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | XPS 15 9530                 | Notebook    | [09ada263c3](https://linux-hardware.org/?probe=09ada263c3) | Jul 07, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [c5fcc4bcf0](https://linux-hardware.org/?probe=c5fcc4bcf0) | Jul 06, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f05e91be82](https://linux-hardware.org/?probe=f05e91be82) | Jul 06, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [60c1acd1fc](https://linux-hardware.org/?probe=60c1acd1fc) | Jul 04, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16IAH7 8... | Notebook    | [ad57a8dd50](https://linux-hardware.org/?probe=ad57a8dd50) | Jul 04, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [0064c1c269](https://linux-hardware.org/?probe=0064c1c269) | Jul 03, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f9e366002e](https://linux-hardware.org/?probe=f9e366002e) | Jul 03, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [c1a241c0a5](https://linux-hardware.org/?probe=c1a241c0a5) | Jul 03, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [6df7cc5145](https://linux-hardware.org/?probe=6df7cc5145) | Jul 02, 2023 |
| Dell          | Latitude E5470              | Notebook    | [0a50455c18](https://linux-hardware.org/?probe=0a50455c18) | Jul 02, 2023 |
| Lenovo        | Legion Y9000X IAH7 82TF     | Notebook    | [efb7d0f42a](https://linux-hardware.org/?probe=efb7d0f42a) | Jul 02, 2023 |
| Dell          | XPS L521X                   | Notebook    | [b80baf340c](https://linux-hardware.org/?probe=b80baf340c) | Jul 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [83dd07d2a7](https://linux-hardware.org/?probe=83dd07d2a7) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [1ab74730be](https://linux-hardware.org/?probe=1ab74730be) | Jul 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [b5f1dc88df](https://linux-hardware.org/?probe=b5f1dc88df) | Jul 01, 2023 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [916b60f6f7](https://linux-hardware.org/?probe=916b60f6f7) | Jun 30, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [287d7d6f60](https://linux-hardware.org/?probe=287d7d6f60) | Jun 29, 2023 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [f3cb4dc749](https://linux-hardware.org/?probe=f3cb4dc749) | Jun 29, 2023 |
| eMachines     | eME728                      | Notebook    | [37dc0ef617](https://linux-hardware.org/?probe=37dc0ef617) | Jun 29, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [89f1647ea1](https://linux-hardware.org/?probe=89f1647ea1) | Jun 29, 2023 |
| MSI           | A320M PRO-VH                | Desktop     | [1a84c61bd4](https://linux-hardware.org/?probe=1a84c61bd4) | Jun 27, 2023 |
| ASUSTek       | X455LJ                      | Notebook    | [c147d5716d](https://linux-hardware.org/?probe=c147d5716d) | Jun 27, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d0d602b518](https://linux-hardware.org/?probe=d0d602b518) | Jun 27, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | Notebook    | [e4b1fa692d](https://linux-hardware.org/?probe=e4b1fa692d) | Jun 25, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [e0f5116d38](https://linux-hardware.org/?probe=e0f5116d38) | Jun 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [7ac67acfed](https://linux-hardware.org/?probe=7ac67acfed) | Jun 21, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [481ef14837](https://linux-hardware.org/?probe=481ef14837) | Jun 21, 2023 |
| MSI           | B450M PRO-VDH               | Desktop     | [ed8ee7af2c](https://linux-hardware.org/?probe=ed8ee7af2c) | Jun 19, 2023 |
| ASRock        | Z77 Extreme4                | Desktop     | [78207fbf49](https://linux-hardware.org/?probe=78207fbf49) | Jun 19, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [90720c3820](https://linux-hardware.org/?probe=90720c3820) | Jun 18, 2023 |
| ASUSTek       | ROG Flow X16 GV601RW_GV6... | Convertible | [4b184d1037](https://linux-hardware.org/?probe=4b184d1037) | Jun 18, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [2bcd63ec1e](https://linux-hardware.org/?probe=2bcd63ec1e) | Jun 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [bc3ba9b05e](https://linux-hardware.org/?probe=bc3ba9b05e) | Jun 15, 2023 |
| ZOTAC         | ZBOX-EN760                  | Mini pc     | [e36c953da7](https://linux-hardware.org/?probe=e36c953da7) | Jun 14, 2023 |
| MSI           | B350M MORTAR                | Desktop     | [1050576987](https://linux-hardware.org/?probe=1050576987) | Jun 14, 2023 |
| Dell          | Latitude E5570              | Notebook    | [43171e0f19](https://linux-hardware.org/?probe=43171e0f19) | Jun 14, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [e8ed28dba0](https://linux-hardware.org/?probe=e8ed28dba0) | Jun 14, 2023 |
| Sony          | SVE1513B1EW                 | Notebook    | [3528d095e0](https://linux-hardware.org/?probe=3528d095e0) | Jun 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [2db1bbb316](https://linux-hardware.org/?probe=2db1bbb316) | Jun 13, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [507d8cc765](https://linux-hardware.org/?probe=507d8cc765) | Jun 13, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [21a8144a2e](https://linux-hardware.org/?probe=21a8144a2e) | Jun 13, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [51a3b444dd](https://linux-hardware.org/?probe=51a3b444dd) | Jun 13, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [c433d533f0](https://linux-hardware.org/?probe=c433d533f0) | Jun 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [3c7683dfc4](https://linux-hardware.org/?probe=3c7683dfc4) | Jun 11, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [33579719ed](https://linux-hardware.org/?probe=33579719ed) | Jun 11, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [1d46e48d92](https://linux-hardware.org/?probe=1d46e48d92) | Jun 10, 2023 |
| Dell          | Latitude E6510              | Notebook    | [e7c1e59ac7](https://linux-hardware.org/?probe=e7c1e59ac7) | Jun 10, 2023 |
| Dell          | 0DWPVW A00                  | Desktop     | [ffad802816](https://linux-hardware.org/?probe=ffad802816) | Jun 10, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [2627421665](https://linux-hardware.org/?probe=2627421665) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [ab95a219f5](https://linux-hardware.org/?probe=ab95a219f5) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [a597fc235e](https://linux-hardware.org/?probe=a597fc235e) | Jun 09, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [6a368b8ecc](https://linux-hardware.org/?probe=6a368b8ecc) | Jun 09, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [2f0f8eb596](https://linux-hardware.org/?probe=2f0f8eb596) | Jun 09, 2023 |
| VIT           | P2402                       | Notebook    | [5ea93f652a](https://linux-hardware.org/?probe=5ea93f652a) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [52df878410](https://linux-hardware.org/?probe=52df878410) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [3e38c53463](https://linux-hardware.org/?probe=3e38c53463) | Jun 07, 2023 |
| Dell          | Vostro 1015                 | Notebook    | [0e24e0ad6c](https://linux-hardware.org/?probe=0e24e0ad6c) | Jun 07, 2023 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [33fb312b6d](https://linux-hardware.org/?probe=33fb312b6d) | Jun 05, 2023 |
| Dell          | 0D24M8 A00                  | Desktop     | [92fe930ecf](https://linux-hardware.org/?probe=92fe930ecf) | Jun 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [cadfadec0e](https://linux-hardware.org/?probe=cadfadec0e) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [bfe6623b23](https://linux-hardware.org/?probe=bfe6623b23) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| ASUSTek       | H97-PRO                     | Desktop     | [c3dae64ee6](https://linux-hardware.org/?probe=c3dae64ee6) | Jun 03, 2023 |
| TUXEDO        | InfinityBook Pro 15 v5      | Notebook    | [1b01df33d2](https://linux-hardware.org/?probe=1b01df33d2) | Jun 03, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [04830d213f](https://linux-hardware.org/?probe=04830d213f) | Jun 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [4ccfddd671](https://linux-hardware.org/?probe=4ccfddd671) | Jun 02, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [becb85a201](https://linux-hardware.org/?probe=becb85a201) | Jun 02, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [c4cd05b00f](https://linux-hardware.org/?probe=c4cd05b00f) | Jun 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TN34... | Convertible | [7d35807036](https://linux-hardware.org/?probe=7d35807036) | Jun 01, 2023 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | Notebook    | [3de415ea72](https://linux-hardware.org/?probe=3de415ea72) | Jun 01, 2023 |
| MSI           | MEG X670E ACE               | Desktop     | [8bc281486e](https://linux-hardware.org/?probe=8bc281486e) | May 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c198463bc3](https://linux-hardware.org/?probe=c198463bc3) | May 31, 2023 |
| Lenovo        | Legion Y540-17IRH 81Q4      | Notebook    | [87d9c3f3a1](https://linux-hardware.org/?probe=87d9c3f3a1) | May 31, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [3b186c07a2](https://linux-hardware.org/?probe=3b186c07a2) | May 30, 2023 |
| ASUSTek       | GL553VD                     | Notebook    | [a1f825f4e5](https://linux-hardware.org/?probe=a1f825f4e5) | May 29, 2023 |
| Lenovo        | ThinkPad X230 23252UU       | Notebook    | [7819b88c10](https://linux-hardware.org/?probe=7819b88c10) | May 29, 2023 |
| Lenovo        | ThinkPad T480 20L5A00PCD    | Notebook    | [0b04d3bf20](https://linux-hardware.org/?probe=0b04d3bf20) | May 28, 2023 |
| ASUSTek       | X455LF                      | Notebook    | [b90c1083ca](https://linux-hardware.org/?probe=b90c1083ca) | May 28, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [574e88c4f3](https://linux-hardware.org/?probe=574e88c4f3) | May 28, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [af33101302](https://linux-hardware.org/?probe=af33101302) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [8621305f75](https://linux-hardware.org/?probe=8621305f75) | May 27, 2023 |
| HP            | 86EE                        | All in one  | [ba49672c5b](https://linux-hardware.org/?probe=ba49672c5b) | May 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4362f979b8](https://linux-hardware.org/?probe=4362f979b8) | May 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [4c22ef876f](https://linux-hardware.org/?probe=4c22ef876f) | May 26, 2023 |
| Apple         | MacBookPro16,2              | Notebook    | [46cb91a74d](https://linux-hardware.org/?probe=46cb91a74d) | May 25, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48bd340a09](https://linux-hardware.org/?probe=48bd340a09) | May 24, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [7f5d36cc34](https://linux-hardware.org/?probe=7f5d36cc34) | May 23, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [b7fbda70d3](https://linux-hardware.org/?probe=b7fbda70d3) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a605d12e2d](https://linux-hardware.org/?probe=a605d12e2d) | May 23, 2023 |
| HP            | 158A                        | Desktop     | [a1770c45b0](https://linux-hardware.org/?probe=a1770c45b0) | May 23, 2023 |
| Gigabyte      | Z790 UD AX                  | Desktop     | [0cba90ce8e](https://linux-hardware.org/?probe=0cba90ce8e) | May 23, 2023 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [a48977a871](https://linux-hardware.org/?probe=a48977a871) | May 22, 2023 |
| HP            | Laptop 14s-dk1xxx           | Notebook    | [d9f9d8c907](https://linux-hardware.org/?probe=d9f9d8c907) | May 22, 2023 |
| HP            | 18E4                        | Desktop     | [5601900c8b](https://linux-hardware.org/?probe=5601900c8b) | May 22, 2023 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [73dfd22efc](https://linux-hardware.org/?probe=73dfd22efc) | May 21, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [b7655822d2](https://linux-hardware.org/?probe=b7655822d2) | May 19, 2023 |
| Acer          | Aspire A315-42G             | Notebook    | [1125a4111e](https://linux-hardware.org/?probe=1125a4111e) | May 19, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [1edee9f902](https://linux-hardware.org/?probe=1edee9f902) | May 18, 2023 |
| Lenovo        | 3734 SDK0R32862 WIN 3258... | All in one  | [da9ebc680a](https://linux-hardware.org/?probe=da9ebc680a) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [7560196205](https://linux-hardware.org/?probe=7560196205) | May 16, 2023 |
| HP            | 18E4                        | Desktop     | [4dc91feab7](https://linux-hardware.org/?probe=4dc91feab7) | May 14, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [59a9ba6e16](https://linux-hardware.org/?probe=59a9ba6e16) | May 13, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [4fd655c0aa](https://linux-hardware.org/?probe=4fd655c0aa) | May 13, 2023 |
| Dell          | Inspiron 5577               | Notebook    | [e4bfe14f2d](https://linux-hardware.org/?probe=e4bfe14f2d) | May 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [bc0dacd119](https://linux-hardware.org/?probe=bc0dacd119) | May 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [35d056f8bd](https://linux-hardware.org/?probe=35d056f8bd) | May 11, 2023 |
| ASUSTek       | N56VB                       | Notebook    | [e914b76fef](https://linux-hardware.org/?probe=e914b76fef) | May 10, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6 82JS    | Notebook    | [d764690667](https://linux-hardware.org/?probe=d764690667) | May 10, 2023 |
| HP            | 18E4                        | Desktop     | [2a528dc758](https://linux-hardware.org/?probe=2a528dc758) | May 10, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [b81c403545](https://linux-hardware.org/?probe=b81c403545) | May 09, 2023 |
| Lenovo        | ThinkPad Yoga 370 20JJS0... | Convertible | [3346a6a326](https://linux-hardware.org/?probe=3346a6a326) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [2a7a243899](https://linux-hardware.org/?probe=2a7a243899) | May 09, 2023 |
| Lenovo        | ThinkPad 11e Yoga Gen 6 ... | Convertible | [c7a298018f](https://linux-hardware.org/?probe=c7a298018f) | May 08, 2023 |
| Lenovo        | G560 0679                   | Notebook    | [a916fc6080](https://linux-hardware.org/?probe=a916fc6080) | May 08, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [7a1ffd8bd2](https://linux-hardware.org/?probe=7a1ffd8bd2) | May 07, 2023 |
| Timi          | TM1701                      | Notebook    | [c41d566374](https://linux-hardware.org/?probe=c41d566374) | May 07, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [acd4c4af90](https://linux-hardware.org/?probe=acd4c4af90) | May 07, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [7ab24c2d1a](https://linux-hardware.org/?probe=7ab24c2d1a) | May 06, 2023 |
| Lenovo        | ThinkPad L13 Yoga 20R6S0... | Convertible | [df58b07032](https://linux-hardware.org/?probe=df58b07032) | May 06, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| HP            | 1589                        | Desktop     | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [8ff62a5045](https://linux-hardware.org/?probe=8ff62a5045) | May 05, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [bac25fa124](https://linux-hardware.org/?probe=bac25fa124) | May 04, 2023 |
| Lenovo        | ThinkPad W530 24473F2       | Notebook    | [937dddbff0](https://linux-hardware.org/?probe=937dddbff0) | May 04, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [4aec6123b0](https://linux-hardware.org/?probe=4aec6123b0) | May 04, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [e49682836a](https://linux-hardware.org/?probe=e49682836a) | May 04, 2023 |
| HP            | 18E4                        | Desktop     | [d1344e36dd](https://linux-hardware.org/?probe=d1344e36dd) | May 03, 2023 |
| Lenovo        | Legion 5 15ARH7H 82RD       | Notebook    | [9984dd7707](https://linux-hardware.org/?probe=9984dd7707) | May 03, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [16ac84221b](https://linux-hardware.org/?probe=16ac84221b) | May 02, 2023 |
| Notebook      | NS5x_NS7xPU                 | Notebook    | [c775137d4f](https://linux-hardware.org/?probe=c775137d4f) | May 02, 2023 |
| Daten Tecn... | DH110MXV                    | Desktop     | [96402fa64a](https://linux-hardware.org/?probe=96402fa64a) | May 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [07324ae678](https://linux-hardware.org/?probe=07324ae678) | May 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [24363c23cf](https://linux-hardware.org/?probe=24363c23cf) | May 01, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [1a343a4622](https://linux-hardware.org/?probe=1a343a4622) | Apr 30, 2023 |
| Dell          | Latitude 5580               | Notebook    | [556abc1561](https://linux-hardware.org/?probe=556abc1561) | Apr 30, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [54f8ed91cf](https://linux-hardware.org/?probe=54f8ed91cf) | Apr 30, 2023 |
| HP            | 18E4                        | Desktop     | [da858ea464](https://linux-hardware.org/?probe=da858ea464) | Apr 30, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [f767bfff00](https://linux-hardware.org/?probe=f767bfff00) | Apr 29, 2023 |
| Gigabyte      | B365M D3H-CF                | Desktop     | [8c4352985e](https://linux-hardware.org/?probe=8c4352985e) | Apr 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [c1e0f0fa03](https://linux-hardware.org/?probe=c1e0f0fa03) | Apr 29, 2023 |
| Timi          | Redmi Book Pro 15 2022      | Notebook    | [a8adc86550](https://linux-hardware.org/?probe=a8adc86550) | Apr 28, 2023 |
| HP            | 8715                        | Mini pc     | [8d210cce39](https://linux-hardware.org/?probe=8d210cce39) | Apr 28, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [f1d5d361d5](https://linux-hardware.org/?probe=f1d5d361d5) | Apr 27, 2023 |
| MSI           | Modern 14 C7M               | Notebook    | [5946c9a0d2](https://linux-hardware.org/?probe=5946c9a0d2) | Apr 27, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [496934207f](https://linux-hardware.org/?probe=496934207f) | Apr 25, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [0466417666](https://linux-hardware.org/?probe=0466417666) | Apr 25, 2023 |
| Notebook      | NH5x_NH7xHP                 | Notebook    | [6f1c24d844](https://linux-hardware.org/?probe=6f1c24d844) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [47ac6239d5](https://linux-hardware.org/?probe=47ac6239d5) | Apr 24, 2023 |
| Lenovo        | ThinkPad T480s 20L8S0ER0... | Notebook    | [a05c41b44d](https://linux-hardware.org/?probe=a05c41b44d) | Apr 24, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [b935ad65e3](https://linux-hardware.org/?probe=b935ad65e3) | Apr 22, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [17ae2e245a](https://linux-hardware.org/?probe=17ae2e245a) | Apr 22, 2023 |
| Notebook      | W65_W67RB                   | Notebook    | [f34e442b8b](https://linux-hardware.org/?probe=f34e442b8b) | Apr 22, 2023 |
| MSI           | GP60 2QE                    | Notebook    | [550a1cee3b](https://linux-hardware.org/?probe=550a1cee3b) | Apr 22, 2023 |
| ASUSTek       | ROG Strix G513IM_G513IM     | Notebook    | [00f7379c8f](https://linux-hardware.org/?probe=00f7379c8f) | Apr 21, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [d26a12b2e3](https://linux-hardware.org/?probe=d26a12b2e3) | Apr 21, 2023 |
| Unknown       | Unknown                     | Desktop     | [c27abc2880](https://linux-hardware.org/?probe=c27abc2880) | Apr 17, 2023 |
| ASUSTek       | X55A                        | Notebook    | [c5386929ba](https://linux-hardware.org/?probe=c5386929ba) | Apr 17, 2023 |
| Lenovo        | ThinkPad T490 20N20008US    | Notebook    | [f365509651](https://linux-hardware.org/?probe=f365509651) | Apr 15, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f6a652b68d](https://linux-hardware.org/?probe=f6a652b68d) | Apr 14, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [8eaac4a62d](https://linux-hardware.org/?probe=8eaac4a62d) | Apr 13, 2023 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [abf6dd7200](https://linux-hardware.org/?probe=abf6dd7200) | Apr 13, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [47f2ba894b](https://linux-hardware.org/?probe=47f2ba894b) | Apr 12, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [07353da9f6](https://linux-hardware.org/?probe=07353da9f6) | Apr 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d9f95c9169](https://linux-hardware.org/?probe=d9f95c9169) | Apr 11, 2023 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [0e074bebcf](https://linux-hardware.org/?probe=0e074bebcf) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [59db7a4f11](https://linux-hardware.org/?probe=59db7a4f11) | Apr 10, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [01cae1e152](https://linux-hardware.org/?probe=01cae1e152) | Apr 10, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ccf16cae6a](https://linux-hardware.org/?probe=ccf16cae6a) | Apr 10, 2023 |
| HP            | 18E4                        | Desktop     | [54c681affc](https://linux-hardware.org/?probe=54c681affc) | Apr 10, 2023 |
| Lenovo        | ThinkPad T450 20BUS0QT04    | Notebook    | [90d7e2bb21](https://linux-hardware.org/?probe=90d7e2bb21) | Apr 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [ea22560713](https://linux-hardware.org/?probe=ea22560713) | Apr 09, 2023 |
| Acer          | Aspire E5-575               | Notebook    | [15d7d40bed](https://linux-hardware.org/?probe=15d7d40bed) | Apr 09, 2023 |
| Lenovo        | ThinkPad L14 Gen 3 21C6S... | Notebook    | [aee22ee8b3](https://linux-hardware.org/?probe=aee22ee8b3) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [d1167f66b8](https://linux-hardware.org/?probe=d1167f66b8) | Apr 08, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [a6c5efe560](https://linux-hardware.org/?probe=a6c5efe560) | Apr 07, 2023 |
| HP            | 250 G4                      | Notebook    | [3e85d0e3ef](https://linux-hardware.org/?probe=3e85d0e3ef) | Apr 06, 2023 |
| HP            | Unknown                     | Notebook    | [0af30fd642](https://linux-hardware.org/?probe=0af30fd642) | Apr 06, 2023 |
| Gigabyte      | H87M-D3H                    | Desktop     | [b9c169025d](https://linux-hardware.org/?probe=b9c169025d) | Apr 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [c31fccd9d8](https://linux-hardware.org/?probe=c31fccd9d8) | Apr 05, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [258f32d502](https://linux-hardware.org/?probe=258f32d502) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [5012c822d7](https://linux-hardware.org/?probe=5012c822d7) | Apr 05, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [33eb81c75e](https://linux-hardware.org/?probe=33eb81c75e) | Apr 05, 2023 |
| MSI           | Modern 15 A11SBU            | Notebook    | [269c7d638e](https://linux-hardware.org/?probe=269c7d638e) | Apr 05, 2023 |
| Lenovo        | ThinkBook 13s G4 ARB 21A... | Notebook    | [546e8e3742](https://linux-hardware.org/?probe=546e8e3742) | Apr 04, 2023 |
| Samsung       | 950QDB                      | Convertible | [967646c481](https://linux-hardware.org/?probe=967646c481) | Apr 04, 2023 |
| Dell          | Inspiron 5402               | Notebook    | [5035f094da](https://linux-hardware.org/?probe=5035f094da) | Apr 03, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [d3a27ee996](https://linux-hardware.org/?probe=d3a27ee996) | Apr 03, 2023 |
| Lenovo        | ThinkBook 16 G4+ ARA 21D... | Notebook    | [9ba99b597e](https://linux-hardware.org/?probe=9ba99b597e) | Apr 03, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [d64af320d7](https://linux-hardware.org/?probe=d64af320d7) | Apr 02, 2023 |
| Apple         | MacBookAir6,2               | Notebook    | [3400bd9412](https://linux-hardware.org/?probe=3400bd9412) | Apr 02, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2R40... | Notebook    | [edb6e927bd](https://linux-hardware.org/?probe=edb6e927bd) | Apr 02, 2023 |
| PC Special... | Elimina Iv 17               | Notebook    | [0681af5346](https://linux-hardware.org/?probe=0681af5346) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [bfba694531](https://linux-hardware.org/?probe=bfba694531) | Apr 01, 2023 |
| HP            | 8715                        | Mini pc     | [bcd377dcb7](https://linux-hardware.org/?probe=bcd377dcb7) | Apr 01, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0K    | Notebook    | [4169f13182](https://linux-hardware.org/?probe=4169f13182) | Apr 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [016ddeab52](https://linux-hardware.org/?probe=016ddeab52) | Mar 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [3ac0a9cc94](https://linux-hardware.org/?probe=3ac0a9cc94) | Mar 31, 2023 |
| GPD           | G1621-02                    | Notebook    | [7d000ab41b](https://linux-hardware.org/?probe=7d000ab41b) | Mar 31, 2023 |
| HP            | 8715                        | Mini pc     | [222fde0a83](https://linux-hardware.org/?probe=222fde0a83) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [008eb6ad60](https://linux-hardware.org/?probe=008eb6ad60) | Mar 31, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [4dd142ab8f](https://linux-hardware.org/?probe=4dd142ab8f) | Mar 31, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8953aa2e04](https://linux-hardware.org/?probe=8953aa2e04) | Mar 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M140... | Notebook    | [d1295d9d1e](https://linux-hardware.org/?probe=d1295d9d1e) | Mar 30, 2023 |
| AWOW          | AL34                        | Notebook    | [19f60f27c8](https://linux-hardware.org/?probe=19f60f27c8) | Mar 29, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [65671e15cb](https://linux-hardware.org/?probe=65671e15cb) | Mar 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | Notebook    | [c1f1d2bcc8](https://linux-hardware.org/?probe=c1f1d2bcc8) | Mar 28, 2023 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [b165f54c80](https://linux-hardware.org/?probe=b165f54c80) | Mar 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fa77641b57](https://linux-hardware.org/?probe=fa77641b57) | Mar 27, 2023 |
| HP            | Pavilion Laptop 15-eh2xx... | Notebook    | [d80388d7ef](https://linux-hardware.org/?probe=d80388d7ef) | Mar 27, 2023 |
| HP            | 18E4                        | Desktop     | [5d10e73e1d](https://linux-hardware.org/?probe=5d10e73e1d) | Mar 26, 2023 |
| ASUSTek       | N76VM                       | Notebook    | [0a05b4b5ce](https://linux-hardware.org/?probe=0a05b4b5ce) | Mar 26, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [a8d31fc431](https://linux-hardware.org/?probe=a8d31fc431) | Mar 26, 2023 |
| ASUSTek       | STRIX Z270I GAMING          | Desktop     | [4253088a92](https://linux-hardware.org/?probe=4253088a92) | Mar 25, 2023 |
| Samsung       | 550XDA                      | Notebook    | [058982f7d8](https://linux-hardware.org/?probe=058982f7d8) | Mar 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [18cd806803](https://linux-hardware.org/?probe=18cd806803) | Mar 24, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E6C... | Notebook    | [3042a430c0](https://linux-hardware.org/?probe=3042a430c0) | Mar 24, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [e923cf7edb](https://linux-hardware.org/?probe=e923cf7edb) | Mar 24, 2023 |
| ASUSTek       | PRIME X670-P WIFI           | Desktop     | [5bd922e142](https://linux-hardware.org/?probe=5bd922e142) | Mar 23, 2023 |
| AZW           | GK35                        | Desktop     | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| HP            | EliteBook 850 G1            | Notebook    | [a27ad7df2d](https://linux-hardware.org/?probe=a27ad7df2d) | Mar 22, 2023 |
| GPD           | G1619-04                    | Notebook    | [c69bb703ae](https://linux-hardware.org/?probe=c69bb703ae) | Mar 21, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [e0ec2e73be](https://linux-hardware.org/?probe=e0ec2e73be) | Mar 21, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a0ebd92c60](https://linux-hardware.org/?probe=a0ebd92c60) | Mar 21, 2023 |
| Acer          | Swift SF315-52G             | Notebook    | [f6042580d0](https://linux-hardware.org/?probe=f6042580d0) | Mar 20, 2023 |
| Notebook      | N150ZU                      | Notebook    | [4b7d1e249f](https://linux-hardware.org/?probe=4b7d1e249f) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [b82aade579](https://linux-hardware.org/?probe=b82aade579) | Mar 19, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [361ca1537d](https://linux-hardware.org/?probe=361ca1537d) | Mar 19, 2023 |
| Timi          | Xiaomi NoteBook Pro         | Notebook    | [a911c14f22](https://linux-hardware.org/?probe=a911c14f22) | Mar 19, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5f14b733bb](https://linux-hardware.org/?probe=5f14b733bb) | Mar 19, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [6dda9bae81](https://linux-hardware.org/?probe=6dda9bae81) | Mar 18, 2023 |
| ASUSTek       | UX301LAA                    | Notebook    | [882d4d095b](https://linux-hardware.org/?probe=882d4d095b) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [1c2c765978](https://linux-hardware.org/?probe=1c2c765978) | Mar 18, 2023 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [809d9ecb40](https://linux-hardware.org/?probe=809d9ecb40) | Mar 18, 2023 |
| MSI           | MAG X570S TORPEDO MAX       | Desktop     | [a3e8bcd9dd](https://linux-hardware.org/?probe=a3e8bcd9dd) | Mar 18, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [ae4d8ba68c](https://linux-hardware.org/?probe=ae4d8ba68c) | Mar 18, 2023 |
| AZW           | U59                         | Desktop     | [ce6bd37711](https://linux-hardware.org/?probe=ce6bd37711) | Mar 18, 2023 |
| HP            | 8715                        | Mini pc     | [cd9310c350](https://linux-hardware.org/?probe=cd9310c350) | Mar 17, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [b43ea7bb6e](https://linux-hardware.org/?probe=b43ea7bb6e) | Mar 17, 2023 |
| Toshiba       | Satellite C55-C             | Notebook    | [9d2c56bf69](https://linux-hardware.org/?probe=9d2c56bf69) | Mar 17, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [c6ef926aa6](https://linux-hardware.org/?probe=c6ef926aa6) | Mar 17, 2023 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [d95b09eda0](https://linux-hardware.org/?probe=d95b09eda0) | Mar 17, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [066f0cd17b](https://linux-hardware.org/?probe=066f0cd17b) | Mar 15, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [daa3d3869e](https://linux-hardware.org/?probe=daa3d3869e) | Mar 14, 2023 |
| Lenovo        | ThinkPad T430 23426QU       | Notebook    | [b588252431](https://linux-hardware.org/?probe=b588252431) | Mar 14, 2023 |
| Dell          | XPS 15 9520                 | Notebook    | [0f3b7bd317](https://linux-hardware.org/?probe=0f3b7bd317) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [7f58d0d0a0](https://linux-hardware.org/?probe=7f58d0d0a0) | Mar 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Notebook    | [0c58b8ebad](https://linux-hardware.org/?probe=0c58b8ebad) | Mar 13, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [fc04961aef](https://linux-hardware.org/?probe=fc04961aef) | Mar 11, 2023 |
| Unknown       | HX90                        | Desktop     | [51aca581e4](https://linux-hardware.org/?probe=51aca581e4) | Mar 11, 2023 |
| MSI           | B450I GAMING PLUS AC        | Desktop     | [bf6081f2af](https://linux-hardware.org/?probe=bf6081f2af) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [6132f690aa](https://linux-hardware.org/?probe=6132f690aa) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [8a33917a89](https://linux-hardware.org/?probe=8a33917a89) | Mar 09, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop S540... | Notebook    | [f4d71dcbd0](https://linux-hardware.org/?probe=f4d71dcbd0) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0fdb67b9d2](https://linux-hardware.org/?probe=0fdb67b9d2) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e48f233a0](https://linux-hardware.org/?probe=2e48f233a0) | Mar 09, 2023 |
| Dell          | Precision 7720              | Notebook    | [e4a1149bcb](https://linux-hardware.org/?probe=e4a1149bcb) | Mar 08, 2023 |
| Dell          | 0KWVT8 A03                  | Desktop     | [af171db9dc](https://linux-hardware.org/?probe=af171db9dc) | Mar 08, 2023 |
| Timi          | TM1701                      | Notebook    | [3a94d06b73](https://linux-hardware.org/?probe=3a94d06b73) | Mar 07, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [f363dca8ca](https://linux-hardware.org/?probe=f363dca8ca) | Mar 07, 2023 |
| HP            | 8860 A                      | Desktop     | [78c9aa9174](https://linux-hardware.org/?probe=78c9aa9174) | Mar 07, 2023 |
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [54ad36532c](https://linux-hardware.org/?probe=54ad36532c) | Mar 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [be24c7e178](https://linux-hardware.org/?probe=be24c7e178) | Mar 07, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [3519073f46](https://linux-hardware.org/?probe=3519073f46) | Mar 07, 2023 |
| Dell          | Latitude 5289               | Notebook    | [dcac5b8ebc](https://linux-hardware.org/?probe=dcac5b8ebc) | Mar 06, 2023 |
| Google        | Rammus                      | Notebook    | [0d905c6981](https://linux-hardware.org/?probe=0d905c6981) | Mar 05, 2023 |
| HP            | 18E4                        | Desktop     | [a277b636c1](https://linux-hardware.org/?probe=a277b636c1) | Mar 05, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [1ac55121cf](https://linux-hardware.org/?probe=1ac55121cf) | Mar 05, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [a4941ea70f](https://linux-hardware.org/?probe=a4941ea70f) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [f27119aef2](https://linux-hardware.org/?probe=f27119aef2) | Mar 03, 2023 |
| HP            | 18E4                        | Desktop     | [8e76736e7e](https://linux-hardware.org/?probe=8e76736e7e) | Mar 02, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [80dca547fc](https://linux-hardware.org/?probe=80dca547fc) | Mar 01, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [89fb184b09](https://linux-hardware.org/?probe=89fb184b09) | Mar 01, 2023 |
| HP            | 18E4                        | Desktop     | [cab6d807e9](https://linux-hardware.org/?probe=cab6d807e9) | Feb 27, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [83cb442ad5](https://linux-hardware.org/?probe=83cb442ad5) | Feb 27, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [1412fd5885](https://linux-hardware.org/?probe=1412fd5885) | Feb 26, 2023 |
| HP            | 18E4                        | Desktop     | [5c7c3413c9](https://linux-hardware.org/?probe=5c7c3413c9) | Feb 26, 2023 |
| Lenovo        | Y50-70 20378                | Notebook    | [005749f4ef](https://linux-hardware.org/?probe=005749f4ef) | Feb 26, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [612418b6e7](https://linux-hardware.org/?probe=612418b6e7) | Feb 25, 2023 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [ccff1403b0](https://linux-hardware.org/?probe=ccff1403b0) | Feb 24, 2023 |
| Intel         | NUC7JYB J67967-404          | Mini pc     | [32f4f192fa](https://linux-hardware.org/?probe=32f4f192fa) | Feb 24, 2023 |
| ASUSTek       | M32CD_A_F_K20CD_K31CD       | Desktop     | [576a0fc8f5](https://linux-hardware.org/?probe=576a0fc8f5) | Feb 23, 2023 |
| Medion        | Akoya E6412T                | Notebook    | [2915d1c409](https://linux-hardware.org/?probe=2915d1c409) | Feb 23, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [8a638dd3a7](https://linux-hardware.org/?probe=8a638dd3a7) | Feb 23, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [e62c134a68](https://linux-hardware.org/?probe=e62c134a68) | Feb 22, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f7f94aa827](https://linux-hardware.org/?probe=f7f94aa827) | Feb 22, 2023 |
| ASRock        | B460 Steel Legend           | Desktop     | [e8963c4e59](https://linux-hardware.org/?probe=e8963c4e59) | Feb 21, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [d5f5531b82](https://linux-hardware.org/?probe=d5f5531b82) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [05ce3a9038](https://linux-hardware.org/?probe=05ce3a9038) | Feb 20, 2023 |
| ASUSTek       | ROG Strix G712LWS_G712LW... | Notebook    | [661017eb0b](https://linux-hardware.org/?probe=661017eb0b) | Feb 20, 2023 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f55697d9b3](https://linux-hardware.org/?probe=f55697d9b3) | Feb 19, 2023 |
| ASUSTek       | S551LN                      | Notebook    | [ff5df2cf03](https://linux-hardware.org/?probe=ff5df2cf03) | Feb 19, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [6234395029](https://linux-hardware.org/?probe=6234395029) | Feb 18, 2023 |
| Chuwi         | GemiBook Pro                | Notebook    | [7af4d238e8](https://linux-hardware.org/?probe=7af4d238e8) | Feb 18, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [09b0c2bf17](https://linux-hardware.org/?probe=09b0c2bf17) | Feb 17, 2023 |
| Gigabyte      | B450M S2H                   | Desktop     | [f594570a77](https://linux-hardware.org/?probe=f594570a77) | Feb 16, 2023 |
| Google        | Helios                      | Notebook    | [4505c27d12](https://linux-hardware.org/?probe=4505c27d12) | Feb 16, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [6c7f73c4a5](https://linux-hardware.org/?probe=6c7f73c4a5) | Feb 16, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [b0693958a6](https://linux-hardware.org/?probe=b0693958a6) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [c84212b39c](https://linux-hardware.org/?probe=c84212b39c) | Feb 15, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [6c540405e8](https://linux-hardware.org/?probe=6c540405e8) | Feb 15, 2023 |
| GPD           | G1621-02                    | Notebook    | [5d584fa1cf](https://linux-hardware.org/?probe=5d584fa1cf) | Feb 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop TP42... | Convertible | [4b0331863e](https://linux-hardware.org/?probe=4b0331863e) | Feb 14, 2023 |
| Alienware     | 0VDT73 A00                  | Desktop     | [d8ed5d5e88](https://linux-hardware.org/?probe=d8ed5d5e88) | Feb 14, 2023 |
| HP            | Laptop 15s-fq4xxx           | Notebook    | [9d1c8bca14](https://linux-hardware.org/?probe=9d1c8bca14) | Feb 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [820aa2bf49](https://linux-hardware.org/?probe=820aa2bf49) | Feb 13, 2023 |
| ASUSTek       | ROG Zephyrus G15 GA503RM    | Notebook    | [9e0e0bef82](https://linux-hardware.org/?probe=9e0e0bef82) | Feb 13, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [debdb17904](https://linux-hardware.org/?probe=debdb17904) | Feb 12, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8133fc11b8](https://linux-hardware.org/?probe=8133fc11b8) | Feb 12, 2023 |
| MSI           | 760GMA-P34                  | Desktop     | [05d11c4fe3](https://linux-hardware.org/?probe=05d11c4fe3) | Feb 12, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [632c139c4b](https://linux-hardware.org/?probe=632c139c4b) | Feb 12, 2023 |
| HP            | Compaq 6820s                | Notebook    | [6c67866714](https://linux-hardware.org/?probe=6c67866714) | Feb 12, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [0c6da36f9d](https://linux-hardware.org/?probe=0c6da36f9d) | Feb 11, 2023 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [059d515c3c](https://linux-hardware.org/?probe=059d515c3c) | Feb 09, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [96d63ff41b](https://linux-hardware.org/?probe=96d63ff41b) | Feb 08, 2023 |
| Dell          | 0Y5FXV A00                  | Desktop     | [692b7eab6b](https://linux-hardware.org/?probe=692b7eab6b) | Feb 08, 2023 |
| Lenovo        | ThinkPad T495s 20QKS2LN0... | Notebook    | [4fdb5d662c](https://linux-hardware.org/?probe=4fdb5d662c) | Feb 08, 2023 |
| HP            | ENVY Notebook PC            | Convertible | [a8165997b7](https://linux-hardware.org/?probe=a8165997b7) | Feb 06, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [43c3e4d160](https://linux-hardware.org/?probe=43c3e4d160) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [f2a6af1f7e](https://linux-hardware.org/?probe=f2a6af1f7e) | Feb 06, 2023 |
| HP            | Setzer                      | Notebook    | [bd65b300ae](https://linux-hardware.org/?probe=bd65b300ae) | Feb 06, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [e523dbd162](https://linux-hardware.org/?probe=e523dbd162) | Feb 02, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [96847498e3](https://linux-hardware.org/?probe=96847498e3) | Feb 02, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [ecf260f299](https://linux-hardware.org/?probe=ecf260f299) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [de7f0840d1](https://linux-hardware.org/?probe=de7f0840d1) | Feb 01, 2023 |
| Microsoft     | Surface Laptop Go           | Tablet      | [455825998f](https://linux-hardware.org/?probe=455825998f) | Feb 01, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4251ab2f9a](https://linux-hardware.org/?probe=4251ab2f9a) | Feb 01, 2023 |
| Lenovo        | Legion 7 16ARHA7 82UH       | Notebook    | [bcaa2e6b1a](https://linux-hardware.org/?probe=bcaa2e6b1a) | Jan 30, 2023 |
| Dell          | Latitude 5400               | Notebook    | [80651273e4](https://linux-hardware.org/?probe=80651273e4) | Jan 29, 2023 |
| Dell          | Latitude 5400               | Notebook    | [eb97e73f08](https://linux-hardware.org/?probe=eb97e73f08) | Jan 29, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [096eede9c5](https://linux-hardware.org/?probe=096eede9c5) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [3e957e185d](https://linux-hardware.org/?probe=3e957e185d) | Jan 28, 2023 |
| HP            | ZBook 15 G4                 | Notebook    | [849d901314](https://linux-hardware.org/?probe=849d901314) | Jan 28, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [b15899ef80](https://linux-hardware.org/?probe=b15899ef80) | Jan 27, 2023 |
| Toshiba       | Satellite L755              | Notebook    | [357a0cd22d](https://linux-hardware.org/?probe=357a0cd22d) | Jan 27, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [8fa82c8684](https://linux-hardware.org/?probe=8fa82c8684) | Jan 26, 2023 |
| Dell          | Latitude E5410              | Notebook    | [22df8731a9](https://linux-hardware.org/?probe=22df8731a9) | Jan 26, 2023 |
| Google        | Magpie                      | Notebook    | [34506f260e](https://linux-hardware.org/?probe=34506f260e) | Jan 26, 2023 |
| HP            | 86EE                        | All in one  | [2632541785](https://linux-hardware.org/?probe=2632541785) | Jan 25, 2023 |
| MSI           | MPG X570S CARBON MAX WIF... | Desktop     | [55b2bf8aea](https://linux-hardware.org/?probe=55b2bf8aea) | Jan 25, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [cb29f724a0](https://linux-hardware.org/?probe=cb29f724a0) | Jan 24, 2023 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [ec369b35a4](https://linux-hardware.org/?probe=ec369b35a4) | Jan 24, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [56a9b7ad32](https://linux-hardware.org/?probe=56a9b7ad32) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [be73748546](https://linux-hardware.org/?probe=be73748546) | Jan 24, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [7595deef91](https://linux-hardware.org/?probe=7595deef91) | Jan 24, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [f371c1c8b6](https://linux-hardware.org/?probe=f371c1c8b6) | Jan 23, 2023 |
| Gigabyte      | X570 AORUS PRO WIFI         | Notebook    | [76955052a7](https://linux-hardware.org/?probe=76955052a7) | Jan 22, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1153793fd9](https://linux-hardware.org/?probe=1153793fd9) | Jan 22, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [10796ad8f6](https://linux-hardware.org/?probe=10796ad8f6) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [241b637096](https://linux-hardware.org/?probe=241b637096) | Jan 21, 2023 |
| Positivo      | S14BW01                     | Notebook    | [c818b70b5b](https://linux-hardware.org/?probe=c818b70b5b) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [bbc2c32eee](https://linux-hardware.org/?probe=bbc2c32eee) | Jan 19, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [8a13d31503](https://linux-hardware.org/?probe=8a13d31503) | Jan 19, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [2c44f8275e](https://linux-hardware.org/?probe=2c44f8275e) | Jan 17, 2023 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [25cbbcfc98](https://linux-hardware.org/?probe=25cbbcfc98) | Jan 16, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [3967a4560b](https://linux-hardware.org/?probe=3967a4560b) | Jan 15, 2023 |
| Unknown       | Unknown                     | Desktop     | [2e40c15660](https://linux-hardware.org/?probe=2e40c15660) | Jan 15, 2023 |
| Razer         | Blade 15 (2022) - RZ09-0... | Notebook    | [8b1ccef51d](https://linux-hardware.org/?probe=8b1ccef51d) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [154dafff1e](https://linux-hardware.org/?probe=154dafff1e) | Jan 15, 2023 |
| Gigabyte      | B650I AORUS ULTRA           | Desktop     | [ce588e0413](https://linux-hardware.org/?probe=ce588e0413) | Jan 14, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [1681bdc38e](https://linux-hardware.org/?probe=1681bdc38e) | Jan 14, 2023 |
| Dell          | Precision M4800             | Notebook    | [c5deb205c7](https://linux-hardware.org/?probe=c5deb205c7) | Jan 14, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [425fb5340d](https://linux-hardware.org/?probe=425fb5340d) | Jan 13, 2023 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [4fc1f3aff0](https://linux-hardware.org/?probe=4fc1f3aff0) | Jan 11, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [878c92decc](https://linux-hardware.org/?probe=878c92decc) | Jan 11, 2023 |
| HP            | 18E4                        | Desktop     | [600d82b264](https://linux-hardware.org/?probe=600d82b264) | Jan 11, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [c82f19c656](https://linux-hardware.org/?probe=c82f19c656) | Jan 10, 2023 |
| HP            | 18E4                        | Desktop     | [3386d53667](https://linux-hardware.org/?probe=3386d53667) | Jan 10, 2023 |
| HP            | 2179                        | Desktop     | [ad75cc2104](https://linux-hardware.org/?probe=ad75cc2104) | Jan 10, 2023 |
| Dell          | 0NRKPK A01                  | Desktop     | [f5bdf45b4a](https://linux-hardware.org/?probe=f5bdf45b4a) | Jan 08, 2023 |
| Dell          | 0J584C A00                  | Desktop     | [c18913a39e](https://linux-hardware.org/?probe=c18913a39e) | Jan 07, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [28ed8a48bd](https://linux-hardware.org/?probe=28ed8a48bd) | Jan 06, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4947d17a2b](https://linux-hardware.org/?probe=4947d17a2b) | Jan 06, 2023 |
| ASRock        | AB350 Pro4                  | Desktop     | [b2dfc2437e](https://linux-hardware.org/?probe=b2dfc2437e) | Jan 06, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [81431f1578](https://linux-hardware.org/?probe=81431f1578) | Jan 06, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [cef6a9db45](https://linux-hardware.org/?probe=cef6a9db45) | Jan 05, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [8defa5d641](https://linux-hardware.org/?probe=8defa5d641) | Jan 05, 2023 |
| Dell          | XPS 9320                    | Notebook    | [8684c6d86b](https://linux-hardware.org/?probe=8684c6d86b) | Jan 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0c84118baf](https://linux-hardware.org/?probe=0c84118baf) | Jan 03, 2023 |
| HP            | Pavilion Aero Laptop 13-... | Notebook    | [be6730b67b](https://linux-hardware.org/?probe=be6730b67b) | Jan 03, 2023 |
| ASRock        | B450M Pro4                  | Desktop     | [2d0530b779](https://linux-hardware.org/?probe=2d0530b779) | Jan 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [bc57a904f7](https://linux-hardware.org/?probe=bc57a904f7) | Jan 03, 2023 |
| MSI           | B250M PRO-VD                | Desktop     | [d94e8b5637](https://linux-hardware.org/?probe=d94e8b5637) | Jan 02, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [1be42c9032](https://linux-hardware.org/?probe=1be42c9032) | Jan 02, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [b613cd1179](https://linux-hardware.org/?probe=b613cd1179) | Jan 02, 2023 |
| Intel         | DH61DL AAG14066-205         | Desktop     | [8f923bc065](https://linux-hardware.org/?probe=8f923bc065) | Jan 01, 2023 |
| Toshiba       | EQUIUM A100                 | Notebook    | [424904034a](https://linux-hardware.org/?probe=424904034a) | Jan 01, 2023 |
| Gigabyte      | P55A-UD3                    | Desktop     | [6def847114](https://linux-hardware.org/?probe=6def847114) | Jan 01, 2023 |
| HP            | 18E4                        | Desktop     | [c83c8341e3](https://linux-hardware.org/?probe=c83c8341e3) | Jan 01, 2023 |
| MSI           | MPG B560I GAMING EDGE WI... | Desktop     | [20eb2d93e2](https://linux-hardware.org/?probe=20eb2d93e2) | Jan 01, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e0cb4d278d](https://linux-hardware.org/?probe=e0cb4d278d) | Dec 31, 2022 |
| HP            | 18E4                        | Desktop     | [1b1eccbbe1](https://linux-hardware.org/?probe=1b1eccbbe1) | Dec 31, 2022 |
| Gigabyte      | H310M S2 x.x                | Desktop     | [9aba0ac647](https://linux-hardware.org/?probe=9aba0ac647) | Dec 30, 2022 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [30e1303337](https://linux-hardware.org/?probe=30e1303337) | Dec 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4d915292f4](https://linux-hardware.org/?probe=4d915292f4) | Dec 30, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [b38e3cc51e](https://linux-hardware.org/?probe=b38e3cc51e) | Dec 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [ce45aaceaf](https://linux-hardware.org/?probe=ce45aaceaf) | Dec 29, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [bb1b612416](https://linux-hardware.org/?probe=bb1b612416) | Dec 29, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [adb13e2649](https://linux-hardware.org/?probe=adb13e2649) | Dec 29, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [e422b934d0](https://linux-hardware.org/?probe=e422b934d0) | Dec 29, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [b8099c7a94](https://linux-hardware.org/?probe=b8099c7a94) | Dec 28, 2022 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [0f15c0b801](https://linux-hardware.org/?probe=0f15c0b801) | Dec 28, 2022 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [475b76e98a](https://linux-hardware.org/?probe=475b76e98a) | Dec 28, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [cd90f1782c](https://linux-hardware.org/?probe=cd90f1782c) | Dec 26, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [098390e03e](https://linux-hardware.org/?probe=098390e03e) | Dec 25, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | Desktop     | [78418bfaa6](https://linux-hardware.org/?probe=78418bfaa6) | Dec 25, 2022 |
| Lenovo        | ThinkPad X230 2324KP1       | Notebook    | [628adc89bf](https://linux-hardware.org/?probe=628adc89bf) | Dec 24, 2022 |
| Apple         | Mac-F2218FC8                | All in one  | [416b0bb4e1](https://linux-hardware.org/?probe=416b0bb4e1) | Dec 24, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [244ad65a78](https://linux-hardware.org/?probe=244ad65a78) | Dec 24, 2022 |
| HP            | ProBook 450 G7              | Notebook    | [f47d3ce638](https://linux-hardware.org/?probe=f47d3ce638) | Dec 24, 2022 |
| ASUSTek       | M5A78L/USB3                 | Desktop     | [348c431775](https://linux-hardware.org/?probe=348c431775) | Dec 23, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [262a879a99](https://linux-hardware.org/?probe=262a879a99) | Dec 19, 2022 |
| Sony          | VGN-FW11E                   | Notebook    | [2d57afaa38](https://linux-hardware.org/?probe=2d57afaa38) | Dec 19, 2022 |
| HP            | 15                          | Notebook    | [cce5eb4078](https://linux-hardware.org/?probe=cce5eb4078) | Dec 19, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [54e81a596c](https://linux-hardware.org/?probe=54e81a596c) | Dec 18, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [0a486ca67b](https://linux-hardware.org/?probe=0a486ca67b) | Dec 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [c5adff1ad5](https://linux-hardware.org/?probe=c5adff1ad5) | Dec 17, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [8c87fc340b](https://linux-hardware.org/?probe=8c87fc340b) | Dec 16, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [e69127d249](https://linux-hardware.org/?probe=e69127d249) | Dec 15, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57ecebdc0f](https://linux-hardware.org/?probe=57ecebdc0f) | Dec 15, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8968e6816e](https://linux-hardware.org/?probe=8968e6816e) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [26757adc9d](https://linux-hardware.org/?probe=26757adc9d) | Dec 15, 2022 |
| HP            | 18E4                        | Desktop     | [ba6bef79d5](https://linux-hardware.org/?probe=ba6bef79d5) | Dec 15, 2022 |
| Lenovo        | Yoga 510-15IKB 80VC         | Convertible | [cb1e09289e](https://linux-hardware.org/?probe=cb1e09289e) | Dec 15, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [de70f43070](https://linux-hardware.org/?probe=de70f43070) | Dec 14, 2022 |
| HP            | 18E4                        | Desktop     | [00f1e4a14a](https://linux-hardware.org/?probe=00f1e4a14a) | Dec 14, 2022 |
| PC Special... | Elimina Iv 17               | Notebook    | [66a5d6dd6a](https://linux-hardware.org/?probe=66a5d6dd6a) | Dec 13, 2022 |
| Lenovo        | Yoga C740-14IML 81TC        | Convertible | [502792fe8a](https://linux-hardware.org/?probe=502792fe8a) | Dec 12, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [65c6c18ffe](https://linux-hardware.org/?probe=65c6c18ffe) | Dec 12, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [97691e3dca](https://linux-hardware.org/?probe=97691e3dca) | Dec 11, 2022 |
| Lenovo        | ThinkPad T480 20L5000UUS    | Notebook    | [2a1d9a153b](https://linux-hardware.org/?probe=2a1d9a153b) | Dec 11, 2022 |
| MSI           | MAG B660M BAZOOKA DDR4      | Desktop     | [280f28a486](https://linux-hardware.org/?probe=280f28a486) | Dec 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [48ccfd51b4](https://linux-hardware.org/?probe=48ccfd51b4) | Dec 11, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [6ae6d710b7](https://linux-hardware.org/?probe=6ae6d710b7) | Dec 10, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [b56f450d6d](https://linux-hardware.org/?probe=b56f450d6d) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [5f3e259429](https://linux-hardware.org/?probe=5f3e259429) | Dec 10, 2022 |
| HP            | 18E4                        | Desktop     | [418a689ae5](https://linux-hardware.org/?probe=418a689ae5) | Dec 10, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [de42f36422](https://linux-hardware.org/?probe=de42f36422) | Dec 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [963477cf57](https://linux-hardware.org/?probe=963477cf57) | Dec 07, 2022 |
| MSI           | B450M-A PRO MAX             | Desktop     | [46a6e9e722](https://linux-hardware.org/?probe=46a6e9e722) | Dec 07, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | Notebook    | [ebf5cc9d6e](https://linux-hardware.org/?probe=ebf5cc9d6e) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [e897549786](https://linux-hardware.org/?probe=e897549786) | Dec 06, 2022 |
| HP            | 18E4                        | Desktop     | [b12969b62f](https://linux-hardware.org/?probe=b12969b62f) | Dec 06, 2022 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [a4bdd8b19d](https://linux-hardware.org/?probe=a4bdd8b19d) | Dec 05, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [dcd57e5862](https://linux-hardware.org/?probe=dcd57e5862) | Dec 04, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [8741c9175e](https://linux-hardware.org/?probe=8741c9175e) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [c3b6dada9d](https://linux-hardware.org/?probe=c3b6dada9d) | Dec 02, 2022 |
| MSI           | GS75 Stealth 8SG            | Notebook    | [70be467762](https://linux-hardware.org/?probe=70be467762) | Dec 01, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [eff3d877bc](https://linux-hardware.org/?probe=eff3d877bc) | Nov 30, 2022 |
| MSI           | MEG Z490 UNIFY              | Desktop     | [b6af703e1a](https://linux-hardware.org/?probe=b6af703e1a) | Nov 28, 2022 |
| HP            | ENVY 17                     | Notebook    | [4a784f4642](https://linux-hardware.org/?probe=4a784f4642) | Nov 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [3ce1a2c42a](https://linux-hardware.org/?probe=3ce1a2c42a) | Nov 27, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [4e7809f7f6](https://linux-hardware.org/?probe=4e7809f7f6) | Nov 27, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [1deadcff69](https://linux-hardware.org/?probe=1deadcff69) | Nov 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d5d04cf0f9](https://linux-hardware.org/?probe=d5d04cf0f9) | Nov 26, 2022 |
| HP            | 18E4                        | Desktop     | [d72a174606](https://linux-hardware.org/?probe=d72a174606) | Nov 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [f76927c5ef](https://linux-hardware.org/?probe=f76927c5ef) | Nov 26, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [63521d3e8d](https://linux-hardware.org/?probe=63521d3e8d) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [5b19381bf6](https://linux-hardware.org/?probe=5b19381bf6) | Nov 26, 2022 |
| Dell          | 01Y1CJ A00                  | Mini pc     | [1878ce00d7](https://linux-hardware.org/?probe=1878ce00d7) | Nov 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [123efdf4df](https://linux-hardware.org/?probe=123efdf4df) | Nov 26, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [f05943013c](https://linux-hardware.org/?probe=f05943013c) | Nov 25, 2022 |
| Lenovo        | ThinkPad T440s 20ARA12UM... | Notebook    | [5e1b88160e](https://linux-hardware.org/?probe=5e1b88160e) | Nov 25, 2022 |
| HP            | 18E4                        | Desktop     | [4a4ac150b6](https://linux-hardware.org/?probe=4a4ac150b6) | Nov 24, 2022 |
| ASRock        | X570M Pro4                  | Desktop     | [2b2778b81a](https://linux-hardware.org/?probe=2b2778b81a) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [0200afcfb3](https://linux-hardware.org/?probe=0200afcfb3) | Nov 24, 2022 |
| Acer          | TravelMate 5730             | Notebook    | [077cd77583](https://linux-hardware.org/?probe=077cd77583) | Nov 24, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1986287453](https://linux-hardware.org/?probe=1986287453) | Nov 24, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [18b7141401](https://linux-hardware.org/?probe=18b7141401) | Nov 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [415fd12650](https://linux-hardware.org/?probe=415fd12650) | Nov 22, 2022 |
| ASUSTek       | PRIME B460M-A               | Desktop     | [4ed396ae3f](https://linux-hardware.org/?probe=4ed396ae3f) | Nov 21, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [aca01ed633](https://linux-hardware.org/?probe=aca01ed633) | Nov 21, 2022 |
| HP            | 15                          | Notebook    | [ab7c1e3bfd](https://linux-hardware.org/?probe=ab7c1e3bfd) | Nov 21, 2022 |
| HP            | 18E4                        | Desktop     | [ff954b29c9](https://linux-hardware.org/?probe=ff954b29c9) | Nov 21, 2022 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [8e7aa30e4e](https://linux-hardware.org/?probe=8e7aa30e4e) | Nov 19, 2022 |
| HP            | EliteBook 840 G2            | Notebook    | [6c896ef17e](https://linux-hardware.org/?probe=6c896ef17e) | Nov 19, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0b0d1f6427](https://linux-hardware.org/?probe=0b0d1f6427) | Nov 19, 2022 |
| MSI           | B360 GAMING PLUS            | Desktop     | [6552f5cfc9](https://linux-hardware.org/?probe=6552f5cfc9) | Nov 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [01810a4098](https://linux-hardware.org/?probe=01810a4098) | Nov 17, 2022 |
| HP            | 18E4                        | Desktop     | [37dd18c268](https://linux-hardware.org/?probe=37dd18c268) | Nov 17, 2022 |
| Apple         | MacBookPro16,2              | Notebook    | [8c63644200](https://linux-hardware.org/?probe=8c63644200) | Nov 14, 2022 |
| HP            | 3397                        | Desktop     | [035eb81bdf](https://linux-hardware.org/?probe=035eb81bdf) | Nov 13, 2022 |
| HP            | 18E4                        | Desktop     | [be545cc91f](https://linux-hardware.org/?probe=be545cc91f) | Nov 13, 2022 |
| ASUSTek       | B85M-GAMER                  | Desktop     | [112508759b](https://linux-hardware.org/?probe=112508759b) | Nov 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21ECS... | Notebook    | [7aeba8b69a](https://linux-hardware.org/?probe=7aeba8b69a) | Nov 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [cde0b24cde](https://linux-hardware.org/?probe=cde0b24cde) | Nov 10, 2022 |
| Lenovo        | ThinkPad X250 20CLS3AJ00    | Notebook    | [ec16a4b3c5](https://linux-hardware.org/?probe=ec16a4b3c5) | Nov 09, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [fba0c1a99c](https://linux-hardware.org/?probe=fba0c1a99c) | Nov 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [0527a7a983](https://linux-hardware.org/?probe=0527a7a983) | Nov 07, 2022 |
| Lenovo        | ThinkPad T520 42406AG       | Notebook    | [1038487513](https://linux-hardware.org/?probe=1038487513) | Nov 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [d137598aff](https://linux-hardware.org/?probe=d137598aff) | Nov 06, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [31cae1e989](https://linux-hardware.org/?probe=31cae1e989) | Nov 04, 2022 |
| Timi          | RedmiBook Pro 15            | Notebook    | [226d8de9bb](https://linux-hardware.org/?probe=226d8de9bb) | Nov 04, 2022 |
| HP            | 18E4                        | Desktop     | [66463ac87d](https://linux-hardware.org/?probe=66463ac87d) | Nov 04, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [08a8e0079a](https://linux-hardware.org/?probe=08a8e0079a) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [0235661dbe](https://linux-hardware.org/?probe=0235661dbe) | Nov 03, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA502IU    | Notebook    | [9e1b981f01](https://linux-hardware.org/?probe=9e1b981f01) | Nov 03, 2022 |
| HP            | 18E4                        | Desktop     | [1b1339be3d](https://linux-hardware.org/?probe=1b1339be3d) | Nov 02, 2022 |
| MSI           | Prestige 15 A11SCX          | Notebook    | [973b498b3f](https://linux-hardware.org/?probe=973b498b3f) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [cd300a0714](https://linux-hardware.org/?probe=cd300a0714) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | Notebook    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [45a2f4473b](https://linux-hardware.org/?probe=45a2f4473b) | Nov 01, 2022 |
| Apple         | MacBookPro16,1              | Notebook    | [025e3e7e4e](https://linux-hardware.org/?probe=025e3e7e4e) | Nov 01, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bd9909fff8](https://linux-hardware.org/?probe=bd9909fff8) | Oct 30, 2022 |
| HP            | 18E7                        | Desktop     | [d4a4ad62cb](https://linux-hardware.org/?probe=d4a4ad62cb) | Oct 29, 2022 |
| Acer          | Predator PO3-620            | Desktop     | [e737f3b4bd](https://linux-hardware.org/?probe=e737f3b4bd) | Oct 29, 2022 |
| MSI           | Prestige 14Evo A12M         | Notebook    | [5e32f7b38b](https://linux-hardware.org/?probe=5e32f7b38b) | Oct 28, 2022 |
| HP            | 18E4                        | Desktop     | [9d0444b1b8](https://linux-hardware.org/?probe=9d0444b1b8) | Oct 28, 2022 |
| ASRock        | Z270 Killer SLI/ac          | Desktop     | [22ec61d307](https://linux-hardware.org/?probe=22ec61d307) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [ed6d5efa84](https://linux-hardware.org/?probe=ed6d5efa84) | Oct 28, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [6263763f01](https://linux-hardware.org/?probe=6263763f01) | Oct 27, 2022 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [264d164669](https://linux-hardware.org/?probe=264d164669) | Oct 27, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [7be37b6a2d](https://linux-hardware.org/?probe=7be37b6a2d) | Oct 27, 2022 |
| HP            | Pavilion Laptop 14-ce0xx... | Notebook    | [7e1a95e569](https://linux-hardware.org/?probe=7e1a95e569) | Oct 26, 2022 |
| Acer          | Extensa 2540                | Notebook    | [367660309f](https://linux-hardware.org/?probe=367660309f) | Oct 26, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [3848afd2c8](https://linux-hardware.org/?probe=3848afd2c8) | Oct 26, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [cc0b502ddf](https://linux-hardware.org/?probe=cc0b502ddf) | Oct 25, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [be4e6c1903](https://linux-hardware.org/?probe=be4e6c1903) | Oct 25, 2022 |
| HP            | 650                         | Notebook    | [d7b73bebc7](https://linux-hardware.org/?probe=d7b73bebc7) | Oct 25, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [3ab5922ddf](https://linux-hardware.org/?probe=3ab5922ddf) | Oct 25, 2022 |
| MSI           | MAG Z490 TOMAHAWK           | Desktop     | [aa4a86445a](https://linux-hardware.org/?probe=aa4a86445a) | Oct 25, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [95707c7cd5](https://linux-hardware.org/?probe=95707c7cd5) | Oct 25, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [17a0e006d0](https://linux-hardware.org/?probe=17a0e006d0) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [c6966a0df9](https://linux-hardware.org/?probe=c6966a0df9) | Oct 25, 2022 |
| Gigabyte      | P35C-DS3R                   | Desktop     | [5b4ecfb7e9](https://linux-hardware.org/?probe=5b4ecfb7e9) | Oct 25, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [d9590e8d45](https://linux-hardware.org/?probe=d9590e8d45) | Oct 24, 2022 |
| Medion        | B460H6-EM                   | Desktop     | [9023ea833f](https://linux-hardware.org/?probe=9023ea833f) | Oct 24, 2022 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [f81e674faf](https://linux-hardware.org/?probe=f81e674faf) | Oct 21, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [0312fb4d88](https://linux-hardware.org/?probe=0312fb4d88) | Oct 21, 2022 |
| HP            | 18E4                        | Desktop     | [dfbdab6987](https://linux-hardware.org/?probe=dfbdab6987) | Oct 21, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503RM... | Notebook    | [d6275970a0](https://linux-hardware.org/?probe=d6275970a0) | Oct 21, 2022 |
| HP            | Laptop 15-bs2xx             | Notebook    | [0fd75382e9](https://linux-hardware.org/?probe=0fd75382e9) | Oct 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [facb462239](https://linux-hardware.org/?probe=facb462239) | Oct 20, 2022 |
| Gigabyte      | H87M-D3H                    | Desktop     | [bda1da1137](https://linux-hardware.org/?probe=bda1da1137) | Oct 20, 2022 |
| Lenovo        | 3111 SDK0J40697 WIN 3305... | Desktop     | [c8997eb831](https://linux-hardware.org/?probe=c8997eb831) | Oct 20, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [8105425af8](https://linux-hardware.org/?probe=8105425af8) | Oct 20, 2022 |
| MSI           | GE75 Raider 10SF            | Notebook    | [dd4102e2e7](https://linux-hardware.org/?probe=dd4102e2e7) | Oct 20, 2022 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [01338c4f3c](https://linux-hardware.org/?probe=01338c4f3c) | Oct 19, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [d7784759fb](https://linux-hardware.org/?probe=d7784759fb) | Oct 19, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [5e31cc470c](https://linux-hardware.org/?probe=5e31cc470c) | Oct 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [00fece9d77](https://linux-hardware.org/?probe=00fece9d77) | Oct 18, 2022 |
| ASUSTek       | X441SA                      | Notebook    | [31e3f95d58](https://linux-hardware.org/?probe=31e3f95d58) | Oct 18, 2022 |
| MSI           | Z390-A PRO                  | Desktop     | [d79e9be41b](https://linux-hardware.org/?probe=d79e9be41b) | Oct 18, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [0e827df91b](https://linux-hardware.org/?probe=0e827df91b) | Oct 18, 2022 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [09a4ac981b](https://linux-hardware.org/?probe=09a4ac981b) | Oct 17, 2022 |
| MSI           | B250M PRO-VD                | Desktop     | [28d9942c9f](https://linux-hardware.org/?probe=28d9942c9f) | Oct 17, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3a6855c328](https://linux-hardware.org/?probe=3a6855c328) | Oct 15, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bf1677e47c](https://linux-hardware.org/?probe=bf1677e47c) | Oct 14, 2022 |
| Google        | Liara                       | Notebook    | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| HP            | 340S G7 Notebook PC         | Notebook    | [1927ae6949](https://linux-hardware.org/?probe=1927ae6949) | Oct 12, 2022 |
| Lenovo        | V110-15AST 80TD             | Notebook    | [9d4b6fafb6](https://linux-hardware.org/?probe=9d4b6fafb6) | Oct 12, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| ASUSTek       | S550CA                      | Notebook    | [261f171b10](https://linux-hardware.org/?probe=261f171b10) | Oct 12, 2022 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [90661c40a3](https://linux-hardware.org/?probe=90661c40a3) | Oct 12, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [95daf6fc30](https://linux-hardware.org/?probe=95daf6fc30) | Oct 12, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [930887578f](https://linux-hardware.org/?probe=930887578f) | Oct 11, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [07870a3cde](https://linux-hardware.org/?probe=07870a3cde) | Oct 11, 2022 |
| HP            | 18E4                        | Desktop     | [6603067eba](https://linux-hardware.org/?probe=6603067eba) | Oct 10, 2022 |
| Acer          | Swift SF314-51              | Notebook    | [cfc56878f0](https://linux-hardware.org/?probe=cfc56878f0) | Oct 07, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [90c1d12ca3](https://linux-hardware.org/?probe=90c1d12ca3) | Oct 07, 2022 |
| Packard Be... | EasyNote TJ65               | Notebook    | [bb815f037b](https://linux-hardware.org/?probe=bb815f037b) | Oct 06, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [986a405690](https://linux-hardware.org/?probe=986a405690) | Oct 06, 2022 |
| HP            | 18E4                        | Desktop     | [53c6bf7af4](https://linux-hardware.org/?probe=53c6bf7af4) | Oct 06, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [1f77699521](https://linux-hardware.org/?probe=1f77699521) | Oct 03, 2022 |
| iRU           | v1.0                        | Mini pc     | [388d438bbc](https://linux-hardware.org/?probe=388d438bbc) | Oct 03, 2022 |
| HP            | 250 G4                      | Notebook    | [7c892fab7a](https://linux-hardware.org/?probe=7c892fab7a) | Oct 03, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [1a2e047ca1](https://linux-hardware.org/?probe=1a2e047ca1) | Oct 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [75e1aeaff5](https://linux-hardware.org/?probe=75e1aeaff5) | Oct 02, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [348bc23246](https://linux-hardware.org/?probe=348bc23246) | Oct 01, 2022 |
| MSI           | GF65 Thin 9SD               | Notebook    | [a761de487d](https://linux-hardware.org/?probe=a761de487d) | Oct 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [176695aa20](https://linux-hardware.org/?probe=176695aa20) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [d547ed6f83](https://linux-hardware.org/?probe=d547ed6f83) | Sep 30, 2022 |
| Lenovo        | IdeaPad 310-15IKB 80TV      | Notebook    | [9781419cc1](https://linux-hardware.org/?probe=9781419cc1) | Sep 30, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [1570daf698](https://linux-hardware.org/?probe=1570daf698) | Sep 29, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [1914cf579b](https://linux-hardware.org/?probe=1914cf579b) | Sep 29, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [456ff5f9a7](https://linux-hardware.org/?probe=456ff5f9a7) | Sep 29, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [81ddb430e3](https://linux-hardware.org/?probe=81ddb430e3) | Sep 28, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [f9eecf6781](https://linux-hardware.org/?probe=f9eecf6781) | Sep 28, 2022 |
| HP            | Pavilion Laptop 15-eg2xx... | Notebook    | [658f9b891f](https://linux-hardware.org/?probe=658f9b891f) | Sep 27, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [c0d2617a28](https://linux-hardware.org/?probe=c0d2617a28) | Sep 27, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [2c69225287](https://linux-hardware.org/?probe=2c69225287) | Sep 27, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [28631c9681](https://linux-hardware.org/?probe=28631c9681) | Sep 27, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [479dfeae74](https://linux-hardware.org/?probe=479dfeae74) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [6e96f4620a](https://linux-hardware.org/?probe=6e96f4620a) | Sep 25, 2022 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [acb677ddeb](https://linux-hardware.org/?probe=acb677ddeb) | Sep 25, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [fe99b8a461](https://linux-hardware.org/?probe=fe99b8a461) | Sep 25, 2022 |
| Lenovo        | ThinkBook 14 G2 ITL Ub 2... | Notebook    | [2b3c66f0ee](https://linux-hardware.org/?probe=2b3c66f0ee) | Sep 24, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [164ad85233](https://linux-hardware.org/?probe=164ad85233) | Sep 23, 2022 |
| HP            | 250 G4                      | Notebook    | [5d4c56fe14](https://linux-hardware.org/?probe=5d4c56fe14) | Sep 23, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [8e7a7a914c](https://linux-hardware.org/?probe=8e7a7a914c) | Sep 23, 2022 |
| AZW           | SEi                         | Desktop     | [579b2be420](https://linux-hardware.org/?probe=579b2be420) | Sep 23, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | Notebook    | [031f4bb4f1](https://linux-hardware.org/?probe=031f4bb4f1) | Sep 23, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [d852d9e0dd](https://linux-hardware.org/?probe=d852d9e0dd) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [6f43da7fb4](https://linux-hardware.org/?probe=6f43da7fb4) | Sep 22, 2022 |
| ASUSTek       | GL553VD                     | Notebook    | [e6cb381fd2](https://linux-hardware.org/?probe=e6cb381fd2) | Sep 21, 2022 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [d0f94bde46](https://linux-hardware.org/?probe=d0f94bde46) | Sep 21, 2022 |
| Lenovo        | ThinkPad Yoga 370 20JJS1... | Convertible | [7ae4855566](https://linux-hardware.org/?probe=7ae4855566) | Sep 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [f4f33e2362](https://linux-hardware.org/?probe=f4f33e2362) | Sep 20, 2022 |
| ASUSTek       | G74Sx                       | Notebook    | [e8f0a018c9](https://linux-hardware.org/?probe=e8f0a018c9) | Sep 19, 2022 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [579f73fc88](https://linux-hardware.org/?probe=579f73fc88) | Sep 19, 2022 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [543fad9f1c](https://linux-hardware.org/?probe=543fad9f1c) | Sep 18, 2022 |
| Acer          | Aspire A515-41G             | Notebook    | [434b1869d7](https://linux-hardware.org/?probe=434b1869d7) | Sep 16, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4f1e683ced](https://linux-hardware.org/?probe=4f1e683ced) | Sep 16, 2022 |
| HP            | 1998                        | Desktop     | [f3ef7a85fe](https://linux-hardware.org/?probe=f3ef7a85fe) | Sep 16, 2022 |
| MSI           | Summit E13FlipEvo A12MT     | Notebook    | [465e8d2c86](https://linux-hardware.org/?probe=465e8d2c86) | Sep 15, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [13cd2039a1](https://linux-hardware.org/?probe=13cd2039a1) | Sep 15, 2022 |
| Lenovo        | ThinkPad T480 20L6S58700    | Notebook    | [9d9d51e924](https://linux-hardware.org/?probe=9d9d51e924) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | Notebook    | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [98ae2af06f](https://linux-hardware.org/?probe=98ae2af06f) | Sep 14, 2022 |
| MSI           | Z170A KRAIT GAMING 3X       | Desktop     | [bfcf5bab5f](https://linux-hardware.org/?probe=bfcf5bab5f) | Sep 12, 2022 |
| Gigabyte      | AORUS 15G XC                | Notebook    | [4b0e97e947](https://linux-hardware.org/?probe=4b0e97e947) | Sep 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [fcf2ccb1d2](https://linux-hardware.org/?probe=fcf2ccb1d2) | Sep 12, 2022 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [cf9447ce8c](https://linux-hardware.org/?probe=cf9447ce8c) | Sep 10, 2022 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [20ead11e02](https://linux-hardware.org/?probe=20ead11e02) | Sep 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [39c0297cb1](https://linux-hardware.org/?probe=39c0297cb1) | Sep 10, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [82058771f7](https://linux-hardware.org/?probe=82058771f7) | Sep 09, 2022 |
| Timi          | TM1703                      | Notebook    | [5c30ece6ff](https://linux-hardware.org/?probe=5c30ece6ff) | Sep 08, 2022 |
| HP            | ProBook 450 G0              | Notebook    | [07dfc865cf](https://linux-hardware.org/?probe=07dfc865cf) | Sep 08, 2022 |
| ASUSTek       | H170M-PLUS                  | Desktop     | [df80ca89ee](https://linux-hardware.org/?probe=df80ca89ee) | Sep 08, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9690933a68](https://linux-hardware.org/?probe=9690933a68) | Sep 08, 2022 |
| Acer          | Aspire A315-22              | Notebook    | [49d54ac5c5](https://linux-hardware.org/?probe=49d54ac5c5) | Sep 07, 2022 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [cc40453955](https://linux-hardware.org/?probe=cc40453955) | Sep 06, 2022 |
| Timi          | TM1703                      | Notebook    | [fb7386017f](https://linux-hardware.org/?probe=fb7386017f) | Sep 06, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [dd3b771e55](https://linux-hardware.org/?probe=dd3b771e55) | Sep 05, 2022 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [e8887916fa](https://linux-hardware.org/?probe=e8887916fa) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [a75fed8b3f](https://linux-hardware.org/?probe=a75fed8b3f) | Sep 05, 2022 |
| Dell          | Vostro 7620                 | Notebook    | [cd613ebcd2](https://linux-hardware.org/?probe=cd613ebcd2) | Sep 05, 2022 |
| ASUSTek       | Zenbook UX5400EA_UX5400E... | Notebook    | [6ce8accfb1](https://linux-hardware.org/?probe=6ce8accfb1) | Sep 04, 2022 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [0e4f12b377](https://linux-hardware.org/?probe=0e4f12b377) | Sep 04, 2022 |
| Lenovo        | ThinkPad X200T 7449G6G      | Notebook    | [2667cd1609](https://linux-hardware.org/?probe=2667cd1609) | Sep 03, 2022 |
| Dell          | 0HMF7C A01                  | Desktop     | [292123f83b](https://linux-hardware.org/?probe=292123f83b) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [05221c6c18](https://linux-hardware.org/?probe=05221c6c18) | Sep 03, 2022 |
| ASUSTek       | PRIME H310M-K               | Desktop     | [2fb52eb1a8](https://linux-hardware.org/?probe=2fb52eb1a8) | Sep 03, 2022 |
| ASUSTek       | X580VN                      | Notebook    | [fe8f1a7e6f](https://linux-hardware.org/?probe=fe8f1a7e6f) | Sep 03, 2022 |
| HP            | OMEN by Laptop 16z-c000     | Notebook    | [edc4a4ce85](https://linux-hardware.org/?probe=edc4a4ce85) | Sep 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [4a7d6a9276](https://linux-hardware.org/?probe=4a7d6a9276) | Sep 01, 2022 |
| Schenker      | XMG FUSION 15 (XFU15M22)    | Notebook    | [3a8cfc8781](https://linux-hardware.org/?probe=3a8cfc8781) | Sep 01, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [297cab0eb2](https://linux-hardware.org/?probe=297cab0eb2) | Sep 01, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [18822e9fbe](https://linux-hardware.org/?probe=18822e9fbe) | Sep 01, 2022 |
| HP            | 18E7                        | Desktop     | [9344f12eea](https://linux-hardware.org/?probe=9344f12eea) | Aug 31, 2022 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [94b00f5da5](https://linux-hardware.org/?probe=94b00f5da5) | Aug 27, 2022 |
| Google        | Peppy                       | Notebook    | [be4ecba4dc](https://linux-hardware.org/?probe=be4ecba4dc) | Aug 26, 2022 |
| Google        | Auron_Yuna                  | Notebook    | [de2984c01a](https://linux-hardware.org/?probe=de2984c01a) | Aug 26, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [005afabbff](https://linux-hardware.org/?probe=005afabbff) | Aug 25, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [788397e7ae](https://linux-hardware.org/?probe=788397e7ae) | Aug 22, 2022 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [782466213a](https://linux-hardware.org/?probe=782466213a) | Aug 19, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [9b5ba9f755](https://linux-hardware.org/?probe=9b5ba9f755) | Aug 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [eec78b1552](https://linux-hardware.org/?probe=eec78b1552) | Aug 17, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UFS... | Notebook    | [6eadd1ec75](https://linux-hardware.org/?probe=6eadd1ec75) | Aug 17, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [b74ab22c1f](https://linux-hardware.org/?probe=b74ab22c1f) | Aug 16, 2022 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [fb77adfb99](https://linux-hardware.org/?probe=fb77adfb99) | Aug 16, 2022 |
| MSI           | A320M PRO-E                 | Desktop     | [2aa966d8af](https://linux-hardware.org/?probe=2aa966d8af) | Aug 14, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [94fb37c745](https://linux-hardware.org/?probe=94fb37c745) | Aug 14, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [94579c3a70](https://linux-hardware.org/?probe=94579c3a70) | Aug 13, 2022 |
| Lenovo        | IdeaPad S540-15IWL GTX 8... | Notebook    | [b391d570ba](https://linux-hardware.org/?probe=b391d570ba) | Aug 12, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [9e297d5dde](https://linux-hardware.org/?probe=9e297d5dde) | Aug 11, 2022 |
| ASUSTek       | GL502VT                     | Notebook    | [5e95e514a4](https://linux-hardware.org/?probe=5e95e514a4) | Aug 11, 2022 |
| HP            | Elite x2 1012 G1            | Notebook    | [a76e460266](https://linux-hardware.org/?probe=a76e460266) | Aug 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [d76760ffa4](https://linux-hardware.org/?probe=d76760ffa4) | Aug 11, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c257fb6e7](https://linux-hardware.org/?probe=9c257fb6e7) | Aug 10, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9c5e5976db](https://linux-hardware.org/?probe=9c5e5976db) | Aug 08, 2022 |
| Dell          | Inspiron 16 7620 2-in-1     | Convertible | [ddbb081e21](https://linux-hardware.org/?probe=ddbb081e21) | Aug 08, 2022 |
| AZW           | U59                         | Desktop     | [33aea75ff4](https://linux-hardware.org/?probe=33aea75ff4) | Aug 07, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [3ef9c93317](https://linux-hardware.org/?probe=3ef9c93317) | Aug 06, 2022 |
| Dell          | 0JYH5J A00                  | All in one  | [7940378ce2](https://linux-hardware.org/?probe=7940378ce2) | Aug 06, 2022 |
| Dell          | Inspiron 5402               | Notebook    | [5373247b06](https://linux-hardware.org/?probe=5373247b06) | Aug 05, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [d1079f3fba](https://linux-hardware.org/?probe=d1079f3fba) | Aug 04, 2022 |
| Positivo      | S14BW01                     | Notebook    | [28c70dfa85](https://linux-hardware.org/?probe=28c70dfa85) | Aug 04, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [ec13dcb17f](https://linux-hardware.org/?probe=ec13dcb17f) | Aug 01, 2022 |
| HP            | EliteBook 745 G6            | Notebook    | [0bcc9863e3](https://linux-hardware.org/?probe=0bcc9863e3) | Jul 31, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [7a5337e18d](https://linux-hardware.org/?probe=7a5337e18d) | Jul 28, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [b6dea628df](https://linux-hardware.org/?probe=b6dea628df) | Jul 27, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [60b06048f3](https://linux-hardware.org/?probe=60b06048f3) | Jul 24, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [06dd902359](https://linux-hardware.org/?probe=06dd902359) | Jul 23, 2022 |
| Lenovo        | ThinkBook 14p Gen 2 20YN    | Notebook    | [b41ce610a4](https://linux-hardware.org/?probe=b41ce610a4) | Jul 22, 2022 |
| MSI           | PRO Z690-A WIFI             | Desktop     | [00f490c5d0](https://linux-hardware.org/?probe=00f490c5d0) | Jul 22, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [b3f65d7c35](https://linux-hardware.org/?probe=b3f65d7c35) | Jul 21, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [dca2e009f0](https://linux-hardware.org/?probe=dca2e009f0) | Jul 20, 2022 |
| ASUSTek       | TUF Gaming B550-PRO         | Desktop     | [d7e2758b93](https://linux-hardware.org/?probe=d7e2758b93) | Jul 20, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [434edfc4cc](https://linux-hardware.org/?probe=434edfc4cc) | Jul 20, 2022 |
| Acer          | Nitro AN515-43              | Notebook    | [4e33f5e902](https://linux-hardware.org/?probe=4e33f5e902) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [d0d33ec330](https://linux-hardware.org/?probe=d0d33ec330) | Jul 19, 2022 |
| Samsung       | DeskTop System              | Desktop     | [3af9bcc9cb](https://linux-hardware.org/?probe=3af9bcc9cb) | Jul 19, 2022 |
| Microsoft     | Surface Pro 4               | Tablet      | [76b994344e](https://linux-hardware.org/?probe=76b994344e) | Jul 19, 2022 |
| ASUSTek       | TUF B450-PLUS GAMING        | Desktop     | [e8156cb24f](https://linux-hardware.org/?probe=e8156cb24f) | Jul 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [10be1cd329](https://linux-hardware.org/?probe=10be1cd329) | Jul 18, 2022 |
| Lenovo        | ThinkPad T460p 20FXS0550... | Notebook    | [1a394fdf59](https://linux-hardware.org/?probe=1a394fdf59) | Jul 18, 2022 |
| Lenovo        | ThinkPad E595 20NF001HGE    | Notebook    | [9d3a54dbcf](https://linux-hardware.org/?probe=9d3a54dbcf) | Jul 17, 2022 |
| Gigabyte      | B550 AORUS ELITE            | Desktop     | [85a02f5d41](https://linux-hardware.org/?probe=85a02f5d41) | Jul 15, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [e888c3e118](https://linux-hardware.org/?probe=e888c3e118) | Jul 08, 2022 |
| HP            | 158B                        | Desktop     | [1f3ebf7ecf](https://linux-hardware.org/?probe=1f3ebf7ecf) | Jul 07, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [df383e16e9](https://linux-hardware.org/?probe=df383e16e9) | Jul 07, 2022 |
| Gigabyte      | N3160TN                     | Desktop     | [b92830b100](https://linux-hardware.org/?probe=b92830b100) | Jul 03, 2022 |
| Gigabyte      | P55A-UD3                    | Desktop     | [36dcdacdb1](https://linux-hardware.org/?probe=36dcdacdb1) | Jul 01, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [5dd727cd5e](https://linux-hardware.org/?probe=5dd727cd5e) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [9aa0a38b17](https://linux-hardware.org/?probe=9aa0a38b17) | Jul 01, 2022 |
| HP            | Laptop 14-fq1xxx            | Notebook    | [b9b09609b8](https://linux-hardware.org/?probe=b9b09609b8) | Jul 01, 2022 |
| HUAWEI        | MACH-WX9                    | Notebook    | [329e3a150f](https://linux-hardware.org/?probe=329e3a150f) | Jun 30, 2022 |
| ASUSTek       | ROG Maximus Z690 HERO       | Desktop     | [73d9748926](https://linux-hardware.org/?probe=73d9748926) | Jun 29, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c84ca40dae](https://linux-hardware.org/?probe=c84ca40dae) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | Notebook    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [7528e47074](https://linux-hardware.org/?probe=7528e47074) | Jun 24, 2022 |
| Lenovo        | V330-14ARR 81B1             | Notebook    | [9816b1d616](https://linux-hardware.org/?probe=9816b1d616) | Jun 23, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [834bed6eda](https://linux-hardware.org/?probe=834bed6eda) | Jun 21, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b9a8ce148e](https://linux-hardware.org/?probe=b9a8ce148e) | Jun 21, 2022 |
| ASUSTek       | P8Z77-V                     | Desktop     | [16d7a07f8f](https://linux-hardware.org/?probe=16d7a07f8f) | Jun 20, 2022 |
| Dell          | 040DDP A01                  | Desktop     | [a4091a0526](https://linux-hardware.org/?probe=a4091a0526) | Jun 19, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [b0cc04798d](https://linux-hardware.org/?probe=b0cc04798d) | Jun 18, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [dc04d6eb1a](https://linux-hardware.org/?probe=dc04d6eb1a) | Jun 18, 2022 |
| ASUSTek       | N56VB                       | Notebook    | [a87c22baee](https://linux-hardware.org/?probe=a87c22baee) | Jun 16, 2022 |
| Microsoft     | Surface Go                  | Tablet      | [5c9a2e5312](https://linux-hardware.org/?probe=5c9a2e5312) | Jun 16, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [82a66444ec](https://linux-hardware.org/?probe=82a66444ec) | Jun 16, 2022 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [999d96890c](https://linux-hardware.org/?probe=999d96890c) | Jun 16, 2022 |
| Dell          | Latitude XT                 | Notebook    | [6ca0e5ca92](https://linux-hardware.org/?probe=6ca0e5ca92) | Jun 14, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [9275d3d785](https://linux-hardware.org/?probe=9275d3d785) | Jun 13, 2022 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [ab0ad88b31](https://linux-hardware.org/?probe=ab0ad88b31) | Jun 10, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [ed5235f3f4](https://linux-hardware.org/?probe=ed5235f3f4) | Jun 09, 2022 |
| Dell          | Latitude E6440              | Notebook    | [63238f8fe9](https://linux-hardware.org/?probe=63238f8fe9) | Jun 09, 2022 |
| Lenovo        | SKYBAY No DPK               | All in one  | [c27da0faa9](https://linux-hardware.org/?probe=c27da0faa9) | Jun 06, 2022 |
| Acer          | Aspire A515-43              | Notebook    | [343315ec17](https://linux-hardware.org/?probe=343315ec17) | Jun 06, 2022 |
| ASUSTek       | SABERTOOTH X99              | Desktop     | [5c7a9690cf](https://linux-hardware.org/?probe=5c7a9690cf) | Jun 05, 2022 |
| ASUSTek       | H110M-E/M.2                 | Desktop     | [cb5ea65a1d](https://linux-hardware.org/?probe=cb5ea65a1d) | Jun 04, 2022 |
| ASUSTek       | UX461UN                     | Convertible | [e75c214872](https://linux-hardware.org/?probe=e75c214872) | Jun 03, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [eaff4f6db6](https://linux-hardware.org/?probe=eaff4f6db6) | Jun 03, 2022 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [4a055cff40](https://linux-hardware.org/?probe=4a055cff40) | Jun 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [fb18d30478](https://linux-hardware.org/?probe=fb18d30478) | Jun 02, 2022 |
| ZOTAC         | ZBOX-ECM73070C/53060C       | Mini pc     | [e9721391d2](https://linux-hardware.org/?probe=e9721391d2) | Jun 01, 2022 |
| ASUSTek       | GL753VE                     | Notebook    | [a96aa73dd6](https://linux-hardware.org/?probe=a96aa73dd6) | Jun 01, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [394d112de5](https://linux-hardware.org/?probe=394d112de5) | May 31, 2022 |
| Dell          | Latitude 5289               | Notebook    | [f9e3e0fa57](https://linux-hardware.org/?probe=f9e3e0fa57) | May 30, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [462a42a8c9](https://linux-hardware.org/?probe=462a42a8c9) | May 28, 2022 |
| Gigabyte      | X470 AORUS GAMING 7 WIFI... | Desktop     | [8306cefd31](https://linux-hardware.org/?probe=8306cefd31) | May 28, 2022 |
| Gigabyte      | B550M AORUS PRO             | Desktop     | [0075e2d9df](https://linux-hardware.org/?probe=0075e2d9df) | May 28, 2022 |
| Dell          | 0K240Y A01                  | Desktop     | [4ef7645f2d](https://linux-hardware.org/?probe=4ef7645f2d) | May 28, 2022 |
| Lenovo        | Yoga C740-15IML 81TD        | Convertible | [d17aaf4cc5](https://linux-hardware.org/?probe=d17aaf4cc5) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| Lenovo        | IdeaPadFlex 5 81X2          | Convertible | [df65cb7a9e](https://linux-hardware.org/?probe=df65cb7a9e) | May 26, 2022 |
| Sony          | VPCCA17FX                   | Notebook    | [4ced9d5222](https://linux-hardware.org/?probe=4ced9d5222) | May 26, 2022 |
| Dell          | Latitude E6510              | Notebook    | [52b94e68a9](https://linux-hardware.org/?probe=52b94e68a9) | May 23, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [4495957eae](https://linux-hardware.org/?probe=4495957eae) | May 23, 2022 |
| HP            | 0A08h                       | Desktop     | [86c65b6b1f](https://linux-hardware.org/?probe=86c65b6b1f) | May 21, 2022 |
| HP            | 0A08h                       | Desktop     | [18b2ce1297](https://linux-hardware.org/?probe=18b2ce1297) | May 21, 2022 |
| Timi          | A35S                        | Notebook    | [8278281113](https://linux-hardware.org/?probe=8278281113) | May 20, 2022 |
| ASRock        | A320M/ac                    | Desktop     | [78ee9c8853](https://linux-hardware.org/?probe=78ee9c8853) | May 20, 2022 |
| HP            | 3647h                       | Desktop     | [eccb82bec8](https://linux-hardware.org/?probe=eccb82bec8) | May 20, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [0bc568827c](https://linux-hardware.org/?probe=0bc568827c) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [bc731dc190](https://linux-hardware.org/?probe=bc731dc190) | May 18, 2022 |
| Microsoft     | Surface Laptop Go           | Tablet      | [aa810f6e41](https://linux-hardware.org/?probe=aa810f6e41) | May 18, 2022 |
| HP            | Pavilion x360 Convertibl... | Convertible | [798bcbfce3](https://linux-hardware.org/?probe=798bcbfce3) | May 17, 2022 |
| Lenovo        | ThinkPad X270 20HMS12K00    | Notebook    | [c4e15012d5](https://linux-hardware.org/?probe=c4e15012d5) | May 15, 2022 |
| Dell          | Inspiron 3580               | Notebook    | [33dbac4352](https://linux-hardware.org/?probe=33dbac4352) | May 15, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [5dea5cd6ff](https://linux-hardware.org/?probe=5dea5cd6ff) | May 14, 2022 |
| HP            | Notebook                    | Notebook    | [e672632acf](https://linux-hardware.org/?probe=e672632acf) | May 13, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII IMPAC... | Desktop     | [a6a2ef59b0](https://linux-hardware.org/?probe=a6a2ef59b0) | May 11, 2022 |
| MSI           | B75MA-E33                   | Desktop     | [220e04a116](https://linux-hardware.org/?probe=220e04a116) | May 11, 2022 |
| Unknown       | Unknown                     | Notebook    | [fac14402be](https://linux-hardware.org/?probe=fac14402be) | May 11, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [34272a60d1](https://linux-hardware.org/?probe=34272a60d1) | May 10, 2022 |
| HP            | ProBook 440 G4              | Notebook    | [1f0811673a](https://linux-hardware.org/?probe=1f0811673a) | May 09, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [b5145fe094](https://linux-hardware.org/?probe=b5145fe094) | May 08, 2022 |
| Lenovo        | Yoga C930-13IKB 81C4        | Convertible | [3d921b618b](https://linux-hardware.org/?probe=3d921b618b) | May 07, 2022 |
| Lenovo        | V14 G2 ITL 82NM             | Notebook    | [6a3cbcae26](https://linux-hardware.org/?probe=6a3cbcae26) | May 06, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/EndeavourOS/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| EndeavourOS Rolling | 970       | 86.3%   |
| EndeavourOS         | 154       | 13.7%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| EndeavourOS | 1113      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version          | Computers | Percent |
|------------------|-----------|---------|
| 6.4.12-arch1-1   | 23        | 1.76%   |
| 6.2.8-arch1-1    | 20        | 1.53%   |
| 5.15.12-arch1-1  | 20        | 1.53%   |
| 6.1.1-arch1-1    | 16        | 1.23%   |
| 6.3.9-arch1-1    | 15        | 1.15%   |
| 6.3.1-arch1-1    | 13        | 1%      |
| 6.1.12-arch1-1   | 13        | 1%      |
| 6.5.3-arch1-1    | 12        | 0.92%   |
| 6.3.4-arch1-1    | 11        | 0.84%   |
| 6.2.2-arch1-1    | 11        | 0.84%   |
| 6.2.13-arch1-1   | 11        | 0.84%   |
| 6.2.10-arch1-1   | 11        | 0.84%   |
| 6.0.9-arch1-1    | 11        | 0.84%   |
| 6.0.2-arch1-1    | 11        | 0.84%   |
| 5.17.1-arch1-1   | 11        | 0.84%   |
| 6.4.11-arch2-1   | 10        | 0.77%   |
| 5.19.7-arch1-1   | 10        | 0.77%   |
| 5.17.5-arch1-1   | 10        | 0.77%   |
| 6.0.2-zen1-1-zen | 9         | 0.69%   |
| 6.0.12-arch1-1   | 9         | 0.69%   |
| 5.15.10-arch1-1  | 9         | 0.69%   |
| 6.4.7-arch1-1    | 8         | 0.61%   |
| 6.2.9-arch1-1    | 8         | 0.61%   |
| 5.17.9-arch1-1   | 8         | 0.61%   |
| 5.15.7-arch1-1   | 8         | 0.61%   |
| 5.14.9-arch2-1   | 8         | 0.61%   |
| 5.13.13-arch1-1  | 8         | 0.61%   |
| 5.11.11-arch1-1  | 8         | 0.61%   |
| 6.1.11-arch1-1   | 7         | 0.54%   |
| 5.9.14-arch1-1   | 7         | 0.54%   |
| 5.19.12-arch1-1  | 7         | 0.54%   |
| 5.18.16-arch1-1  | 7         | 0.54%   |
| 5.18.12-arch1-1  | 7         | 0.54%   |
| 5.16.10-arch1-1  | 7         | 0.54%   |
| 6.5.4-arch2-1    | 6         | 0.46%   |
| 6.4.3-arch1-2    | 6         | 0.46%   |
| 6.4.2-arch1-1    | 6         | 0.46%   |
| 6.4.10-arch1-1   | 6         | 0.46%   |
| 6.3.5-arch1-1    | 6         | 0.46%   |
| 6.2.12-arch1-1   | 6         | 0.46%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.4.12  | 29        | 2.22%   |
| 5.15.12 | 28        | 2.14%   |
| 6.3.1   | 23        | 1.76%   |
| 6.1.1   | 23        | 1.76%   |
| 6.2.8   | 22        | 1.68%   |
| 6.0.2   | 22        | 1.68%   |
| 6.4.11  | 16        | 1.23%   |
| 6.3.9   | 16        | 1.23%   |
| 6.5.3   | 15        | 1.15%   |
| 6.4.7   | 15        | 1.15%   |
| 6.4.3   | 15        | 1.15%   |
| 6.3.4   | 15        | 1.15%   |
| 6.1.12  | 15        | 1.15%   |
| 6.0.9   | 15        | 1.15%   |
| 5.17.1  | 15        | 1.15%   |
| 6.2.2   | 14        | 1.07%   |
| 6.2.13  | 14        | 1.07%   |
| 5.17.5  | 14        | 1.07%   |
| 6.2.10  | 13        | 1%      |
| 6.0.6   | 12        | 0.92%   |
| 6.0.12  | 12        | 0.92%   |
| 5.19.7  | 12        | 0.92%   |
| 5.13.13 | 12        | 0.92%   |
| 6.2.9   | 11        | 0.84%   |
| 5.18.12 | 11        | 0.84%   |
| 5.17.9  | 11        | 0.84%   |
| 6.4.1   | 10        | 0.77%   |
| 6.3.5   | 10        | 0.77%   |
| 5.19.9  | 10        | 0.77%   |
| 5.14.9  | 10        | 0.77%   |
| 6.4.10  | 9         | 0.69%   |
| 6.1.9   | 9         | 0.69%   |
| 5.19.13 | 9         | 0.69%   |
| 5.18.16 | 9         | 0.69%   |
| 5.15.7  | 9         | 0.69%   |
| 5.15.4  | 9         | 0.69%   |
| 5.15.10 | 9         | 0.69%   |
| 5.11.11 | 9         | 0.69%   |
| 6.5.4   | 8         | 0.61%   |
| 6.1.8   | 8         | 0.61%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 139       | 11.05%  |
| 6.1     | 130       | 10.33%  |
| 6.4     | 114       | 9.06%   |
| 6.2     | 105       | 8.35%   |
| 6.3     | 85        | 6.76%   |
| 6.0     | 83        | 6.6%    |
| 5.19    | 79        | 6.28%   |
| 5.16    | 66        | 5.25%   |
| 5.17    | 64        | 5.09%   |
| 5.18    | 60        | 4.77%   |
| 5.14    | 52        | 4.13%   |
| 5.12    | 38        | 3.02%   |
| 5.10    | 38        | 3.02%   |
| 5.11    | 37        | 2.94%   |
| 5.9     | 35        | 2.78%   |
| 5.13    | 35        | 2.78%   |
| 6.5     | 34        | 2.7%    |
| 5.8     | 24        | 1.91%   |
| 5.7     | 21        | 1.67%   |
| 5.4     | 7         | 0.56%   |
| 5.6     | 5         | 0.4%    |
| 5.5     | 2         | 0.16%   |
| 4.19    | 2         | 0.16%   |
| 5.2     | 1         | 0.08%   |
| 5.17.1  | 1         | 0.08%   |
| Unknown | 1         | 0.08%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1112      | 99.91%  |
| aarch64 | 1         | 0.09%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE5            | 444       | 38.38%  |
| GNOME           | 243       | 21%     |
| XFCE            | 215       | 18.58%  |
| i3              | 49        | 4.24%   |
| X-Cinnamon      | 44        | 3.8%    |
| KDE             | 26        | 2.25%   |
| Budgie          | 25        | 2.16%   |
| Unknown         | 23        | 1.99%   |
| Cinnamon        | 17        | 1.47%   |
| sway            | 14        | 1.21%   |
| MATE            | 11        | 0.95%   |
| LXQt            | 9         | 0.78%   |
| Hyprland        | 7         | 0.61%   |
| Deepin          | 5         | 0.43%   |
| bspwm           | 5         | 0.43%   |
| openbox         | 4         | 0.35%   |
| GNOME Flashback | 4         | 0.35%   |
| awesome         | 3         | 0.26%   |
| qtile           | 2         | 0.17%   |
| LXDE            | 2         | 0.17%   |
| xmonad          | 1         | 0.09%   |
| LeftWM          | 1         | 0.09%   |
| jwm             | 1         | 0.09%   |
| herbstluftwm    | 1         | 0.09%   |
| GNOME Classic   | 1         | 0.09%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 833       | 73.07%  |
| Wayland | 246       | 21.58%  |
| Tty     | 42        | 3.68%   |
| Unknown | 18        | 1.58%   |
| Web     | 1         | 0.09%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| LightDM | 374       | 32.55%  |
| SDDM    | 293       | 25.5%   |
| Unknown | 287       | 24.98%  |
| GDM     | 143       | 12.45%  |
| TDM     | 48        | 4.18%   |
| LY-DM   | 2         | 0.17%   |
| GREETD  | 2         | 0.17%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 562       | 50.18%  |
| en_GB   | 84        | 7.5%    |
| it_IT   | 67        | 5.98%   |
| de_DE   | 61        | 5.45%   |
| en_CA   | 47        | 4.2%    |
| ru_RU   | 29        | 2.59%   |
| en_IN   | 27        | 2.41%   |
| fr_FR   | 25        | 2.23%   |
| es_ES   | 18        | 1.61%   |
| en_AU   | 17        | 1.52%   |
| pl_PL   | 14        | 1.25%   |
| Unknown | 14        | 1.25%   |
| pt_BR   | 12        | 1.07%   |
| nl_NL   | 10        | 0.89%   |
| fi_FI   | 9         | 0.8%    |
| es_MX   | 9         | 0.8%    |
| de_AT   | 9         | 0.8%    |
| tr_TR   | 8         | 0.71%   |
| es_AR   | 8         | 0.71%   |
| en_DK   | 7         | 0.63%   |
| sv_SE   | 6         | 0.54%   |
| en_NZ   | 6         | 0.54%   |
| en_AG   | 6         | 0.54%   |
| pt_PT   | 5         | 0.45%   |
| nl_BE   | 5         | 0.45%   |
| en_PH   | 5         | 0.45%   |
| en_HK   | 4         | 0.36%   |
| de_CH   | 4         | 0.36%   |
| zh_CN   | 3         | 0.27%   |
| en_SG   | 3         | 0.27%   |
| cs_CZ   | 3         | 0.27%   |
| ru_UA   | 2         | 0.18%   |
| hu_HU   | 2         | 0.18%   |
| es_CO   | 2         | 0.18%   |
| en_ZA   | 2         | 0.18%   |
| en_IL   | 2         | 0.18%   |
| C       | 2         | 0.18%   |
| sr_RS   | 1         | 0.09%   |
| sl_SI   | 1         | 0.09%   |
| sk_SK   | 1         | 0.09%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 733       | 64.92%  |
| BIOS | 396       | 35.08%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 772       | 68.87%  |
| Btrfs   | 293       | 26.14%  |
| Overlay | 26        | 2.32%   |
| Xfs     | 12        | 1.07%   |
| Tmpfs   | 11        | 0.98%   |
| F2fs    | 3         | 0.27%   |
| Unknown | 2         | 0.18%   |
| XXX4    | 1         | 0.09%   |
| Ext2    | 1         | 0.09%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 761       | 67.52%  |
| Unknown | 287       | 25.47%  |
| MBR     | 79        | 7.01%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 960       | 85.33%  |
| Yes       | 165       | 14.67%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 763       | 67.17%  |
| Yes       | 373       | 32.83%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 218       | 19.59%  |
| Lenovo                               | 217       | 19.5%   |
| Hewlett-Packard                      | 140       | 12.58%  |
| MSI                                  | 102       | 9.16%   |
| Dell                                 | 99        | 8.89%   |
| Gigabyte Technology                  | 74        | 6.65%   |
| Acer                                 | 49        | 4.4%    |
| ASRock                               | 34        | 3.05%   |
| Apple                                | 29        | 2.61%   |
| HUAWEI                               | 14        | 1.26%   |
| Google                               | 12        | 1.08%   |
| Timi                                 | 11        | 0.99%   |
| Samsung Electronics                  | 11        | 0.99%   |
| Microsoft                            | 10        | 0.9%    |
| Toshiba                              | 8         | 0.72%   |
| Unknown                              | 8         | 0.72%   |
| Notebook                             | 7         | 0.63%   |
| Sony                                 | 5         | 0.45%   |
| Intel                                | 4         | 0.36%   |
| ZOTAC                                | 3         | 0.27%   |
| TUXEDO                               | 3         | 0.27%   |
| Schenker                             | 3         | 0.27%   |
| Positivo                             | 3         | 0.27%   |
| Packard Bell                         | 3         | 0.27%   |
| Fujitsu                              | 3         | 0.27%   |
| AZW                                  | 3         | 0.27%   |
| TrekStor                             | 2         | 0.18%   |
| Razer                                | 2         | 0.18%   |
| Huanan                               | 2         | 0.18%   |
| GPD                                  | 2         | 0.18%   |
| Chuwi                                | 2         | 0.18%   |
| Biostar                              | 2         | 0.18%   |
| BESSTAR Tech                         | 2         | 0.18%   |
| AMI                                  | 2         | 0.18%   |
| Alienware                            | 2         | 0.18%   |
| VIT                                  | 1         | 0.09%   |
| UMAX                                 | 1         | 0.09%   |
| Teclast                              | 1         | 0.09%   |
| Shinelon Computer                    | 1         | 0.09%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.09%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| MSI MS-7C37                           | 11        | 0.99%   |
| ASUS All Series                       | 9         | 0.81%   |
| Unknown                               | 9         | 0.81%   |
| ASUS TUF Gaming X570-PLUS             | 7         | 0.63%   |
| Apple MacBookAir7,2                   | 7         | 0.63%   |
| MSI MS-7C02                           | 5         | 0.45%   |
| MSI MS-7A38                           | 5         | 0.45%   |
| ASUS ROG STRIX X570-E GAMING          | 5         | 0.45%   |
| Microsoft Surface Laptop Go           | 4         | 0.36%   |
| Gigabyte B550 AORUS ELITE V2          | 4         | 0.36%   |
| Gigabyte B450 AORUS ELITE             | 4         | 0.36%   |
| ASUS ROG Zephyrus G14 GA401IV_GA401IV | 4         | 0.36%   |
| ASRock B450M Pro4                     | 4         | 0.36%   |
| ASRock B450 Pro4                      | 4         | 0.36%   |
| MSI MS-7C91                           | 3         | 0.27%   |
| MSI MS-7C56                           | 3         | 0.27%   |
| MSI MS-7C52                           | 3         | 0.27%   |
| MSI Modern 14 B5M                     | 3         | 0.27%   |
| Lenovo ThinkPad X140e 20BL000BUS      | 3         | 0.27%   |
| Lenovo ThinkBook 15 G2 ITL 20VE       | 3         | 0.27%   |
| Lenovo Legion 5 15ACH6H 82JU          | 3         | 0.27%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2   | 3         | 0.27%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5      | 3         | 0.27%   |
| Lenovo IdeaPad 3 15ITL6 82H8          | 3         | 0.27%   |
| HUAWEI KLVL-WXX9                      | 3         | 0.27%   |
| HP Pavilion Gaming Laptop 15-cx0xxx   | 3         | 0.27%   |
| HP Laptop 15-db0xxx                   | 3         | 0.27%   |
| Gigabyte B550M AORUS PRO              | 3         | 0.27%   |
| Gigabyte B450M DS3H                   | 3         | 0.27%   |
| Dell Inspiron 3542                    | 3         | 0.27%   |
| ASUS ROG STRIX B550-F GAMING          | 3         | 0.27%   |
| ASUS PRIME X570-P                     | 3         | 0.27%   |
| ASUS PRIME A320M-K                    | 3         | 0.27%   |
| Apple MacBookPro16,2                  | 3         | 0.27%   |
| Acer Aspire E5-575G                   | 3         | 0.27%   |
| Timi TM1701                           | 2         | 0.18%   |
| Timi A35S                             | 2         | 0.18%   |
| Samsung 950QDB                        | 2         | 0.18%   |
| Samsung 340XAA/350XAA/550XAA          | 2         | 0.18%   |
| Positivo S14BW01                      | 2         | 0.18%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 96        | 8.63%   |
| ASUS ROG           | 56        | 5.03%   |
| Lenovo IdeaPad     | 50        | 4.49%   |
| HP Pavilion        | 29        | 2.61%   |
| Acer Aspire        | 29        | 2.61%   |
| ASUS TUF           | 27        | 2.43%   |
| Dell Latitude      | 26        | 2.34%   |
| Dell Inspiron      | 25        | 2.25%   |
| ASUS PRIME         | 25        | 2.25%   |
| HP EliteBook       | 21        | 1.89%   |
| Lenovo Yoga        | 19        | 1.71%   |
| HP Laptop          | 16        | 1.44%   |
| ASUS VivoBook      | 16        | 1.44%   |
| Lenovo Legion      | 14        | 1.26%   |
| HP ENVY            | 12        | 1.08%   |
| Dell OptiPlex      | 12        | 1.08%   |
| MSI MS-7C37        | 11        | 0.99%   |
| Lenovo ThinkBook   | 11        | 0.99%   |
| Dell XPS           | 11        | 0.99%   |
| ASUS Zenbook       | 11        | 0.99%   |
| Microsoft Surface  | 10        | 0.9%    |
| Dell Precision     | 10        | 0.9%    |
| MSI Modern         | 9         | 0.81%   |
| ASUS ASUS          | 9         | 0.81%   |
| ASUS All           | 9         | 0.81%   |
| Unknown            | 9         | 0.81%   |
| Gigabyte B550      | 8         | 0.72%   |
| Gigabyte B450      | 7         | 0.63%   |
| Apple MacBookAir7  | 7         | 0.63%   |
| Acer Swift         | 7         | 0.63%   |
| Toshiba Satellite  | 6         | 0.54%   |
| HP 255             | 6         | 0.54%   |
| Gigabyte X570      | 6         | 0.54%   |
| ASRock B450        | 6         | 0.54%   |
| MSI MS-7C02        | 5         | 0.45%   |
| MSI MS-7A38        | 5         | 0.45%   |
| Lenovo ThinkCentre | 5         | 0.45%   |
| Lenovo IdeaPadFlex | 5         | 0.45%   |
| Gigabyte B450M     | 5         | 0.45%   |
| Dell Vostro        | 5         | 0.45%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 159       | 14.29%  |
| 2021    | 153       | 13.75%  |
| 2019    | 139       | 12.49%  |
| 2018    | 131       | 11.77%  |
| 2022    | 89        | 8%      |
| 2017    | 76        | 6.83%   |
| 2013    | 57        | 5.12%   |
| 2016    | 55        | 4.94%   |
| 2015    | 55        | 4.94%   |
| 2012    | 53        | 4.76%   |
| 2014    | 45        | 4.04%   |
| 2011    | 27        | 2.43%   |
| 2023    | 19        | 1.71%   |
| 2010    | 19        | 1.71%   |
| 2009    | 14        | 1.26%   |
| 2008    | 14        | 1.26%   |
| 2007    | 7         | 0.63%   |
| Unknown | 1         | 0.09%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 656       | 58.94%  |
| Desktop     | 361       | 32.43%  |
| Convertible | 52        | 4.67%   |
| All in one  | 17        | 1.53%   |
| Tablet      | 13        | 1.17%   |
| Mini pc     | 13        | 1.17%   |
| Server      | 1         | 0.09%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1107      | 99.37%  |
| Enabled  | 7         | 0.63%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1100      | 98.83%  |
| Yes  | 13        | 1.17%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 282       | 25.09%  |
| 8.01-16.0   | 253       | 22.51%  |
| 4.01-8.0    | 231       | 20.55%  |
| 32.01-64.0  | 190       | 16.9%   |
| 3.01-4.0    | 87        | 7.74%   |
| 24.01-32.0  | 40        | 3.56%   |
| 64.01-256.0 | 32        | 2.85%   |
| 1.01-2.0    | 6         | 0.53%   |
| 2.01-3.0    | 3         | 0.27%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 300       | 24.59%  |
| 2.01-3.0   | 293       | 24.02%  |
| 1.01-2.0   | 252       | 20.66%  |
| 3.01-4.0   | 235       | 19.26%  |
| 8.01-16.0  | 95        | 7.79%   |
| 0.51-1.0   | 28        | 2.3%    |
| 16.01-24.0 | 12        | 0.98%   |
| 24.01-32.0 | 3         | 0.25%   |
| 0.01-0.5   | 2         | 0.16%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 607       | 52.92%  |
| 2      | 305       | 26.59%  |
| 3      | 107       | 9.33%   |
| 4      | 71        | 6.19%   |
| 5      | 31        | 2.7%    |
| 6      | 15        | 1.31%   |
| 7      | 4         | 0.35%   |
| 0      | 3         | 0.26%   |
| 9      | 2         | 0.17%   |
| 8      | 2         | 0.17%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 911       | 81.48%  |
| Yes       | 207       | 18.52%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 894       | 79.96%  |
| No        | 224       | 20.04%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 941       | 84.17%  |
| No        | 177       | 15.83%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 891       | 79.34%  |
| No        | 232       | 20.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| USA         | 251       | 22.31%  |
| Germany     | 102       | 9.07%   |
| Italy       | 97        | 8.62%   |
| Canada      | 50        | 4.44%   |
| France      | 43        | 3.82%   |
| Russia      | 34        | 3.02%   |
| India       | 34        | 3.02%   |
| UK          | 33        | 2.93%   |
| Poland      | 32        | 2.84%   |
| Netherlands | 32        | 2.84%   |
| Spain       | 26        | 2.31%   |
| Brazil      | 26        | 2.31%   |
| Turkey      | 25        | 2.22%   |
| Finland     | 22        | 1.96%   |
| Australia   | 19        | 1.69%   |
| Austria     | 18        | 1.6%    |
| Sweden      | 17        | 1.51%   |
| Mexico      | 16        | 1.42%   |
| Belgium     | 16        | 1.42%   |
| Switzerland | 11        | 0.98%   |
| Indonesia   | 11        | 0.98%   |
| Argentina   | 10        | 0.89%   |
| Romania     | 9         | 0.8%    |
| Hungary     | 8         | 0.71%   |
| Vietnam     | 7         | 0.62%   |
| Portugal    | 7         | 0.62%   |
| New Zealand | 7         | 0.62%   |
| Hong Kong   | 7         | 0.62%   |
| Denmark     | 7         | 0.62%   |
| Czechia     | 7         | 0.62%   |
| Ukraine     | 6         | 0.53%   |
| Malaysia    | 6         | 0.53%   |
| Greece      | 6         | 0.53%   |
| Bangladesh  | 6         | 0.53%   |
| Slovenia    | 5         | 0.44%   |
| Philippines | 5         | 0.44%   |
| Norway      | 5         | 0.44%   |
| Croatia     | 5         | 0.44%   |
| Colombia    | 5         | 0.44%   |
| Slovakia    | 4         | 0.36%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Montreal          | 15        | 1.26%   |
| Milan             | 13        | 1.1%    |
| Helsinki          | 12        | 1.01%   |
| Berlin            | 12        | 1.01%   |
| St Petersburg     | 11        | 0.93%   |
| Istanbul          | 11        | 0.93%   |
| Amsterdam         | 11        | 0.93%   |
| Frankfurt am Main | 9         | 0.76%   |
| Sydney            | 8         | 0.67%   |
| Paris             | 8         | 0.67%   |
| Hamburg           | 8         | 0.67%   |
| Warsaw            | 7         | 0.59%   |
| Toms River        | 7         | 0.59%   |
| Rome              | 7         | 0.59%   |
| Moscow            | 7         | 0.59%   |
| Vienna            | 6         | 0.51%   |
| Turin             | 6         | 0.51%   |
| Wroclaw           | 5         | 0.42%   |
| Toronto           | 5         | 0.42%   |
| Madrid            | 5         | 0.42%   |
| Jacksonville      | 5         | 0.42%   |
| Barberton         | 5         | 0.42%   |
| Zurich            | 4         | 0.34%   |
| Victoria          | 4         | 0.34%   |
| Singapore         | 4         | 0.34%   |
| Seattle           | 4         | 0.34%   |
| Portland          | 4         | 0.34%   |
| Ottawa            | 4         | 0.34%   |
| Naples            | 4         | 0.34%   |
| Miami             | 4         | 0.34%   |
| Mexico City       | 4         | 0.34%   |
| Mesa              | 4         | 0.34%   |
| Melbourne         | 4         | 0.34%   |
| Malmo             | 4         | 0.34%   |
| London            | 4         | 0.34%   |
| Leipzig           | 4         | 0.34%   |
| Hyderabad         | 4         | 0.34%   |
| Houston           | 4         | 0.34%   |
| Florence          | 4         | 0.34%   |
| Delhi             | 4         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 368       | 561    | 20.2%   |
| Seagate                     | 204       | 285    | 11.2%   |
| WDC                         | 196       | 302    | 10.76%  |
| SanDisk                     | 128       | 157    | 7.03%   |
| Kingston                    | 118       | 166    | 6.48%   |
| Crucial                     | 76        | 113    | 4.17%   |
| SK hynix                    | 72        | 89     | 3.95%   |
| Toshiba                     | 70        | 85     | 3.84%   |
| Micron Technology           | 50        | 56     | 2.74%   |
| Intel                       | 50        | 64     | 2.74%   |
| Unknown                     | 43        | 57     | 2.36%   |
| HGST                        | 30        | 38     | 1.65%   |
| Hitachi                     | 26        | 28     | 1.43%   |
| KIOXIA                      | 25        | 26     | 1.37%   |
| A-DATA Technology           | 24        | 34     | 1.32%   |
| Apple                       | 23        | 30     | 1.26%   |
| Phison Electronics          | 20        | 22     | 1.1%    |
| Phison                      | 20        | 21     | 1.1%    |
| Kingston Technology Company | 16        | 18     | 0.88%   |
| China                       | 16        | 16     | 0.88%   |
| Micron/Crucial Technology   | 13        | 22     | 0.71%   |
| Corsair                     | 10        | 10     | 0.55%   |
| Patriot                     | 9         | 12     | 0.49%   |
| SPCC                        | 8         | 8      | 0.44%   |
| PNY                         | 8         | 9      | 0.44%   |
| LITEONIT                    | 8         | 9      | 0.44%   |
| ADATA Technology            | 8         | 8      | 0.44%   |
| Gigabyte Technology         | 7         | 9      | 0.38%   |
| Silicon Motion              | 6         | 6      | 0.33%   |
| OCZ                         | 6         | 6      | 0.33%   |
| Intenso                     | 6         | 8      | 0.33%   |
| XPG                         | 5         | 5      | 0.27%   |
| Transcend                   | 5         | 6      | 0.27%   |
| Realtek                     | 5         | 8      | 0.27%   |
| Mushkin                     | 5         | 5      | 0.27%   |
| LITEON                      | 5         | 7      | 0.27%   |
| JMicron Technology          | 5         | 5      | 0.27%   |
| Union Memory (Shenzhen)     | 4         | 4      | 0.22%   |
| SABRENT                     | 4         | 6      | 0.22%   |
| Realtek Semiconductor       | 4         | 4      | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 59        | 2.91%   |
| Seagate ST2000DM008-2FR102 2TB                      | 26        | 1.28%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 25        | 1.23%   |
| Kingston SA400S37240G 240GB SSD                     | 23        | 1.14%   |
| Samsung SSD 860 EVO 1TB                             | 21        | 1.04%   |
| Seagate ST1000LM035-1RK172 1TB                      | 20        | 0.99%   |
| Crucial CT500MX500SSD1 500GB                        | 19        | 0.94%   |
| Samsung SSD 860 EVO 500GB                           | 18        | 0.89%   |
| Samsung SSD 850 EVO 250GB                           | 18        | 0.89%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 16        | 0.79%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB    | 16        | 0.79%   |
| Samsung SSD 850 EVO 500GB                           | 15        | 0.74%   |
| Kingston SA400S37120G 120GB SSD                     | 15        | 0.74%   |
| Kingston SA400S37480G 480GB SSD                     | 14        | 0.69%   |
| Samsung SSD 870 QVO 1TB                             | 12        | 0.59%   |
| HGST HTS721010A9E630 1TB                            | 12        | 0.59%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 11        | 0.54%   |
| Seagate ST4000DM004-2CV104 4TB                      | 11        | 0.54%   |
| Seagate ST1000DM010-2EP102 1TB                      | 11        | 0.54%   |
| Samsung SSD 860 EVO 250GB                           | 11        | 0.54%   |
| Samsung SSD 980 1TB                                 | 9         | 0.44%   |
| Samsung SSD 970 EVO 500GB                           | 9         | 0.44%   |
| Phison E16 PCIe4 NVMe Controller 500GB              | 9         | 0.44%   |
| Crucial CT240BX500SSD1 240GB                        | 9         | 0.44%   |
| Crucial CT1000MX500SSD1 1TB                         | 9         | 0.44%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 8         | 0.4%    |
| Unknown SD/MMC/MS PRO 128GB                         | 8         | 0.4%    |
| Unknown MMC Card  64GB                              | 8         | 0.4%    |
| Toshiba MQ01ABD100 1TB                              | 8         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                     | 8         | 0.4%    |
| Samsung SSD 980 500GB                               | 8         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 8         | 0.4%    |
| Intel SSD 660P Series 1024GB                        | 8         | 0.4%    |
| Seagate ST2000DM006-2DM164 2TB                      | 7         | 0.35%   |
| Seagate Expansion Desk 8TB                          | 7         | 0.35%   |
| Samsung SSD 870 EVO 1TB                             | 7         | 0.35%   |
| Samsung NVMe SSD Drive 512GB                        | 7         | 0.35%   |
| Samsung NVMe SSD Drive 1TB                          | 7         | 0.35%   |
| HGST HTS545050A7E680 500GB                          | 7         | 0.35%   |
| WDC WDS120G2G0A-00JH30 120GB SSD                    | 6         | 0.3%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 195       | 272    | 40.88%  |
| WDC                 | 135       | 202    | 28.3%   |
| Toshiba             | 45        | 51     | 9.43%   |
| HGST                | 30        | 38     | 6.29%   |
| Hitachi             | 26        | 28     | 5.45%   |
| Samsung Electronics | 11        | 30     | 2.31%   |
| Unknown             | 8         | 8      | 1.68%   |
| SABRENT             | 4         | 6      | 0.84%   |
| Maxone              | 3         | 3      | 0.63%   |
| Fujitsu             | 3         | 3      | 0.63%   |
| Apple               | 3         | 3      | 0.63%   |
| Maxtor              | 2         | 2      | 0.42%   |
| ASMT                | 2         | 4      | 0.42%   |
| USB3.0              | 1         | 1      | 0.21%   |
| StoreJet            | 1         | 1      | 0.21%   |
| RSH-319             | 1         | 2      | 0.21%   |
| PI-041              | 1         | 1      | 0.21%   |
| MaxDigital          | 1         | 2      | 0.21%   |
| JMicron Technology  | 1         | 1      | 0.21%   |
| HPE                 | 1         | 1      | 0.21%   |
| Generic-            | 1         | 1      | 0.21%   |
| Fantom              | 1         | 2      | 0.21%   |
| Unknown             | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 186       | 260    | 28.7%   |
| Kingston            | 82        | 118    | 12.65%  |
| Crucial             | 68        | 96     | 10.49%  |
| WDC                 | 46        | 59     | 7.1%    |
| SanDisk             | 46        | 53     | 7.1%    |
| A-DATA Technology   | 17        | 20     | 2.62%   |
| China               | 16        | 16     | 2.47%   |
| SK hynix            | 15        | 19     | 2.31%   |
| Micron Technology   | 13        | 17     | 2.01%   |
| Intel               | 12        | 16     | 1.85%   |
| Apple               | 12        | 15     | 1.85%   |
| Toshiba             | 9         | 11     | 1.39%   |
| Patriot             | 9         | 12     | 1.39%   |
| LITEONIT            | 8         | 9      | 1.23%   |
| SPCC                | 6         | 6      | 0.93%   |
| OCZ                 | 6         | 6      | 0.93%   |
| Intenso             | 6         | 8      | 0.93%   |
| Gigabyte Technology | 6         | 7      | 0.93%   |
| Corsair             | 6         | 6      | 0.93%   |
| Seagate             | 5         | 7      | 0.77%   |
| PNY                 | 5         | 6      | 0.77%   |
| Transcend           | 4         | 4      | 0.62%   |
| Mushkin             | 4         | 4      | 0.62%   |
| LITEON              | 4         | 5      | 0.62%   |
| GOODRAM             | 3         | 3      | 0.46%   |
| WDC WDS             | 2         | 2      | 0.31%   |
| Teclast             | 2         | 4      | 0.31%   |
| Plextor             | 2         | 3      | 0.31%   |
| Phison              | 2         | 2      | 0.31%   |
| Netac               | 2         | 3      | 0.31%   |
| Leven               | 2         | 3      | 0.31%   |
| KingSpec            | 2         | 2      | 0.31%   |
| KingFast            | 2         | 2      | 0.31%   |
| Hewlett-Packard     | 2         | 2      | 0.31%   |
| Emtec               | 2         | 2      | 0.31%   |
| Apacer              | 2         | 2      | 0.31%   |
| Zheino              | 1         | 1      | 0.15%   |
| WALTON              | 1         | 2      | 0.15%   |
| V-GeN               | 1         | 1      | 0.15%   |
| Unknown             | 1         | 2      | 0.15%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 623       | 882    | 39.43%  |
| SSD     | 511       | 861    | 32.34%  |
| HDD     | 393       | 663    | 24.87%  |
| MMC     | 34        | 44     | 2.15%   |
| Unknown | 19        | 25     | 1.2%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 669       | 1427   | 47.31%  |
| NVMe | 622       | 871    | 43.99%  |
| SAS  | 89        | 133    | 6.29%   |
| MMC  | 34        | 44     | 2.4%    |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 481       | 826    | 49.23%  |
| 0.51-1.0   | 313       | 436    | 32.04%  |
| 1.01-2.0   | 102       | 154    | 10.44%  |
| 3.01-4.0   | 34        | 52     | 3.48%   |
| 4.01-10.0  | 22        | 29     | 2.25%   |
| 2.01-3.0   | 20        | 22     | 2.05%   |
| 10.01-20.0 | 5         | 5      | 0.51%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 238       | 20.45%  |
| 251-500        | 198       | 17.01%  |
| 1001-2000      | 185       | 15.89%  |
| 501-1000       | 178       | 15.29%  |
| More than 3000 | 111       | 9.54%   |
| Unknown        | 70        | 6.01%   |
| 2001-3000      | 62        | 5.33%   |
| 1-20           | 57        | 4.9%    |
| 51-100         | 44        | 3.78%   |
| 21-50          | 21        | 1.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 261       | 21.52%  |
| 101-250        | 186       | 15.33%  |
| 21-50          | 178       | 14.67%  |
| 51-100         | 156       | 12.86%  |
| 251-500        | 121       | 9.98%   |
| 501-1000       | 101       | 8.33%   |
| 1001-2000      | 86        | 7.09%   |
| Unknown        | 70        | 5.77%   |
| More than 3000 | 33        | 2.72%   |
| 2001-3000      | 17        | 1.4%    |
| 0              | 4         | 0.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| HGST HTS545050A7E680 500GB               | 6         | 11     | 5.5%    |
| HGST HTS721010A9E630 1TB                 | 4         | 4      | 3.67%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 2.75%   |
| WDC WDS120G2G0A-00JH30 120GB SSD         | 2         | 2      | 1.83%   |
| WDC WD20EARX-00PASB0 2TB                 | 2         | 2      | 1.83%   |
| Seagate ST9320325AS 320GB                | 2         | 5      | 1.83%   |
| Seagate ST500LT012-1DG142 500GB          | 2         | 2      | 1.83%   |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 8      | 1.83%   |
| Seagate ST1000LM035-1RK172 1TB           | 2         | 2      | 1.83%   |
| Corsair Force LS SSD 120GB               | 2         | 2      | 1.83%   |
| XPG GAMMIX S11 240GB                     | 1         | 1      | 0.92%   |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.92%   |
| WDC WD5000LPVT-22G33T0 500GB             | 1         | 1      | 0.92%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 1         | 1      | 0.92%   |
| WDC WD5000AZRX-00A8LB0 500GB             | 1         | 1      | 0.92%   |
| WDC WD5000AVDS-63U7B1 500GB              | 1         | 1      | 0.92%   |
| WDC WD40EFRX-68WT0N0 4TB                 | 1         | 2      | 0.92%   |
| WDC WD2003FZEX-00Z4SA0 2TB               | 1         | 1      | 0.92%   |
| WDC WD2002FYPS-01U1B0 2TB                | 1         | 1      | 0.92%   |
| WDC WD10SPZX-24Z10T0 1TB                 | 1         | 1      | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 0.92%   |
| WDC WD10EARS-00MVWB0 1TB                 | 1         | 1      | 0.92%   |
| WDC WD10EACS-00D6B1 1TB                  | 1         | 1      | 0.92%   |
| WDC WD1003FBYZ-010FB0 1TB                | 1         | 2      | 0.92%   |
| WDC WD1002FBYS-02A6B0 1TB                | 1         | 1      | 0.92%   |
| WDC WD Blue SA510 2.5 1TB                | 1         | 2      | 0.92%   |
| WDC PC SA530 SDASN8Y-256G-1006 256GB     | 1         | 1      | 0.92%   |
| Transcend TS240GMTS420S 240GB SSD        | 1         | 1      | 0.92%   |
| Toshiba THNSNK128GVN8 M.2 2280 128GB SSD | 1         | 1      | 0.92%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.92%   |
| Toshiba MQ01ABD050 500GB                 | 1         | 2      | 0.92%   |
| Toshiba MK5055GSXF 500GB                 | 1         | 1      | 0.92%   |
| Toshiba MK2533GSG 250GB                  | 1         | 1      | 0.92%   |
| Toshiba KSG60ZMV256G M.2 2280 256GB SSD  | 1         | 1      | 0.92%   |
| Toshiba DT01ACA300 3TB                   | 1         | 2      | 0.92%   |
| Toshiba DT01ACA100 1TB                   | 1         | 1      | 0.92%   |
| Toshiba DT01ACA050 500GB                 | 1         | 1      | 0.92%   |
| SSSTC CV8-8E128-HP 128GB SSD             | 1         | 1      | 0.92%   |
| SK hynix SC308 SATA 128GB SSD            | 1         | 1      | 0.92%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 1         | 1      | 0.92%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 33     | 19.63%  |
| WDC                 | 19        | 23     | 17.76%  |
| HGST                | 11        | 16     | 10.28%  |
| Toshiba             | 9         | 11     | 8.41%   |
| Samsung Electronics | 8         | 12     | 7.48%   |
| SK hynix            | 6         | 6      | 5.61%   |
| Hitachi             | 5         | 5      | 4.67%   |
| Crucial             | 4         | 13     | 3.74%   |
| SanDisk             | 3         | 4      | 2.8%    |
| Intel               | 3         | 3      | 2.8%    |
| Kingston            | 2         | 2      | 1.87%   |
| Corsair             | 2         | 2      | 1.87%   |
| Apple               | 2         | 2      | 1.87%   |
| XPG                 | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| SSSTC               | 1         | 1      | 0.93%   |
| Patriot             | 1         | 1      | 0.93%   |
| OCZ                 | 1         | 1      | 0.93%   |
| Micron Technology   | 1         | 1      | 0.93%   |
| LITEONIT            | 1         | 1      | 0.93%   |
| Fujitsu             | 1         | 1      | 0.93%   |
| Drevo               | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |
| ASMT                | 1         | 2      | 0.93%   |
| A-DATA Technology   | 1         | 1      | 0.93%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 21        | 33     | 33.87%  |
| WDC                 | 15        | 17     | 24.19%  |
| HGST                | 11        | 16     | 17.74%  |
| Toshiba             | 7         | 9      | 11.29%  |
| Hitachi             | 5         | 5      | 8.06%   |
| Samsung Electronics | 1         | 1      | 1.61%   |
| Fujitsu             | 1         | 1      | 1.61%   |
| ASMT                | 1         | 2      | 1.61%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 60        | 84     | 58.25%  |
| SSD  | 35        | 49     | 33.98%  |
| NVMe | 8         | 12     | 7.77%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BC142 500GB   | 1         | 1      | 33.33%  |
| Samsung Electronics HD252HJ 250GB | 1         | 1      | 33.33%  |
| LITEON CA3-8D512 512GB            | 1         | 2      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 1      | 33.33%  |
| LITEON              | 1         | 2      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 769       | 1523   | 61.62%  |
| Detected | 377       | 803    | 30.21%  |
| Malfunc  | 99        | 145    | 7.93%   |
| Failed   | 3         | 4      | 0.24%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 580       | 36.43%  |
| AMD                            | 283       | 17.78%  |
| Samsung Electronics            | 221       | 13.88%  |
| SanDisk                        | 116       | 7.29%   |
| SK hynix                       | 56        | 3.52%   |
| Kingston Technology Company    | 54        | 3.39%   |
| Phison Electronics             | 46        | 2.89%   |
| Micron Technology              | 38        | 2.39%   |
| ASMedia Technology             | 34        | 2.14%   |
| KIOXIA                         | 27        | 1.7%    |
| Micron/Crucial Technology      | 21        | 1.32%   |
| Toshiba America Info Systems   | 16        | 1.01%   |
| ADATA Technology               | 15        | 0.94%   |
| Silicon Motion                 | 9         | 0.57%   |
| Solid State Storage Technology | 8         | 0.5%    |
| Realtek Semiconductor          | 8         | 0.5%    |
| Apple                          | 8         | 0.5%    |
| Marvell Technology Group       | 7         | 0.44%   |
| JMicron Technology             | 7         | 0.44%   |
| Union Memory (Shenzhen)        | 6         | 0.38%   |
| Seagate Technology             | 5         | 0.31%   |
| Nvidia                         | 5         | 0.31%   |
| MAXIO Technology (Hangzhou)    | 5         | 0.31%   |
| Shenzhen Longsys Electronics   | 3         | 0.19%   |
| Lenovo                         | 3         | 0.19%   |
| Yangtze Memory Technologies    | 2         | 0.13%   |
| Transcend                      | 2         | 0.13%   |
| Lite-On Technology             | 2         | 0.13%   |
| VIA Technologies               | 1         | 0.06%   |
| LSI Logic / Symbios Logic      | 1         | 0.06%   |
| INNOGRIT                       | 1         | 0.06%   |
| Broadcom / LSI                 | 1         | 0.06%   |
| Biwin Storage Technology       | 1         | 0.06%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 215       | 12.36%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 108       | 6.21%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 63        | 3.62%   |
| AMD 400 Series Chipset SATA Controller                                         | 58        | 3.34%   |
| Samsung NVMe SSD Controller 980                                                | 57        | 3.28%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 45        | 2.59%   |
| Intel Volume Management Device NVMe RAID Controller                            | 35        | 2.01%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 34        | 1.96%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 33        | 1.9%    |
| ASMedia ASM1062 Serial ATA Controller                                          | 33        | 1.9%    |
| AMD 500 Series Chipset SATA Controller                                         | 32        | 1.84%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 30        | 1.73%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 29        | 1.67%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 28        | 1.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 27        | 1.55%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 27        | 1.55%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 1.5%    |
| Intel Comet Lake SATA AHCI Controller                                          | 20        | 1.15%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 20        | 1.15%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 19        | 1.09%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 19        | 1.09%   |
| Phison E12 NVMe Controller                                                     | 18        | 1.04%   |
| Intel SSD 660P Series                                                          | 18        | 1.04%   |
| Phison E16 PCIe4 NVMe Controller                                               | 17        | 0.98%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 16        | 0.92%   |
| Intel Tiger Lake-LP SATA Controller                                            | 16        | 0.92%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 16        | 0.92%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 15        | 0.86%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 15        | 0.86%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 15        | 0.86%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 13        | 0.75%   |
| SanDisk WD Black 2018/SN750 / PC SN720 NVMe SSD                                | 12        | 0.69%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 12        | 0.69%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 12        | 0.69%   |
| Kingston Company OM8PCP Design-In PCIe 3 NVMe SSD (DRAM-less)                  | 12        | 0.69%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 12        | 0.69%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 11        | 0.63%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 11        | 0.63%   |
| Kingston Company A2000 NVMe SSD                                                | 10        | 0.58%   |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD        | 9         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 768       | 50.53%  |
| NVMe | 621       | 40.86%  |
| RAID | 90        | 5.92%   |
| IDE  | 36        | 2.37%   |
| SAS  | 5         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 701       | 62.98%  |
| AMD    | 411       | 36.93%  |
| ARM    | 1         | 0.09%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor            | 20        | 1.8%    |
| AMD Ryzen 5 3600 6-Core Processor             | 18        | 1.62%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 1.53%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 17        | 1.53%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 16        | 1.44%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 1.35%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 14        | 1.26%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 1.17%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 13        | 1.17%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 13        | 1.17%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 13        | 1.17%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 12        | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 12        | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 12        | 1.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.99%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 11        | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 10        | 0.9%    |
| Intel Core i5-6300U CPU @ 2.40GHz             | 10        | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor           | 10        | 0.9%    |
| AMD Ryzen 7 5800X 8-Core Processor            | 10        | 0.9%    |
| Intel Core i7-8750H CPU @ 2.20GHz             | 9         | 0.81%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 9         | 0.81%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 9         | 0.81%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 9         | 0.81%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 8         | 0.72%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 8         | 0.72%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 8         | 0.72%   |
| Intel 12th Gen Core i7-12700H                 | 8         | 0.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.72%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.63%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 7         | 0.63%   |
| Intel Core i5-6600K CPU @ 3.50GHz             | 7         | 0.63%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 7         | 0.63%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 7         | 0.63%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 7         | 0.63%   |
| AMD Ryzen 7 6800H with Radeon Graphics        | 7         | 0.63%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 7         | 0.63%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 7         | 0.63%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 6         | 0.54%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 6         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 243       | 21.83%  |
| Intel Core i7           | 204       | 18.33%  |
| AMD Ryzen 7             | 142       | 12.76%  |
| AMD Ryzen 5             | 139       | 12.49%  |
| Other                   | 112       | 10.06%  |
| Intel Core i3           | 46        | 4.13%   |
| AMD Ryzen 9             | 46        | 4.13%   |
| Intel Celeron           | 35        | 3.14%   |
| Intel Core 2 Duo        | 19        | 1.71%   |
| Intel Xeon              | 18        | 1.62%   |
| AMD Ryzen 3             | 18        | 1.62%   |
| AMD Ryzen 7 PRO         | 17        | 1.53%   |
| Intel Pentium           | 11        | 0.99%   |
| AMD A4                  | 8         | 0.72%   |
| AMD FX                  | 6         | 0.54%   |
| Intel Core i9           | 5         | 0.45%   |
| Intel Core m3           | 4         | 0.36%   |
| AMD Ryzen 5 PRO         | 4         | 0.36%   |
| AMD Athlon              | 4         | 0.36%   |
| AMD A8                  | 4         | 0.36%   |
| Intel Core 2 Quad       | 3         | 0.27%   |
| AMD Ryzen Threadripper  | 3         | 0.27%   |
| AMD A10                 | 3         | 0.27%   |
| Intel Pentium Gold      | 2         | 0.18%   |
| Intel Pentium Dual-Core | 2         | 0.18%   |
| Intel Core 2            | 2         | 0.18%   |
| Intel Atom              | 2         | 0.18%   |
| AMD E1                  | 2         | 0.18%   |
| Intel Pentium Dual      | 1         | 0.09%   |
| Intel Core m5           | 1         | 0.09%   |
| Intel Core 2 Extreme    | 1         | 0.09%   |
| AMD Phenom II X6        | 1         | 0.09%   |
| AMD Phenom II X4        | 1         | 0.09%   |
| AMD E                   | 1         | 0.09%   |
| AMD Athlon X4           | 1         | 0.09%   |
| AMD Athlon II X4        | 1         | 0.09%   |
| AMD Athlon II           | 1         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 381       | 34.2%   |
| 2      | 279       | 25.04%  |
| 8      | 203       | 18.22%  |
| 6      | 170       | 15.26%  |
| 12     | 33        | 2.96%   |
| 14     | 19        | 1.71%   |
| 16     | 11        | 0.99%   |
| 10     | 11        | 0.99%   |
| 3      | 3         | 0.27%   |
| 32     | 1         | 0.09%   |
| 24     | 1         | 0.09%   |
| 5      | 1         | 0.09%   |
| 1      | 1         | 0.09%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 1108      | 99.46%  |
| 2      | 6         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 908       | 81.51%  |
| 1      | 206       | 18.49%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1110      | 99.73%  |
| Unknown        | 2         | 0.18%   |
| 64-bit         | 1         | 0.09%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 473       | 41.35%  |
| 0x0a50000c | 38        | 3.32%   |
| 0x306c3    | 31        | 2.71%   |
| 0x08701021 | 30        | 2.62%   |
| 0x306a9    | 25        | 2.19%   |
| 0x806ea    | 23        | 2.01%   |
| 0x406e3    | 22        | 1.92%   |
| 0x08108109 | 22        | 1.92%   |
| 0x906ea    | 20        | 1.75%   |
| 0x806e9    | 20        | 1.75%   |
| 0x08600106 | 20        | 1.75%   |
| 0x806ec    | 18        | 1.57%   |
| 0x806c1    | 18        | 1.57%   |
| 0x506e3    | 18        | 1.57%   |
| 0x08608103 | 18        | 1.57%   |
| 0x40651    | 17        | 1.49%   |
| 0x08600104 | 16        | 1.4%    |
| 0x906e9    | 15        | 1.31%   |
| 0x0a404102 | 14        | 1.22%   |
| 0x706e5    | 12        | 1.05%   |
| 0x0a201009 | 12        | 1.05%   |
| 0x08108102 | 12        | 1.05%   |
| 0x206a7    | 11        | 0.96%   |
| 0x08701013 | 11        | 0.96%   |
| 0x906a3    | 10        | 0.87%   |
| 0x0a50000d | 10        | 0.87%   |
| 0x706a1    | 9         | 0.79%   |
| 0x306d4    | 9         | 0.79%   |
| 0x1067a    | 9         | 0.79%   |
| 0x0a20120a | 8         | 0.7%    |
| 0x406c4    | 7         | 0.61%   |
| 0x0a201016 | 7         | 0.61%   |
| 0x0800820d | 7         | 0.61%   |
| 0x08001138 | 7         | 0.61%   |
| 0xa0652    | 6         | 0.52%   |
| 0x806d1    | 6         | 0.52%   |
| 0x06006705 | 6         | 0.52%   |
| 0xa0655    | 5         | 0.44%   |
| 0x20655    | 5         | 0.44%   |
| 0x0a404101 | 5         | 0.44%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 203       | 18.22%  |
| Zen 2            | 119       | 10.68%  |
| Zen 3            | 111       | 9.96%   |
| Haswell          | 91        | 8.17%   |
| Unknown          | 84        | 7.54%   |
| Skylake          | 66        | 5.92%   |
| Zen+             | 56        | 5.03%   |
| IvyBridge        | 47        | 4.22%   |
| TigerLake        | 44        | 3.95%   |
| Alderlake Hybrid | 33        | 2.96%   |
| SandyBridge      | 30        | 2.69%   |
| Icelake          | 30        | 2.69%   |
| CometLake        | 30        | 2.69%   |
| Zen              | 25        | 2.24%   |
| Broadwell        | 24        | 2.15%   |
| Penryn           | 19        | 1.71%   |
| Goldmont plus    | 15        | 1.35%   |
| Excavator        | 15        | 1.35%   |
| Westmere         | 14        | 1.26%   |
| Silvermont       | 14        | 1.26%   |
| Core             | 10        | 0.9%    |
| Piledriver       | 7         | 0.63%   |
| Jaguar           | 6         | 0.54%   |
| Nehalem          | 5         | 0.45%   |
| Tremont          | 3         | 0.27%   |
| K10              | 3         | 0.27%   |
| Goldmont         | 3         | 0.27%   |
| Puma             | 2         | 0.18%   |
| Bulldozer        | 2         | 0.18%   |
| Steamroller      | 1         | 0.09%   |
| K10 Llano        | 1         | 0.09%   |
| Bobcat           | 1         | 0.09%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 549       | 40.13%  |
| Nvidia | 423       | 30.92%  |
| AMD    | 396       | 28.95%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 54        | 3.83%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 49        | 3.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 43        | 3.05%   |
| Intel UHD Graphics 620                                                      | 42        | 2.98%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 37        | 2.62%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 36        | 2.55%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 30        | 2.13%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 28        | 1.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 27        | 1.91%   |
| AMD Rembrandt [Radeon 680M]                                                 | 27        | 1.91%   |
| AMD Lucienne                                                                | 26        | 1.84%   |
| Intel HD Graphics 620                                                       | 25        | 1.77%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 25        | 1.77%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 23        | 1.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 21        | 1.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 20        | 1.42%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 18        | 1.28%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 18        | 1.28%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 17        | 1.21%   |
| Intel HD Graphics 630                                                       | 17        | 1.21%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 17        | 1.21%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 16        | 1.13%   |
| Intel HD Graphics 5500                                                      | 16        | 1.13%   |
| Intel HD Graphics 530                                                       | 16        | 1.13%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 16        | 1.13%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 15        | 1.06%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 15        | 1.06%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 13        | 0.92%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 13        | 0.92%   |
| Nvidia GP108M [GeForce MX150]                                               | 12        | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 12        | 0.85%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 11        | 0.78%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 11        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 11        | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                      | 11        | 0.78%   |
| Intel Core Processor Integrated Graphics Controller                         | 11        | 0.78%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                    | 11        | 0.78%   |
| AMD Barcelo                                                                 | 11        | 0.78%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 10        | 0.71%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                     | Computers | Percent |
|--------------------------|-----------|---------|
| 1 x Intel                | 346       | 30.92%  |
| 1 x AMD                  | 286       | 25.56%  |
| 1 x Nvidia               | 198       | 17.69%  |
| Intel + Nvidia           | 167       | 14.92%  |
| AMD + Nvidia             | 53        | 4.74%   |
| 2 x AMD                  | 36        | 3.22%   |
| Intel + AMD              | 23        | 2.06%   |
| 2 x Intel                | 4         | 0.36%   |
| 2 x Nvidia               | 3         | 0.27%   |
| Other                    | 2         | 0.18%   |
| Intel + AMD + 1 x Nvidia | 1         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 794       | 71.08%  |
| Proprietary | 322       | 28.83%  |
| Unknown     | 1         | 0.09%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 619       | 54.59%  |
| 0.01-0.5   | 122       | 10.76%  |
| 1.01-2.0   | 98        | 8.64%   |
| 7.01-8.0   | 87        | 7.67%   |
| 3.01-4.0   | 74        | 6.53%   |
| 5.01-6.0   | 46        | 4.06%   |
| 8.01-16.0  | 43        | 3.79%   |
| 0.51-1.0   | 32        | 2.82%   |
| 2.01-3.0   | 8         | 0.71%   |
| 16.01-24.0 | 5         | 0.44%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 157       | 11.48%  |
| Samsung Electronics     | 144       | 10.53%  |
| BOE                     | 135       | 9.87%   |
| Chimei Innolux          | 126       | 9.21%   |
| LG Display              | 107       | 7.82%   |
| Goldstar                | 68        | 4.97%   |
| Dell                    | 64        | 4.68%   |
| Acer                    | 53        | 3.87%   |
| AOC                     | 45        | 3.29%   |
| Ancor Communications    | 38        | 2.78%   |
| Lenovo                  | 35        | 2.56%   |
| BenQ                    | 34        | 2.49%   |
| Hewlett-Packard         | 33        | 2.41%   |
| Apple                   | 29        | 2.12%   |
| PANDA                   | 26        | 1.9%    |
| ASUSTek Computer        | 26        | 1.9%    |
| Sharp                   | 21        | 1.54%   |
| Philips                 | 18        | 1.32%   |
| ViewSonic               | 16        | 1.17%   |
| Iiyama                  | 15        | 1.1%    |
| InfoVision              | 13        | 0.95%   |
| Gigabyte Technology     | 11        | 0.8%    |
| TMX                     | 10        | 0.73%   |
| CSO                     | 9         | 0.66%   |
| Vizio                   | 8         | 0.58%   |
| LG Electronics          | 7         | 0.51%   |
| Chi Mei Optoelectronics | 6         | 0.44%   |
| Sony                    | 5         | 0.37%   |
| Unknown                 | 4         | 0.29%   |
| Pixio                   | 4         | 0.29%   |
| MSI                     | 4         | 0.29%   |
| Fujitsu Siemens         | 4         | 0.29%   |
| Valve                   | 3         | 0.22%   |
| Toshiba                 | 3         | 0.22%   |
| Sceptre Tech            | 3         | 0.22%   |
| RTK                     | 3         | 0.22%   |
| Panasonic               | 3         | 0.22%   |
| Mi                      | 3         | 0.22%   |
| LG Philips              | 3         | 0.22%   |
| JDI                     | 3         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 9         | 0.64%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.56%   |
| Lenovo P24q-10 LEN61A5 2560x1440 527x296mm 23.8-inch                  | 7         | 0.49%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 7         | 0.49%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 7         | 0.49%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 7         | 0.49%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 7         | 0.49%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 7         | 0.49%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 7         | 0.49%   |
| ViewSonic VX2776 Series VSC3E32 1920x1080 600x340mm 27.2-inch         | 6         | 0.42%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 6         | 0.42%   |
| LG Display LCD Monitor LGD0555 2736x1824 260x173mm 12.3-inch          | 6         | 0.42%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 5         | 0.35%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 5         | 0.35%   |
| Samsung Electronics S24D590 SAM0B47 1920x1080 521x293mm 23.5-inch     | 5         | 0.35%   |
| Samsung Electronics LCD Monitor SDC4171 2880x1800 302x189mm 14.0-inch | 5         | 0.35%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 5         | 0.35%   |
| PANDA LCD Monitor NCP0035 1920x1080 344x194mm 15.5-inch               | 5         | 0.35%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 5         | 0.35%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 5         | 0.35%   |
| AOC 27B2 AOC2702 1920x1080 598x336mm 27.0-inch                        | 5         | 0.35%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 4         | 0.28%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 4         | 0.28%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch               | 4         | 0.28%   |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch          | 4         | 0.28%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 4         | 0.28%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch               | 4         | 0.28%   |
| Gigabyte Technology M27Q GBT270D 2560x1440 700x390mm 31.5-inch        | 4         | 0.28%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch        | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch       | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN15D2 1920x1080 344x193mm 15.5-inch      | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 0.28%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 4         | 0.28%   |
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                    | 4         | 0.28%   |
| Valve Index HMD VLV91A8 2880x1600                                     | 3         | 0.21%   |
| TMX TL140ADXP01 TMX1481 2560x1600 301x188mm 14.0-inch                 | 3         | 0.21%   |
| Sharp LQ156M1JW03 SHP14C5 1920x1080 344x194mm 15.5-inch               | 3         | 0.21%   |
| Samsung Electronics LCD Monitor SDC4154 2880x1800 302x189mm 14.0-inch | 3         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 631       | 49.03%  |
| 1366x768 (WXGA)    | 150       | 11.66%  |
| 2560x1440 (QHD)    | 114       | 8.86%   |
| 3840x2160 (4K)     | 94        | 7.3%    |
| 2560x1600          | 37        | 2.87%   |
| 1920x1200 (WUXGA)  | 31        | 2.41%   |
| 1440x900 (WXGA+)   | 25        | 1.94%   |
| 2560x1080          | 21        | 1.63%   |
| 1600x900 (HD+)     | 20        | 1.55%   |
| 1280x1024 (SXGA)   | 18        | 1.4%    |
| 3440x1440          | 16        | 1.24%   |
| 2880x1800          | 16        | 1.24%   |
| 1680x1050 (WSXGA+) | 15        | 1.17%   |
| Unknown            | 15        | 1.17%   |
| 1280x800 (WXGA)    | 9         | 0.7%    |
| 3840x1080          | 7         | 0.54%   |
| 2160x1440          | 7         | 0.54%   |
| 2736x1824          | 6         | 0.47%   |
| 3840x2400          | 5         | 0.39%   |
| 3200x2000          | 5         | 0.39%   |
| 1360x768           | 5         | 0.39%   |
| 3456x2160          | 3         | 0.23%   |
| 3200x1800 (QHD+)   | 3         | 0.23%   |
| 3072x1920          | 3         | 0.23%   |
| 1920x540           | 3         | 0.23%   |
| 3840x1600          | 2         | 0.16%   |
| 3000x2000          | 2         | 0.16%   |
| 2240x1400          | 2         | 0.16%   |
| 1920x1280          | 2         | 0.16%   |
| 1800x1200          | 2         | 0.16%   |
| 1024x768 (XGA)     | 2         | 0.16%   |
| 9840x3840          | 1         | 0.08%   |
| 5760x1080          | 1         | 0.08%   |
| 4480x1440          | 1         | 0.08%   |
| 3840x2560          | 1         | 0.08%   |
| 3840x1440          | 1         | 0.08%   |
| 3840x1200          | 1         | 0.08%   |
| 3840x1100          | 1         | 0.08%   |
| 3520x1080          | 1         | 0.08%   |
| 3240x2160          | 1         | 0.08%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 310       | 22.55%  |
| 13      | 147       | 10.69%  |
| 27      | 140       | 10.18%  |
| 24      | 133       | 9.67%   |
| 14      | 127       | 9.24%   |
| 23      | 66        | 4.8%    |
| 21      | 62        | 4.51%   |
| 17      | 50        | 3.64%   |
| 31      | 42        | 3.05%   |
| Unknown | 40        | 2.91%   |
| 16      | 37        | 2.69%   |
| 34      | 34        | 2.47%   |
| 12      | 23        | 1.67%   |
| 19      | 19        | 1.38%   |
| 18      | 15        | 1.09%   |
| 54      | 12        | 0.87%   |
| 22      | 12        | 0.87%   |
| 20      | 12        | 0.87%   |
| 11      | 12        | 0.87%   |
| 84      | 7         | 0.51%   |
| 32      | 7         | 0.51%   |
| 40      | 6         | 0.44%   |
| 72      | 5         | 0.36%   |
| 28      | 5         | 0.36%   |
| 10      | 5         | 0.36%   |
| 46      | 4         | 0.29%   |
| 42      | 4         | 0.29%   |
| 29      | 4         | 0.29%   |
| 52      | 3         | 0.22%   |
| 49      | 3         | 0.22%   |
| 37      | 3         | 0.22%   |
| 25      | 3         | 0.22%   |
| 74      | 2         | 0.15%   |
| 69      | 2         | 0.15%   |
| 65      | 2         | 0.15%   |
| 58      | 2         | 0.15%   |
| 48      | 2         | 0.15%   |
| 36      | 2         | 0.15%   |
| 35      | 2         | 0.15%   |
| 33      | 2         | 0.15%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 539       | 40.74%  |
| 501-600     | 296       | 22.37%  |
| 201-300     | 116       | 8.77%   |
| 401-500     | 107       | 8.09%   |
| 351-400     | 63        | 4.76%   |
| 601-700     | 55        | 4.16%   |
| 701-800     | 44        | 3.33%   |
| Unknown     | 40        | 3.02%   |
| 1001-1500   | 30        | 2.27%   |
| 1501-2000   | 16        | 1.21%   |
| 801-900     | 12        | 0.91%   |
| 901-1000    | 4         | 0.3%    |
| 101-200     | 1         | 0.08%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 901       | 76.62%  |
| 16/10   | 148       | 12.59%  |
| 21/9    | 38        | 3.23%   |
| Unknown | 32        | 2.72%   |
| 3/2     | 25        | 2.13%   |
| 5/4     | 13        | 1.11%   |
| 4/3     | 5         | 0.43%   |
| 6/5     | 4         | 0.34%   |
| 32/9    | 4         | 0.34%   |
| 2.65    | 3         | 0.26%   |
| 3.40    | 1         | 0.09%   |
| 0.62    | 1         | 0.09%   |
| 0.56    | 1         | 0.09%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 312       | 23.06%  |
| 81-90          | 213       | 15.74%  |
| 201-250        | 204       | 15.08%  |
| 301-350        | 143       | 10.57%  |
| 351-500        | 86        | 6.36%   |
| 71-80          | 65        | 4.8%    |
| 151-200        | 46        | 3.4%    |
| 251-300        | 45        | 3.33%   |
| 121-130        | 40        | 2.96%   |
| Unknown        | 40        | 2.96%   |
| More than 1000 | 39        | 2.88%   |
| 111-120        | 32        | 2.37%   |
| 501-1000       | 24        | 1.77%   |
| 141-150        | 20        | 1.48%   |
| 61-70          | 15        | 1.11%   |
| 51-60          | 13        | 0.96%   |
| 131-140        | 7         | 0.52%   |
| 41-50          | 5         | 0.37%   |
| 91-100         | 3         | 0.22%   |
| 1-40           | 1         | 0.07%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 420       | 32.71%  |
| 51-100        | 356       | 27.73%  |
| 101-120       | 257       | 20.02%  |
| 161-240       | 131       | 10.2%   |
| More than 240 | 47        | 3.66%   |
| Unknown       | 40        | 3.12%   |
| 1-50          | 33        | 2.57%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 861       | 75.53%  |
| 2     | 240       | 21.05%  |
| 3     | 34        | 2.98%   |
| 0     | 3         | 0.26%   |
| 4     | 2         | 0.18%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 653       | 38.43%  |
| Intel                             | 618       | 36.37%  |
| Qualcomm Atheros                  | 129       | 7.59%   |
| MediaTek                          | 61        | 3.59%   |
| Broadcom                          | 52        | 3.06%   |
| ASIX Electronics                  | 21        | 1.24%   |
| TP-Link                           | 17        | 1%      |
| Broadcom Limited                  | 13        | 0.77%   |
| Microsoft                         | 12        | 0.71%   |
| D-Link                            | 11        | 0.65%   |
| Sierra Wireless                   | 8         | 0.47%   |
| Ralink                            | 7         | 0.41%   |
| Lenovo                            | 7         | 0.41%   |
| DisplayLink                       | 7         | 0.41%   |
| Aquantia                          | 7         | 0.41%   |
| Ralink Technology                 | 5         | 0.29%   |
| Marvell Technology Group          | 5         | 0.29%   |
| Samsung Electronics               | 4         | 0.24%   |
| Qualcomm                          | 4         | 0.24%   |
| Hewlett-Packard                   | 4         | 0.24%   |
| Google                            | 4         | 0.24%   |
| Cypress Semiconductor             | 4         | 0.24%   |
| Apple                             | 4         | 0.24%   |
| Qualcomm Atheros Communications   | 3         | 0.18%   |
| OPPO Electronics                  | 3         | 0.18%   |
| Nvidia                            | 3         | 0.18%   |
| Huawei Technologies               | 3         | 0.18%   |
| Xiaomi                            | 2         | 0.12%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.12%   |
| Oculus VR                         | 2         | 0.12%   |
| NetGear                           | 2         | 0.12%   |
| Microchip Technology              | 2         | 0.12%   |
| Linksys                           | 2         | 0.12%   |
| ICS Advent                        | 2         | 0.12%   |
| Ericsson Business Mobile Networks | 2         | 0.12%   |
| Wilocity                          | 1         | 0.06%   |
| Quectel Wireless Solutions        | 1         | 0.06%   |
| Qualcomm Technologies             | 1         | 0.06%   |
| Motorola PCS                      | 1         | 0.06%   |
| Mellanox Technologies             | 1         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 442       | 21.9%   |
| Intel Wi-Fi 6 AX200                                               | 101       | 5%      |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 2.97%   |
| Intel Wireless 8265 / 8275                                        | 41        | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 1.98%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 1.88%   |
| Intel I211 Gigabit Network Connection                             | 38        | 1.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 37        | 1.83%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 36        | 1.78%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 34        | 1.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 32        | 1.59%   |
| Intel Wi-Fi 6 AX201                                               | 31        | 1.54%   |
| Intel Wireless 7265                                               | 30        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 27        | 1.34%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 25        | 1.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 1.19%   |
| Intel Wireless 7260                                               | 23        | 1.14%   |
| Intel Wireless-AC 9260                                            | 21        | 1.04%   |
| Intel Wireless 8260                                               | 21        | 1.04%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 21        | 1.04%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 20        | 0.99%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 19        | 0.94%   |
| Intel Wireless 3165                                               | 19        | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 19        | 0.94%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 0.94%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 18        | 0.89%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 0.89%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 0.84%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 16        | 0.79%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 15        | 0.74%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 14        | 0.69%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 13        | 0.64%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 13        | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 12        | 0.59%   |
| Realtek 802.11ac NIC                                              | 12        | 0.59%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 0.59%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 11        | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 11        | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 530       | 53.11%  |
| Realtek Semiconductor                 | 171       | 17.13%  |
| Qualcomm Atheros                      | 104       | 10.42%  |
| MediaTek                              | 60        | 6.01%   |
| Broadcom                              | 40        | 4.01%   |
| TP-Link                               | 15        | 1.5%    |
| Broadcom Limited                      | 12        | 1.2%    |
| Microsoft                             | 11        | 1.1%    |
| D-Link                                | 11        | 1.1%    |
| Sierra Wireless                       | 8         | 0.8%    |
| Ralink                                | 7         | 0.7%    |
| Ralink Technology                     | 5         | 0.5%    |
| Qualcomm                              | 4         | 0.4%    |
| Marvell Technology Group              | 4         | 0.4%    |
| Qualcomm Atheros Communications       | 3         | 0.3%    |
| Linksys                               | 2         | 0.2%    |
| Wilocity                              | 1         | 0.1%    |
| Quectel Wireless Solutions            | 1         | 0.1%    |
| Qualcomm Technologies                 | 1         | 0.1%    |
| NetGear                               | 1         | 0.1%    |
| Fibocom                               | 1         | 0.1%    |
| Edimax Technology                     | 1         | 0.1%    |
| Dell                                  | 1         | 0.1%    |
| D-Link System                         | 1         | 0.1%    |
| Belkin Components                     | 1         | 0.1%    |
| AVM                                   | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 101       | 10%     |
| Intel Wireless 8265 / 8275                                    | 41        | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 37        | 3.66%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 36        | 3.56%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 34        | 3.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 32        | 3.17%   |
| Intel Wi-Fi 6 AX201                                           | 31        | 3.07%   |
| Intel Wireless 7265                                           | 30        | 2.97%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 27        | 2.67%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 24        | 2.38%   |
| Intel Wireless 7260                                           | 23        | 2.28%   |
| Intel Wireless-AC 9260                                        | 21        | 2.08%   |
| Intel Wireless 8260                                           | 21        | 2.08%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 21        | 2.08%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 20        | 1.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 19        | 1.88%   |
| Intel Wireless 3165                                           | 19        | 1.88%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 18        | 1.78%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 16        | 1.58%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 15        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 14        | 1.39%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 13        | 1.29%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 13        | 1.29%   |
| Intel Comet Lake PCH CNVi WiFi                                | 13        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter               | 12        | 1.19%   |
| Realtek 802.11ac NIC                                          | 12        | 1.19%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller   | 11        | 1.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 11        | 1.09%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 11        | 1.09%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 10        | 0.99%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 9         | 0.89%   |
| Intel Wireless 3160                                           | 9         | 0.89%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                  | 9         | 0.89%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter    | 9         | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                 | 9         | 0.89%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 8         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 8         | 0.79%   |
| D-Link 802.11ac NIC                                           | 8         | 0.79%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 6         | 0.59%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                    | 6         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 581       | 60.02%  |
| Intel                         | 251       | 25.93%  |
| Qualcomm Atheros              | 38        | 3.93%   |
| ASIX Electronics              | 21        | 2.17%   |
| Broadcom                      | 19        | 1.96%   |
| DisplayLink                   | 7         | 0.72%   |
| Aquantia                      | 7         | 0.72%   |
| Lenovo                        | 6         | 0.62%   |
| Google                        | 4         | 0.41%   |
| Cypress Semiconductor         | 4         | 0.41%   |
| Apple                         | 4         | 0.41%   |
| Samsung Electronics           | 3         | 0.31%   |
| OPPO Electronics              | 3         | 0.31%   |
| Nvidia                        | 3         | 0.31%   |
| Xiaomi                        | 2         | 0.21%   |
| TP-Link                       | 2         | 0.21%   |
| ICS Advent                    | 2         | 0.21%   |
| D-Link                        | 2         | 0.21%   |
| OnePlus Technology (Shenzhen) | 1         | 0.1%    |
| NetGear                       | 1         | 0.1%    |
| Motorola PCS                  | 1         | 0.1%    |
| Microsoft                     | 1         | 0.1%    |
| Mellanox Technologies         | 1         | 0.1%    |
| MediaTek                      | 1         | 0.1%    |
| Marvell Technology Group      | 1         | 0.1%    |
| Hewlett-Packard               | 1         | 0.1%    |
| Broadcom Limited              | 1         | 0.1%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 442       | 44.65%  |
| Realtek RTL8125 2.5GbE Controller                                 | 60        | 6.06%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 40        | 4.04%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 38        | 3.84%   |
| Intel I211 Gigabit Network Connection                             | 38        | 3.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 24        | 2.42%   |
| Intel Ethernet Controller I225-V                                  | 19        | 1.92%   |
| Intel Ethernet Connection I217-LM                                 | 19        | 1.92%   |
| ASIX AX88179 Gigabit Ethernet                                     | 18        | 1.82%   |
| Intel Ethernet Connection (2) I219-V                              | 17        | 1.72%   |
| Intel Ethernet Connection (7) I219-V                              | 13        | 1.31%   |
| Intel Ethernet Connection (4) I219-LM                             | 12        | 1.21%   |
| Intel Ethernet Connection I218-LM                                 | 10        | 1.01%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 9         | 0.91%   |
| Intel Ethernet Connection (4) I219-V                              | 9         | 0.91%   |
| Intel Ethernet Connection I219-LM                                 | 8         | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 8         | 0.81%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 6         | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 6         | 0.61%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.61%   |
| Intel 82577LM Gigabit Network Connection                          | 6         | 0.61%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 5         | 0.51%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 5         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 5         | 0.51%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 4         | 0.4%    |
| Intel Ethernet Connection I217-V                                  | 4         | 0.4%    |
| Intel Ethernet Connection (3) I218-LM                             | 4         | 0.4%    |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.4%    |
| Intel 82567LM Gigabit Network Connection                          | 4         | 0.4%    |
| Cypress K38231_03                                                 | 4         | 0.4%    |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 4         | 0.4%    |
| Apple iBridge                                                     | 4         | 0.4%    |
| Realtek PCIe GbE Family Controller                                | 3         | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.3%    |
| OPPO 8                                                            | 3         | 0.3%    |
| Intel Ethernet Controller I226-V                                  | 3         | 0.3%    |
| Intel Ethernet Connection (6) I219-V                              | 3         | 0.3%    |
| Intel Ethernet Connection (6) I219-LM                             | 3         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                             | 3         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 938       | 50.84%  |
| Ethernet | 889       | 48.18%  |
| Modem    | 16        | 0.87%   |
| Unknown  | 2         | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 758       | 63.7%   |
| Ethernet | 432       | 36.3%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 597       | 53.4%   |
| 1     | 478       | 42.75%  |
| 3     | 34        | 3.04%   |
| 0     | 5         | 0.45%   |
| 4     | 4         | 0.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 867       | 76.46%  |
| Yes  | 267       | 23.54%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 478       | 51.79%  |
| Realtek Semiconductor           | 115       | 12.46%  |
| Qualcomm Atheros Communications | 49        | 5.31%   |
| Cambridge Silicon Radio         | 47        | 5.09%   |
| IMC Networks                    | 41        | 4.44%   |
| Foxconn / Hon Hai               | 34        | 3.68%   |
| Broadcom                        | 30        | 3.25%   |
| Lite-On Technology              | 27        | 2.93%   |
| Apple                           | 21        | 2.28%   |
| ASUSTek Computer                | 18        | 1.95%   |
| MediaTek                        | 15        | 1.63%   |
| Realtek                         | 9         | 0.98%   |
| TP-Link                         | 6         | 0.65%   |
| Toshiba                         | 5         | 0.54%   |
| USI                             | 4         | 0.43%   |
| Ralink                          | 4         | 0.43%   |
| Dell                            | 4         | 0.43%   |
| Marvell Semiconductor           | 3         | 0.33%   |
| HTC (High Tech Computer)        | 3         | 0.33%   |
| Hewlett-Packard                 | 3         | 0.33%   |
| Opticis                         | 2         | 0.22%   |
| Foxconn International           | 1         | 0.11%   |
| Edimax Technology               | 1         | 0.11%   |
| Dynex                           | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |
| Actions                         | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 153       | 16.52%  |
| Intel AX200 Bluetooth                               | 98        | 10.58%  |
| Realtek Bluetooth Radio                             | 84        | 9.07%   |
| Intel AX201 Bluetooth                               | 80        | 8.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 51        | 5.51%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 47        | 5.08%   |
| Intel AX210 Bluetooth                               | 33        | 3.56%   |
| Qualcomm Atheros  Bluetooth Device                  | 32        | 3.46%   |
| Intel Bluetooth Device                              | 28        | 3.02%   |
| Realtek  Bluetooth 4.2 Adapter                      | 19        | 2.05%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 19        | 2.05%   |
| IMC Networks Wireless_Device                        | 16        | 1.73%   |
| MediaTek Wireless_Device                            | 15        | 1.62%   |
| IMC Networks Bluetooth Radio                        | 15        | 1.62%   |
| Intel Wireless-AC 3168 Bluetooth                    | 13        | 1.4%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 12        | 1.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 11        | 1.19%   |
| Apple Bluetooth USB Host Controller                 | 11        | 1.19%   |
| Foxconn / Hon Hai Wireless_Device                   | 10        | 1.08%   |
| Realtek Bluetooth Radio                             | 9         | 0.97%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 8         | 0.86%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 7         | 0.76%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 7         | 0.76%   |
| TP-Link UB5A Adapter                                | 6         | 0.65%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 6         | 0.65%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 6         | 0.65%   |
| Foxconn / Hon Hai Bluetooth Device                  | 6         | 0.65%   |
| Lite-On Bluetooth Device                            | 5         | 0.54%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.54%   |
| IMC Networks Bluetooth Device                       | 5         | 0.54%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 5         | 0.54%   |
| Apple Bluetooth Host Controller                     | 5         | 0.54%   |
| USI Bluetooth Device                                | 4         | 0.43%   |
| Realtek RTL8821A Bluetooth                          | 4         | 0.43%   |
| Ralink RT3290 Bluetooth                             | 4         | 0.43%   |
| Lite-On Wireless_Device                             | 4         | 0.43%   |
| Broadcom BCM2045B (BDC-2.1)                         | 4         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 3         | 0.32%   |
| Marvell Bluetooth and Wireless LAN Composite        | 3         | 0.32%   |
| Lite-On Bluetooth Radio                             | 3         | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 688       | 38.39%  |
| AMD                                             | 455       | 25.39%  |
| Nvidia                                          | 316       | 17.63%  |
| C-Media Electronics                             | 37        | 2.06%   |
| Logitech                                        | 26        | 1.45%   |
| SteelSeries ApS                                 | 20        | 1.12%   |
| Texas Instruments                               | 19        | 1.06%   |
| Kingston Technology                             | 17        | 0.95%   |
| Creative Technology                             | 12        | 0.67%   |
| Creative Labs                                   | 12        | 0.67%   |
| JMTek                                           | 11        | 0.61%   |
| Focusrite-Novation                              | 10        | 0.56%   |
| Sony                                            | 8         | 0.45%   |
| Razer USA                                       | 8         | 0.45%   |
| Corsair                                         | 8         | 0.45%   |
| Realtek Semiconductor                           | 7         | 0.39%   |
| Lenovo                                          | 7         | 0.39%   |
| Blue Microphones                                | 7         | 0.39%   |
| RODE Microphones                                | 6         | 0.33%   |
| Micro Star International                        | 6         | 0.33%   |
| KORG                                            | 6         | 0.33%   |
| Samson Technologies                             | 5         | 0.28%   |
| NAD Electronics                                 | 5         | 0.28%   |
| Generalplus Technology                          | 5         | 0.28%   |
| Apple                                           | 5         | 0.28%   |
| AKAI                                            | 5         | 0.28%   |
| XMOS                                            | 4         | 0.22%   |
| Valve Software                                  | 4         | 0.22%   |
| KTMicro                                         | 3         | 0.17%   |
| Hewlett-Packard                                 | 3         | 0.17%   |
| GYROCOM C&C                                     | 3         | 0.17%   |
| FiiO Electronics Technology                     | 3         | 0.17%   |
| ASUSTek Computer                                | 3         | 0.17%   |
| Thesycon Systemsoftware & Consulting            | 2         | 0.11%   |
| Sennheiser Communications                       | 2         | 0.11%   |
| M-Audio                                         | 2         | 0.11%   |
| Licensed by Sony Computer Entertainment America | 2         | 0.11%   |
| Giga-Byte Technology                            | 2         | 0.11%   |
| Elgato Systems                                  | 2         | 0.11%   |
| Cambridge Silicon Radio                         | 2         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 230       | 10.37%  |
| AMD Renoir Radeon High Definition Audio Controller                         | 131       | 5.9%    |
| Intel Sunrise Point-LP HD Audio                                            | 110       | 4.96%   |
| AMD Starship/Matisse HD Audio Controller                                   | 103       | 4.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 51        | 2.3%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 48        | 2.16%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 46        | 2.07%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 2.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 44        | 1.98%   |
| Intel Cannon Lake PCH cAVS                                                 | 43        | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 38        | 1.71%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 37        | 1.67%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 36        | 1.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 31        | 1.4%    |
| Nvidia GA104 High Definition Audio Controller                              | 29        | 1.31%   |
| Intel 8 Series HD Audio Controller                                         | 29        | 1.31%   |
| Nvidia TU106 High Definition Audio Controller                              | 28        | 1.26%   |
| Nvidia GP107GL High Definition Audio Controller                            | 28        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 28        | 1.26%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 28        | 1.26%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 28        | 1.26%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 25        | 1.13%   |
| Nvidia GP104 High Definition Audio Controller                              | 24        | 1.08%   |
| Nvidia GA106 High Definition Audio Controller                              | 24        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 24        | 1.08%   |
| Intel Broadwell-U Audio Controller                                         | 24        | 1.08%   |
| AMD Navi 10 HDMI Audio                                                     | 24        | 1.08%   |
| Nvidia TU116 High Definition Audio Controller                              | 23        | 1.04%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 23        | 1.04%   |
| Intel 200 Series PCH HD Audio                                              | 21        | 0.95%   |
| Intel Comet Lake PCH cAVS                                                  | 19        | 0.86%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 19        | 0.86%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 18        | 0.81%   |
| Nvidia GP106 High Definition Audio Controller                              | 17        | 0.77%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16        | 0.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 15        | 0.68%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 15        | 0.68%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 15        | 0.68%   |
| Intel CM238 HD Audio Controller                                            | 14        | 0.63%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 14        | 0.63%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 263       | 26.62%  |
| SK hynix            | 173       | 17.51%  |
| Micron Technology   | 112       | 11.34%  |
| Kingston            | 86        | 8.7%    |
| Corsair             | 70        | 7.09%   |
| G.Skill             | 67        | 6.78%   |
| Crucial             | 59        | 5.97%   |
| Unknown             | 36        | 3.64%   |
| Ramaxel Technology  | 16        | 1.62%   |
| A-DATA Technology   | 15        | 1.52%   |
| Team                | 12        | 1.21%   |
| Patriot             | 12        | 1.21%   |
| Elpida              | 8         | 0.81%   |
| Unknown (ABCD)      | 7         | 0.71%   |
| Unknown             | 7         | 0.71%   |
| Nanya Technology    | 4         | 0.4%    |
| Kllisre             | 3         | 0.3%    |
| GOODRAM             | 3         | 0.3%    |
| Transcend           | 2         | 0.2%    |
| Teikon              | 2         | 0.2%    |
| Shenzhen Mic        | 2         | 0.2%    |
| Hikvision           | 2         | 0.2%    |
| Golden Empire       | 2         | 0.2%    |
| Apacer              | 2         | 0.2%    |
| Wilk                | 1         | 0.1%    |
| V-GeN               | 1         | 0.1%    |
| Unknown (0x5846)    | 1         | 0.1%    |
| Toshiba             | 1         | 0.1%    |
| Strontium           | 1         | 0.1%    |
| Smart Brazil        | 1         | 0.1%    |
| Smart               | 1         | 0.1%    |
| Silicon Power       | 1         | 0.1%    |
| Sesame              | 1         | 0.1%    |
| Qimonda             | 1         | 0.1%    |
| PNY                 | 1         | 0.1%    |
| Neo Forza           | 1         | 0.1%    |
| MAXSUN              | 1         | 0.1%    |
| Magnum Tech         | 1         | 0.1%    |
| KLEVV               | 1         | 0.1%    |
| Kingmax             | 1         | 0.1%    |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 20        | 1.88%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 16        | 1.5%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 14        | 1.31%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 13        | 1.22%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 12        | 1.13%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 11        | 1.03%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 10        | 0.94%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 10        | 0.94%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 9         | 0.85%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 9         | 0.85%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.75%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 7         | 0.66%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.66%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 7         | 0.66%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 7         | 0.66%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 7         | 0.66%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s             | 7         | 0.66%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 7         | 0.66%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 7         | 0.66%   |
| Unknown                                                          | 7         | 0.66%   |
| Unknown RAM Module 8GB SODIMM DDR3 1600MT/s                      | 6         | 0.56%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.56%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 6         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 6         | 0.56%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3600MT/s             | 6         | 0.56%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 5         | 0.47%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 5         | 0.47%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.47%   |
| Samsung RAM UBE3D4AA-MGCR 2048MB Row Of Chips LPDDR4 4267MT/s    | 5         | 0.47%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 0.47%   |
| Samsung RAM K4UBE3D4AA-MGCL 8GB Row Of Chips LPDDR4 4267MT/s     | 5         | 0.47%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB Row Of Chips DDR4 3200MT/s      | 5         | 0.47%   |
| G.Skill RAM F4-3600C16-16GTZNC 16GB DIMM DDR4 3600MT/s           | 5         | 0.47%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 4         | 0.38%   |
| SK hynix RAM HMAB2GS6AMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 4         | 0.38%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 4         | 0.38%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.38%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 526       | 61.66%  |
| DDR3    | 174       | 20.4%   |
| LPDDR4  | 46        | 5.39%   |
| LPDDR3  | 29        | 3.4%    |
| DDR5    | 29        | 3.4%    |
| LPDDR5  | 18        | 2.11%   |
| DDR2    | 14        | 1.64%   |
| SDRAM   | 9         | 1.06%   |
| Unknown | 7         | 0.82%   |
| DDR     | 1         | 0.12%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 498       | 58.45%  |
| DIMM         | 242       | 28.4%   |
| Row Of Chips | 99        | 11.62%  |
| Chip         | 7         | 0.82%   |
| Unknown      | 4         | 0.47%   |
| RIMM         | 1         | 0.12%   |
| FB-DIMM      | 1         | 0.12%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 453       | 49.08%  |
| 4096  | 205       | 22.21%  |
| 16384 | 163       | 17.66%  |
| 2048  | 52        | 5.63%   |
| 32768 | 42        | 4.55%   |
| 1024  | 7         | 0.76%   |
| 49152 | 1         | 0.11%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 234       | 25.41%  |
| 2667    | 147       | 15.96%  |
| 1600    | 135       | 14.66%  |
| 2400    | 52        | 5.65%   |
| 3600    | 50        | 5.43%   |
| 2133    | 39        | 4.23%   |
| 3266    | 25        | 2.71%   |
| 1333    | 24        | 2.61%   |
| 4800    | 22        | 2.39%   |
| 1867    | 22        | 2.39%   |
| 6400    | 19        | 2.06%   |
| 4267    | 17        | 1.85%   |
| 1334    | 11        | 1.19%   |
| 3733    | 9         | 0.98%   |
| 3533    | 8         | 0.87%   |
| 3400    | 8         | 0.87%   |
| 800     | 7         | 0.76%   |
| 3866    | 6         | 0.65%   |
| 667     | 6         | 0.65%   |
| Unknown | 6         | 0.65%   |
| 3800    | 5         | 0.54%   |
| 3000    | 5         | 0.54%   |
| 1800    | 5         | 0.54%   |
| 4266    | 4         | 0.43%   |
| 1067    | 4         | 0.43%   |
| 6000    | 3         | 0.33%   |
| 5600    | 3         | 0.33%   |
| 2933    | 3         | 0.33%   |
| 2666    | 3         | 0.33%   |
| 2048    | 3         | 0.33%   |
| 1066    | 3         | 0.33%   |
| 3534    | 2         | 0.22%   |
| 3500    | 2         | 0.22%   |
| 3466    | 2         | 0.22%   |
| 2800    | 2         | 0.22%   |
| 2733    | 2         | 0.22%   |
| 1648    | 2         | 0.22%   |
| 65535   | 1         | 0.11%   |
| 49926   | 1         | 0.11%   |
| 8400    | 1         | 0.11%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 6         | 31.58%  |
| Hewlett-Packard     | 5         | 26.32%  |
| Xerox               | 2         | 10.53%  |
| Prolific Technology | 2         | 10.53%  |
| Canon               | 2         | 10.53%  |
| Seiko Epson         | 1         | 5.26%   |
| Pantum              | 1         | 5.26%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                         | Computers | Percent |
|-------------------------------|-----------|---------|
| Xerox B210                    | 2         | 10.53%  |
| Prolific PL2305 Parallel Port | 2         | 10.53%  |
| Seiko Epson WF-2010 Series    | 1         | 5.26%   |
| Pantum P2500W series          | 1         | 5.26%   |
| HP OfficeJet Pro 8020 series  | 1         | 5.26%   |
| HP ENVY 5540 series           | 1         | 5.26%   |
| HP ENVY 5000 series           | 1         | 5.26%   |
| HP DeskJet 2130 series        | 1         | 5.26%   |
| HP ColorLaserJet M253-M254    | 1         | 5.26%   |
| Canon PIXMA MG2500 Series     | 1         | 5.26%   |
| Canon MF260 II Series         | 1         | 5.26%   |
| Brother Printer               | 1         | 5.26%   |
| Brother MFC-L2710DW series    | 1         | 5.26%   |
| Brother MFC-J4535DW           | 1         | 5.26%   |
| Brother HL-2130 series        | 1         | 5.26%   |
| Brother DCP-9020CDW           | 1         | 5.26%   |
| Brother DCP-9015CDW           | 1         | 5.26%   |

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
| Chicony Electronics                    | 144       | 18%     |
| IMC Networks                           | 106       | 13.25%  |
| Logitech                               | 66        | 8.25%   |
| Microdia                               | 55        | 6.88%   |
| Bison Electronics                      | 52        | 6.5%    |
| Quanta                                 | 40        | 5%      |
| Realtek Semiconductor                  | 36        | 4.5%    |
| Sunplus Innovation Technology          | 34        | 4.25%   |
| Cheng Uei Precision Industry (Foxlink) | 34        | 4.25%   |
| Apple                                  | 30        | 3.75%   |
| Syntek                                 | 27        | 3.38%   |
| Lite-On Technology                     | 23        | 2.88%   |
| Luxvisions Innotech Limited            | 22        | 2.75%   |
| Acer                                   | 17        | 2.13%   |
| Sonix Technology                       | 11        | 1.38%   |
| Microsoft                              | 11        | 1.38%   |
| Suyin                                  | 7         | 0.88%   |
| Samsung Electronics                    | 6         | 0.75%   |
| MacroSilicon                           | 5         | 0.63%   |
| Hewlett-Packard                        | 5         | 0.63%   |
| Valve Software                         | 4         | 0.5%    |
| Silicon Motion                         | 4         | 0.5%    |
| Shenzhen Kingcome Optoelectronic       | 4         | 0.5%    |
| Lenovo                                 | 4         | 0.5%    |
| Google                                 | 4         | 0.5%    |
| Alcor Micro                            | 4         | 0.5%    |
| Primax Electronics                     | 3         | 0.38%   |
| GEMBIRD                                | 3         | 0.38%   |
| ShineTech                              | 2         | 0.25%   |
| Ricoh                                  | 2         | 0.25%   |
| LG Electronics                         | 2         | 0.25%   |
| KYE Systems (Mouse Systems)            | 2         | 0.25%   |
| Intel                                  | 2         | 0.25%   |
| Huawei Technologies                    | 2         | 0.25%   |
| Generalplus Technology                 | 2         | 0.25%   |
| Y Media                                | 1         | 0.13%   |
| Xiaomi                                 | 1         | 0.13%   |
| WCM_USB                                | 1         | 0.13%   |
| Trust                                  | 1         | 0.13%   |
| Tripath Technology                     | 1         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 47        | 5.83%   |
| IMC Networks Integrated Camera                               | 42        | 5.21%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 37        | 4.59%   |
| Microdia Integrated_Webcam_HD                                | 21        | 2.61%   |
| Logitech HD Pro Webcam C920                                  | 21        | 2.61%   |
| Bison Integrated Camera                                      | 19        | 2.36%   |
| Syntek Integrated Camera                                     | 17        | 2.11%   |
| Chicony HD WebCam                                            | 16        | 1.99%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X/XR                           | 15        | 1.86%   |
| Realtek Integrated_Webcam_HD                                 | 13        | 1.61%   |
| Bison HD Webcam                                              | 13        | 1.61%   |
| Logitech Webcam C270                                         | 11        | 1.36%   |
| Sunplus Integrated_Webcam_HD                                 | 10        | 1.24%   |
| Apple FaceTime HD Camera (Built-in)                          | 10        | 1.24%   |
| Quanta USB2.0 HD UVC WebCam                                  | 8         | 0.99%   |
| Microdia Webcam Vitade AF                                    | 8         | 0.99%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera         | 8         | 0.99%   |
| Sunplus HD WebCam                                            | 7         | 0.87%   |
| Sonix USB2.0 HD UVC WebCam                                   | 7         | 0.87%   |
| Microdia USB 2.0 Camera                                      | 7         | 0.87%   |
| Logitech C922 Pro Stream Webcam                              | 7         | 0.87%   |
| Lite-On Integrated Camera                                    | 7         | 0.87%   |
| Chicony HP Wide Vision HD Camera                             | 7         | 0.87%   |
| Acer Integrated Camera                                       | 7         | 0.87%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 6         | 0.74%   |
| Quanta HP TrueVision HD Camera                               | 6         | 0.74%   |
| Quanta HP HD Camera                                          | 6         | 0.74%   |
| Microdia Integrated Webcam                                   | 6         | 0.74%   |
| Chicony USB2.0 HD UVC WebCam                                 | 6         | 0.74%   |
| Chicony HD User Facing                                       | 6         | 0.74%   |
| Syntek EasyCamera                                            | 5         | 0.62%   |
| MacroSilicon USB3. 0 capture                                 | 5         | 0.62%   |
| Lite-On HP Webcam                                            | 5         | 0.62%   |
| IMC Networks ov9734_azurewave_camera                         | 5         | 0.62%   |
| Chicony VGA WebCam                                           | 5         | 0.62%   |
| Chicony USB2.0 VGA UVC WebCam                                | 5         | 0.62%   |
| Chicony HP TrueVision HD Camera                              | 5         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 5         | 0.62%   |
| Cheng Uei Precision Industry (Foxlink) HD Camera             | 5         | 0.62%   |
| Acer BisonCam,NB Pro                                         | 5         | 0.62%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 54        | 36.49%  |
| Validity Sensors                   | 35        | 23.65%  |
| Shenzhen Goodix Technology         | 26        | 17.57%  |
| Elan Microelectronics              | 17        | 11.49%  |
| LighTuning Technology              | 6         | 4.05%   |
| Upek                               | 3         | 2.03%   |
| Realtek USB2.0 Finger Print Bridge | 3         | 2.03%   |
| Samsung Electronics                | 2         | 1.35%   |
| AuthenTec                          | 2         | 1.35%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 9.46%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 13        | 8.78%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 8.11%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 9         | 6.08%   |
| Validity Sensors Synaptics WBDI                                            | 8         | 5.41%   |
| Elan ELAN:ARM-M4                                                           | 8         | 5.41%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 7         | 4.73%   |
| Synaptics  WBDI                                                            | 7         | 4.73%   |
| Elan ELAN:Fingerprint                                                      | 7         | 4.73%   |
| Synaptics WBDI                                                             | 6         | 4.05%   |
| Synaptics UWP WBDI                                                         | 5         | 3.38%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 3.38%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 4         | 2.7%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 4         | 2.7%    |
| Validity Sensors VFS491                                                    | 3         | 2.03%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 2.03%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 3         | 2.03%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 2.03%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 3         | 2.03%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 3         | 2.03%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 1.35%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.35%   |
| Synaptics UWP WBDI Device                                                  | 2         | 1.35%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 2         | 1.35%   |
| Elan WBF Fingerprint Sensor                                                | 2         | 1.35%   |
| Unknown                                                                    | 2         | 1.35%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 0.68%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.68%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.68%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 0.68%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 1         | 0.68%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 0.68%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 0.68%   |
| AuthenTec AES2810                                                          | 1         | 0.68%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.68%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor      | Computers | Percent |
|-------------|-----------|---------|
| Broadcom    | 23        | 48.94%  |
| Alcor Micro | 16        | 34.04%  |
| Lenovo      | 3         | 6.38%   |
| Upek        | 2         | 4.26%   |
| O2 Micro    | 2         | 4.26%   |
| HID Global  | 1         | 2.13%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 15        | 31.25%  |
| Broadcom BCM5880 Secure Applications Processor                               | 10        | 20.83%  |
| Broadcom 5880                                                                | 6         | 12.5%   |
| Broadcom 58200                                                               | 5         | 10.42%  |
| Lenovo Integrated Smart Card Reader                                          | 3         | 6.25%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6.25%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4.17%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 4.17%   |
| HID Global USB Reader V3                                                     | 1         | 2.08%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 2.08%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 770       | 67.37%  |
| 1     | 312       | 27.3%   |
| 2     | 58        | 5.07%   |
| 3     | 2         | 0.17%   |
| 4     | 1         | 0.09%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 148       | 35.41%  |
| Net/ethernet             | 49        | 11.72%  |
| Multimedia controller    | 48        | 11.48%  |
| Chipcard                 | 45        | 10.77%  |
| Graphics card            | 42        | 10.05%  |
| Net/wireless             | 32        | 7.66%   |
| Camera                   | 18        | 4.31%   |
| Bluetooth                | 12        | 2.87%   |
| Network                  | 7         | 1.67%   |
| Unassigned class         | 4         | 0.96%   |
| Storage                  | 3         | 0.72%   |
| Dvb card                 | 3         | 0.72%   |
| Sound                    | 2         | 0.48%   |
| Storage/raid             | 1         | 0.24%   |
| Storage/nvme             | 1         | 0.24%   |
| Modem                    | 1         | 0.24%   |
| Communication controller | 1         | 0.24%   |
| Card reader              | 1         | 0.24%   |


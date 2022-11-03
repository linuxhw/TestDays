Linux in Spain - Tested Hardware & Statistics (Notebooks)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Spain.

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

Total: 3405

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | ProBook 450 G8 Notebook ... | [44e281e52c](https://linux-hardware.org/?probe=44e281e52c) | Nov 02, 2022 |
| Valve         | Jupiter                     | [99521b7f24](https://linux-hardware.org/?probe=99521b7f24) | Nov 02, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [690e088c8e](https://linux-hardware.org/?probe=690e088c8e) | Nov 02, 2022 |
| Samsung       | 305V4A/305V5A               | [5df933ddda](https://linux-hardware.org/?probe=5df933ddda) | Nov 01, 2022 |
| HP            | ProBook 650 G1              | [85f1aa7b6d](https://linux-hardware.org/?probe=85f1aa7b6d) | Nov 01, 2022 |
| Lenovo        | ThinkPad T480 20L6S3H108    | [1ed803ae94](https://linux-hardware.org/?probe=1ed803ae94) | Nov 01, 2022 |
| Toshiba       | Satellite L50-C             | [b3e0ff9849](https://linux-hardware.org/?probe=b3e0ff9849) | Nov 01, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [3db734a533](https://linux-hardware.org/?probe=3db734a533) | Nov 01, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [dc7fa9ac1e](https://linux-hardware.org/?probe=dc7fa9ac1e) | Oct 31, 2022 |
| Lenovo        | ThinkPad Edge 25453BG       | [ba67d47c9c](https://linux-hardware.org/?probe=ba67d47c9c) | Oct 31, 2022 |
| MSI           | Pulse GL76 12UEK            | [76a2d8c304](https://linux-hardware.org/?probe=76a2d8c304) | Oct 31, 2022 |
| HP            | 250 G7 Notebook PC          | [7433eae90a](https://linux-hardware.org/?probe=7433eae90a) | Oct 31, 2022 |
| Panasonic     | CF-19RDRCHH7                | [99e94a7708](https://linux-hardware.org/?probe=99e94a7708) | Oct 31, 2022 |
| Fujitsu       | LIFEBOOK T904               | [4591ea2ad6](https://linux-hardware.org/?probe=4591ea2ad6) | Oct 30, 2022 |
| Fujitsu       | LIFEBOOK T904               | [5dd8b365d6](https://linux-hardware.org/?probe=5dd8b365d6) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [6bf9e760ca](https://linux-hardware.org/?probe=6bf9e760ca) | Oct 30, 2022 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [1ca9fe180c](https://linux-hardware.org/?probe=1ca9fe180c) | Oct 30, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [8dfb7265a9](https://linux-hardware.org/?probe=8dfb7265a9) | Oct 30, 2022 |
| Toshiba       | Satellite C855-1T5          | [c07f6a167a](https://linux-hardware.org/?probe=c07f6a167a) | Oct 30, 2022 |
| Notebook      | W230SD                      | [76ae019222](https://linux-hardware.org/?probe=76ae019222) | Oct 29, 2022 |
| Dell          | XPS 13 9370                 | [7bf374b38a](https://linux-hardware.org/?probe=7bf374b38a) | Oct 29, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b8cfddfcbf](https://linux-hardware.org/?probe=b8cfddfcbf) | Oct 29, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [8440ee2b2a](https://linux-hardware.org/?probe=8440ee2b2a) | Oct 29, 2022 |
| Apple         | MacBookPro16,1              | [eba036175b](https://linux-hardware.org/?probe=eba036175b) | Oct 28, 2022 |
| ASUSTek       | ZenBook UX431FLC_UX431FL    | [e34c4fde2c](https://linux-hardware.org/?probe=e34c4fde2c) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [8429395d7d](https://linux-hardware.org/?probe=8429395d7d) | Oct 28, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [366e5edec9](https://linux-hardware.org/?probe=366e5edec9) | Oct 28, 2022 |
| HP            | EliteBook 820 G2            | [7056cf1574](https://linux-hardware.org/?probe=7056cf1574) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [9986b4ff02](https://linux-hardware.org/?probe=9986b4ff02) | Oct 27, 2022 |
| MSI           | GE66 Raider 10UE            | [334d883dd3](https://linux-hardware.org/?probe=334d883dd3) | Oct 27, 2022 |
| Acer          | Aspire A315-21              | [14f5f5ceeb](https://linux-hardware.org/?probe=14f5f5ceeb) | Oct 26, 2022 |
| Lenovo        | G500 20236                  | [b5508a855e](https://linux-hardware.org/?probe=b5508a855e) | Oct 26, 2022 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | [56c91f99e7](https://linux-hardware.org/?probe=56c91f99e7) | Oct 26, 2022 |
| Dell          | Latitude E6440              | [81a4c0f5d5](https://linux-hardware.org/?probe=81a4c0f5d5) | Oct 26, 2022 |
| Acer          | Aspire ES1-511              | [0db2597f65](https://linux-hardware.org/?probe=0db2597f65) | Oct 26, 2022 |
| Apple         | MacBook5,1                  | [a7fa475b56](https://linux-hardware.org/?probe=a7fa475b56) | Oct 25, 2022 |
| ALURIN        | PR1-M146                    | [af492a458f](https://linux-hardware.org/?probe=af492a458f) | Oct 25, 2022 |
| Acer          | Aspire ES1-571              | [f9f7926da2](https://linux-hardware.org/?probe=f9f7926da2) | Oct 25, 2022 |
| Lenovo        | ThinkPad T490s 20NYS6FL0... | [ef0cad4118](https://linux-hardware.org/?probe=ef0cad4118) | Oct 25, 2022 |
| ASUSTek       | X550EA                      | [6a7b7a70a5](https://linux-hardware.org/?probe=6a7b7a70a5) | Oct 23, 2022 |
| ASUSTek       | X550EA                      | [e2c2ac571f](https://linux-hardware.org/?probe=e2c2ac571f) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2991b1a2cf](https://linux-hardware.org/?probe=2991b1a2cf) | Oct 23, 2022 |
| MSI           | Modern 14 C12M              | [2015c6f7fc](https://linux-hardware.org/?probe=2015c6f7fc) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [55a5d78e1c](https://linux-hardware.org/?probe=55a5d78e1c) | Oct 22, 2022 |
| HUAWEI        | RLEF-XX                     | [5bebcbd76d](https://linux-hardware.org/?probe=5bebcbd76d) | Oct 22, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [d806b92948](https://linux-hardware.org/?probe=d806b92948) | Oct 22, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1227d6561e](https://linux-hardware.org/?probe=1227d6561e) | Oct 22, 2022 |
| HP            | 15                          | [937cf874b0](https://linux-hardware.org/?probe=937cf874b0) | Oct 21, 2022 |
| Toshiba       | Satellite P50-B-103         | [011581fdbf](https://linux-hardware.org/?probe=011581fdbf) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [85a58721ed](https://linux-hardware.org/?probe=85a58721ed) | Oct 21, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [1e4d67ad76](https://linux-hardware.org/?probe=1e4d67ad76) | Oct 21, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | [3dd060400b](https://linux-hardware.org/?probe=3dd060400b) | Oct 21, 2022 |
| ASUSTek       | TUF Gaming FX505GT_FX505... | [1a99b642cc](https://linux-hardware.org/?probe=1a99b642cc) | Oct 20, 2022 |
| ASUSTek       | K54C                        | [124cad3faf](https://linux-hardware.org/?probe=124cad3faf) | Oct 20, 2022 |
| Valve         | Jupiter                     | [982d4175a3](https://linux-hardware.org/?probe=982d4175a3) | Oct 19, 2022 |
| MSI           | Modern 14 C12M              | [33c0e4861e](https://linux-hardware.org/?probe=33c0e4861e) | Oct 18, 2022 |
| HP            | Pavilion Notebook           | [462a0f1d13](https://linux-hardware.org/?probe=462a0f1d13) | Oct 18, 2022 |
| Chuwi         | HeroBook Air                | [21c0a75b93](https://linux-hardware.org/?probe=21c0a75b93) | Oct 17, 2022 |
| Dell          | Latitude E6330              | [d4d6ca7ae9](https://linux-hardware.org/?probe=d4d6ca7ae9) | Oct 17, 2022 |
| SLIMBOOK      | TITAN                       | [87177b2371](https://linux-hardware.org/?probe=87177b2371) | Oct 17, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [7b5da7d635](https://linux-hardware.org/?probe=7b5da7d635) | Oct 17, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c1bad579af](https://linux-hardware.org/?probe=c1bad579af) | Oct 17, 2022 |
| MSI           | Stealth GS66 12UGS          | [10f52ac957](https://linux-hardware.org/?probe=10f52ac957) | Oct 16, 2022 |
| ASUSTek       | ROG Strix G512LV_G512LV     | [53a9eb1420](https://linux-hardware.org/?probe=53a9eb1420) | Oct 16, 2022 |
| Notebook      | N2x0WU                      | [bc1072e527](https://linux-hardware.org/?probe=bc1072e527) | Oct 16, 2022 |
| ASUSTek       | X540LA                      | [1680f919c8](https://linux-hardware.org/?probe=1680f919c8) | Oct 15, 2022 |
| Google        | Liara                       | [8e2b131f8f](https://linux-hardware.org/?probe=8e2b131f8f) | Oct 14, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [4e29271bab](https://linux-hardware.org/?probe=4e29271bab) | Oct 14, 2022 |
| Qilive        | QW20141BSP                  | [a497e419fe](https://linux-hardware.org/?probe=a497e419fe) | Oct 13, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [0ce5415fa5](https://linux-hardware.org/?probe=0ce5415fa5) | Oct 13, 2022 |
| VANT          | MOOVE3-15                   | [ed3f1f2728](https://linux-hardware.org/?probe=ed3f1f2728) | Oct 13, 2022 |
| HP            | Laptop 17-cn2xxx            | [55bdfc4aef](https://linux-hardware.org/?probe=55bdfc4aef) | Oct 11, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [3e43886af3](https://linux-hardware.org/?probe=3e43886af3) | Oct 11, 2022 |
| Dell          | Vostro 5490                 | [8263bf7d5b](https://linux-hardware.org/?probe=8263bf7d5b) | Oct 11, 2022 |
| Dell          | Latitude E7240              | [3f9f9c38d1](https://linux-hardware.org/?probe=3f9f9c38d1) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [a0833e04a4](https://linux-hardware.org/?probe=a0833e04a4) | Oct 10, 2022 |
| Fujitsu       | LIFEBOOK AH532              | [dc29e6568f](https://linux-hardware.org/?probe=dc29e6568f) | Oct 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [6ccdbecf19](https://linux-hardware.org/?probe=6ccdbecf19) | Oct 10, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [71ef13e7f5](https://linux-hardware.org/?probe=71ef13e7f5) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [b188c7c0dc](https://linux-hardware.org/?probe=b188c7c0dc) | Oct 09, 2022 |
| ASUSTek       | K55VM                       | [d17d1273de](https://linux-hardware.org/?probe=d17d1273de) | Oct 09, 2022 |
| Chuwi         | HeroBook Air                | [4b263aaaae](https://linux-hardware.org/?probe=4b263aaaae) | Oct 09, 2022 |
| Notebook      | W65_W67RB                   | [dc57cb32d4](https://linux-hardware.org/?probe=dc57cb32d4) | Oct 07, 2022 |
| HP            | Victus by Laptop 16-e1xx... | [e2b4876c6e](https://linux-hardware.org/?probe=e2b4876c6e) | Oct 07, 2022 |
| HUAWEI        | RLEF-XX                     | [81f1574f73](https://linux-hardware.org/?probe=81f1574f73) | Oct 07, 2022 |
| HUAWEI        | NBLK-WAX9X                  | [84aa1dcbb2](https://linux-hardware.org/?probe=84aa1dcbb2) | Oct 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | [3ade8f820b](https://linux-hardware.org/?probe=3ade8f820b) | Oct 07, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | [c3ecfbe57b](https://linux-hardware.org/?probe=c3ecfbe57b) | Oct 07, 2022 |
| Toshiba       | Satellite R830              | [0a5299f7e0](https://linux-hardware.org/?probe=0a5299f7e0) | Oct 06, 2022 |
| MSI           | Creator Z16 A11UE           | [ad24aa79d7](https://linux-hardware.org/?probe=ad24aa79d7) | Oct 06, 2022 |
| Acer          | Aspire E1-522               | [769baa3828](https://linux-hardware.org/?probe=769baa3828) | Oct 05, 2022 |
| Valve         | Jupiter                     | [471bd7e244](https://linux-hardware.org/?probe=471bd7e244) | Oct 05, 2022 |
| Toshiba       | Satellite L10W-B-101        | [403446f5ce](https://linux-hardware.org/?probe=403446f5ce) | Oct 05, 2022 |
| MSI           | Raider GE76 12UGS           | [4586e7ece8](https://linux-hardware.org/?probe=4586e7ece8) | Oct 05, 2022 |
| HP            | Pavilion Notebook           | [17c8e22c3b](https://linux-hardware.org/?probe=17c8e22c3b) | Oct 05, 2022 |
| Acer          | Aspire E1-571               | [602710e8d3](https://linux-hardware.org/?probe=602710e8d3) | Oct 04, 2022 |
| HP            | Notebook                    | [58dd536d7d](https://linux-hardware.org/?probe=58dd536d7d) | Oct 04, 2022 |
| Acer          | Extensa 5230                | [8154485976](https://linux-hardware.org/?probe=8154485976) | Oct 04, 2022 |
| Acer          | Aspire 5253G                | [6bd00aec7a](https://linux-hardware.org/?probe=6bd00aec7a) | Oct 04, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [50d641ecf9](https://linux-hardware.org/?probe=50d641ecf9) | Oct 03, 2022 |
| Lenovo        | ThinkPad T470 20HES2SH2B    | [8d405f5135](https://linux-hardware.org/?probe=8d405f5135) | Oct 02, 2022 |
| Samsung       | N248P/N143P                 | [56e4d025af](https://linux-hardware.org/?probe=56e4d025af) | Oct 02, 2022 |
| Chuwi         | HeroBook Air                | [8de9e9df4a](https://linux-hardware.org/?probe=8de9e9df4a) | Oct 01, 2022 |
| HP            | Laptop 15s-eq1xxx           | [a4252ba03a](https://linux-hardware.org/?probe=a4252ba03a) | Oct 01, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [f50a823779](https://linux-hardware.org/?probe=f50a823779) | Oct 01, 2022 |
| Sony          | VPCEH2D0E                   | [a08d0148e2](https://linux-hardware.org/?probe=a08d0148e2) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [9fd2d2169a](https://linux-hardware.org/?probe=9fd2d2169a) | Sep 30, 2022 |
| HP            | Pavilion dv5                | [1c42236e47](https://linux-hardware.org/?probe=1c42236e47) | Sep 30, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [85b6d03edb](https://linux-hardware.org/?probe=85b6d03edb) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [565b94d7f4](https://linux-hardware.org/?probe=565b94d7f4) | Sep 29, 2022 |
| HP            | Compaq 6730s                | [62fc1b721e](https://linux-hardware.org/?probe=62fc1b721e) | Sep 29, 2022 |
| Valve         | Jupiter                     | [9de5371096](https://linux-hardware.org/?probe=9de5371096) | Sep 28, 2022 |
| HP            | 250 G7 Notebook PC          | [6ad96a2beb](https://linux-hardware.org/?probe=6ad96a2beb) | Sep 28, 2022 |
| Lenovo        | ThinkPad T440s 20ARS06C0... | [a5aa60c709](https://linux-hardware.org/?probe=a5aa60c709) | Sep 28, 2022 |
| Valve         | Jupiter                     | [4c7799c515](https://linux-hardware.org/?probe=4c7799c515) | Sep 28, 2022 |
| Chuwi         | HeroBook Air                | [c31e327867](https://linux-hardware.org/?probe=c31e327867) | Sep 27, 2022 |
| Apple         | MacBookAir6,2               | [8c4c7f3dc1](https://linux-hardware.org/?probe=8c4c7f3dc1) | Sep 27, 2022 |
| Fujitsu       | LIFEBOOK E548               | [bf70c9dd7b](https://linux-hardware.org/?probe=bf70c9dd7b) | Sep 27, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [e39766ed4d](https://linux-hardware.org/?probe=e39766ed4d) | Sep 26, 2022 |
| Lenovo        | G50-70 20351                | [77c0454f45](https://linux-hardware.org/?probe=77c0454f45) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [f3c74059d5](https://linux-hardware.org/?probe=f3c74059d5) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [ac296ea23b](https://linux-hardware.org/?probe=ac296ea23b) | Sep 26, 2022 |
| Dell          | XPS 13 7390                 | [cfebe9461d](https://linux-hardware.org/?probe=cfebe9461d) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [f4ea1372b7](https://linux-hardware.org/?probe=f4ea1372b7) | Sep 26, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [dc6d36a0eb](https://linux-hardware.org/?probe=dc6d36a0eb) | Sep 26, 2022 |
| HP            | 250 G8 Notebook PC          | [ae83bec6ad](https://linux-hardware.org/?probe=ae83bec6ad) | Sep 26, 2022 |
| MSI           | Alpha 15 A4DEK              | [d2e3e7736c](https://linux-hardware.org/?probe=d2e3e7736c) | Sep 26, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | [6527be1bb2](https://linux-hardware.org/?probe=6527be1bb2) | Sep 26, 2022 |
| MSI           | GF63 8RD                    | [f6ef1dbd07](https://linux-hardware.org/?probe=f6ef1dbd07) | Sep 25, 2022 |
| Intel         | H81U                        | [9e4458528b](https://linux-hardware.org/?probe=9e4458528b) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [49b0161bf0](https://linux-hardware.org/?probe=49b0161bf0) | Sep 25, 2022 |
| HONOR         | BMH-WCX9                    | [867da0c4b8](https://linux-hardware.org/?probe=867da0c4b8) | Sep 25, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [f844479504](https://linux-hardware.org/?probe=f844479504) | Sep 25, 2022 |
| Apple         | MacBookPro6,2               | [be92ff8ffc](https://linux-hardware.org/?probe=be92ff8ffc) | Sep 25, 2022 |
| MSI           | GF75 Thin 10SC              | [0bda368d15](https://linux-hardware.org/?probe=0bda368d15) | Sep 24, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [786063cdde](https://linux-hardware.org/?probe=786063cdde) | Sep 24, 2022 |
| Lenovo        | ThinkPad T450 20BV001CSP    | [9233c6db8f](https://linux-hardware.org/?probe=9233c6db8f) | Sep 24, 2022 |
| HP            | 15                          | [bd8fc32d19](https://linux-hardware.org/?probe=bd8fc32d19) | Sep 24, 2022 |
| Unknown       | Unknown                     | [4a1323c81e](https://linux-hardware.org/?probe=4a1323c81e) | Sep 24, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [b73b2224d1](https://linux-hardware.org/?probe=b73b2224d1) | Sep 23, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [67ec6c656b](https://linux-hardware.org/?probe=67ec6c656b) | Sep 23, 2022 |
| Acer          | TravelMate P256-MG          | [0a7c58d00a](https://linux-hardware.org/?probe=0a7c58d00a) | Sep 23, 2022 |
| Sony          | VPCEB1Z1E                   | [37fea84df6](https://linux-hardware.org/?probe=37fea84df6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| HP            | Presario CQ57               | [322f46c499](https://linux-hardware.org/?probe=322f46c499) | Sep 22, 2022 |
| HP            | Stream Notebook PC 13       | [a5dff5d1f6](https://linux-hardware.org/?probe=a5dff5d1f6) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [080fdb990e](https://linux-hardware.org/?probe=080fdb990e) | Sep 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [849246d9f3](https://linux-hardware.org/?probe=849246d9f3) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [6db3839532](https://linux-hardware.org/?probe=6db3839532) | Sep 20, 2022 |
| Dell          | Latitude E7240              | [21dc4700da](https://linux-hardware.org/?probe=21dc4700da) | Sep 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [f03ae050eb](https://linux-hardware.org/?probe=f03ae050eb) | Sep 20, 2022 |
| Lenovo        | ThinkPad L15 Gen 1 20U30... | [317ff73ff5](https://linux-hardware.org/?probe=317ff73ff5) | Sep 20, 2022 |
| Chuwi         | CoreBook X                  | [4c963415cd](https://linux-hardware.org/?probe=4c963415cd) | Sep 20, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [ba7800b231](https://linux-hardware.org/?probe=ba7800b231) | Sep 20, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0fa5921ddf](https://linux-hardware.org/?probe=0fa5921ddf) | Sep 20, 2022 |
| Lenovo        | IdeaPad S340-15IIL 81VW     | [d14a12b8ca](https://linux-hardware.org/?probe=d14a12b8ca) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [04252a0991](https://linux-hardware.org/?probe=04252a0991) | Sep 20, 2022 |
| ASUSTek       | ROG Strix G712LV_G712LV     | [1e7ca74f13](https://linux-hardware.org/?probe=1e7ca74f13) | Sep 20, 2022 |
| Acer          | TravelMate P414-51          | [2ebd8f21d3](https://linux-hardware.org/?probe=2ebd8f21d3) | Sep 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U1S... | [e33202084e](https://linux-hardware.org/?probe=e33202084e) | Sep 20, 2022 |
| MSI           | Bravo 15 B5DD               | [3c51417d8f](https://linux-hardware.org/?probe=3c51417d8f) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [329f95e326](https://linux-hardware.org/?probe=329f95e326) | Sep 19, 2022 |
| LG Electro... | P530-K.AE23B                | [5891712135](https://linux-hardware.org/?probe=5891712135) | Sep 19, 2022 |
| Dell          | Inspiron 7559               | [4abbaf3df9](https://linux-hardware.org/?probe=4abbaf3df9) | Sep 19, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b415f7be91](https://linux-hardware.org/?probe=b415f7be91) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [4a7bdd8ed1](https://linux-hardware.org/?probe=4a7bdd8ed1) | Sep 19, 2022 |
| HUAWEI        | HN-WX9X                     | [46e9732572](https://linux-hardware.org/?probe=46e9732572) | Sep 19, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [4fcfd69ec1](https://linux-hardware.org/?probe=4fcfd69ec1) | Sep 19, 2022 |
| Dell          | Latitude 3420               | [5364b3d032](https://linux-hardware.org/?probe=5364b3d032) | Sep 18, 2022 |
| Chuwi         | HeroBook Air                | [26967f1d9e](https://linux-hardware.org/?probe=26967f1d9e) | Sep 17, 2022 |
| HP            | Stream Notebook PC 13       | [589078809b](https://linux-hardware.org/?probe=589078809b) | Sep 17, 2022 |
| ASUSTek       | UX430UAR                    | [a265f6053f](https://linux-hardware.org/?probe=a265f6053f) | Sep 17, 2022 |
| ASUSTek       | ROG Strix G513RM_G513RM     | [6b15cc63cc](https://linux-hardware.org/?probe=6b15cc63cc) | Sep 17, 2022 |
| HP            | Laptop 15-db0xxx            | [c4a7f1814f](https://linux-hardware.org/?probe=c4a7f1814f) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [197ccf755d](https://linux-hardware.org/?probe=197ccf755d) | Sep 16, 2022 |
| HP            | Compaq 6720s                | [75bc6df1df](https://linux-hardware.org/?probe=75bc6df1df) | Sep 16, 2022 |
| MSI           | GF63 8RD                    | [9e7ef8d86d](https://linux-hardware.org/?probe=9e7ef8d86d) | Sep 16, 2022 |
| HUAWEI        | HN-WX9X                     | [6f29359618](https://linux-hardware.org/?probe=6f29359618) | Sep 16, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [2c97d43674](https://linux-hardware.org/?probe=2c97d43674) | Sep 16, 2022 |
| Chuwi         | CoreBook X                  | [d5a3bc0015](https://linux-hardware.org/?probe=d5a3bc0015) | Sep 16, 2022 |
| Valve         | Jupiter                     | [44056051c4](https://linux-hardware.org/?probe=44056051c4) | Sep 16, 2022 |
| AXDIA Inte... | WINPAD V10                  | [ef71c6cd50](https://linux-hardware.org/?probe=ef71c6cd50) | Sep 15, 2022 |
| Dell          | Latitude D630               | [b898e91e58](https://linux-hardware.org/?probe=b898e91e58) | Sep 15, 2022 |
| ASUSTek       | 1201N                       | [0a48f359f8](https://linux-hardware.org/?probe=0a48f359f8) | Sep 15, 2022 |
| INFINITY      | Unknown                     | [37d2d32628](https://linux-hardware.org/?probe=37d2d32628) | Sep 15, 2022 |
| Toshiba       | Satellite P50-B-11L         | [eba4212008](https://linux-hardware.org/?probe=eba4212008) | Sep 15, 2022 |
| Chuwi         | HeroBook Air                | [fdf38c7fb0](https://linux-hardware.org/?probe=fdf38c7fb0) | Sep 14, 2022 |
| Lenovo        | IdeaPad S145-15AST 81N3     | [b552f0482d](https://linux-hardware.org/?probe=b552f0482d) | Sep 14, 2022 |
| Apple         | MacBookAir7,2               | [eb169c543e](https://linux-hardware.org/?probe=eb169c543e) | Sep 14, 2022 |
| Acer          | Aspire A715-72G             | [60cbc2fb39](https://linux-hardware.org/?probe=60cbc2fb39) | Sep 14, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | [4aa3e2b6c2](https://linux-hardware.org/?probe=4aa3e2b6c2) | Sep 14, 2022 |
| Acer          | Aspire 5742                 | [9c37d390a7](https://linux-hardware.org/?probe=9c37d390a7) | Sep 13, 2022 |
| Samsung       | 305V4A/305V5A               | [ba2ad7bf06](https://linux-hardware.org/?probe=ba2ad7bf06) | Sep 13, 2022 |
| Dell          | Latitude 7420               | [84f0ebcfea](https://linux-hardware.org/?probe=84f0ebcfea) | Sep 13, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [aa9d57c27e](https://linux-hardware.org/?probe=aa9d57c27e) | Sep 13, 2022 |
| MSI           | Prestige 14 A11SCX          | [0c0264943f](https://linux-hardware.org/?probe=0c0264943f) | Sep 13, 2022 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | [b6b3f2dce1](https://linux-hardware.org/?probe=b6b3f2dce1) | Sep 13, 2022 |
| ASUSTek       | X200LA                      | [e0947fe5c7](https://linux-hardware.org/?probe=e0947fe5c7) | Sep 13, 2022 |
| Medion        | E4251 MD61227               | [8b3475f65b](https://linux-hardware.org/?probe=8b3475f65b) | Sep 13, 2022 |
| Toshiba       | Satellite A500              | [0d96df6375](https://linux-hardware.org/?probe=0d96df6375) | Sep 13, 2022 |
| Toshiba       | Satellite L50D-B            | [2d09796251](https://linux-hardware.org/?probe=2d09796251) | Sep 12, 2022 |
| Lenovo        | B570e 521524G               | [c08fe13d14](https://linux-hardware.org/?probe=c08fe13d14) | Sep 12, 2022 |
| Lenovo        | ThinkPad T440 20B7A1P700    | [5be9f89a6f](https://linux-hardware.org/?probe=5be9f89a6f) | Sep 12, 2022 |
| HP            | Pavilion Laptop 15-ck0xx    | [390223e073](https://linux-hardware.org/?probe=390223e073) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming FX504GM_FX80G... | [0d1c08d02b](https://linux-hardware.org/?probe=0d1c08d02b) | Sep 11, 2022 |
| MSI           | Modern 14 C12M              | [e523452a96](https://linux-hardware.org/?probe=e523452a96) | Sep 11, 2022 |
| Dell          | Latitude E7240              | [2976e9106e](https://linux-hardware.org/?probe=2976e9106e) | Sep 10, 2022 |
| AXDIA Inte... | WINPAD V10                  | [b3e5abaf4b](https://linux-hardware.org/?probe=b3e5abaf4b) | Sep 09, 2022 |
| HP            | Compaq 8510w                | [a720eb1f63](https://linux-hardware.org/?probe=a720eb1f63) | Sep 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [efc8c6b2e7](https://linux-hardware.org/?probe=efc8c6b2e7) | Sep 08, 2022 |
| Lenovo        | B570e 521524G               | [1926ba3c2f](https://linux-hardware.org/?probe=1926ba3c2f) | Sep 07, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [2959121934](https://linux-hardware.org/?probe=2959121934) | Sep 07, 2022 |
| ASUSTek       | ProArt StudioBook H7600H... | [2817268e91](https://linux-hardware.org/?probe=2817268e91) | Sep 07, 2022 |
| HP            | ProBook 430 G6              | [99de13d37c](https://linux-hardware.org/?probe=99de13d37c) | Sep 07, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [2850ddb81f](https://linux-hardware.org/?probe=2850ddb81f) | Sep 06, 2022 |
| Lenovo        | V145-15AST 81MT             | [90d59bf651](https://linux-hardware.org/?probe=90d59bf651) | Sep 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [c1cc348ec8](https://linux-hardware.org/?probe=c1cc348ec8) | Sep 06, 2022 |
| MSI           | Prestige 15 A10SC           | [adbe97d2f1](https://linux-hardware.org/?probe=adbe97d2f1) | Sep 05, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [cb809c935a](https://linux-hardware.org/?probe=cb809c935a) | Sep 05, 2022 |
| Chuwi         | Hi10 Go                     | [f0d55e8aea](https://linux-hardware.org/?probe=f0d55e8aea) | Sep 04, 2022 |
| Notebook      | N141CU                      | [9a03ce91af](https://linux-hardware.org/?probe=9a03ce91af) | Sep 04, 2022 |
| HP            | Compaq 8510w                | [a49dcb1261](https://linux-hardware.org/?probe=a49dcb1261) | Sep 03, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [6d1fcccbb8](https://linux-hardware.org/?probe=6d1fcccbb8) | Sep 03, 2022 |
| MSI           | Katana GF66 12UC            | [270a50ac4c](https://linux-hardware.org/?probe=270a50ac4c) | Sep 01, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | [f25f0f5499](https://linux-hardware.org/?probe=f25f0f5499) | Sep 01, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [46e67b2b16](https://linux-hardware.org/?probe=46e67b2b16) | Sep 01, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [7b6028e52d](https://linux-hardware.org/?probe=7b6028e52d) | Sep 01, 2022 |
| LG Electro... | 14Z990-V.AP72B              | [8c67c188a1](https://linux-hardware.org/?probe=8c67c188a1) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [c9fcbe9935](https://linux-hardware.org/?probe=c9fcbe9935) | Sep 01, 2022 |
| Lenovo        | Legion Y530-15ICH 81FV      | [52efef286f](https://linux-hardware.org/?probe=52efef286f) | Sep 01, 2022 |
| HP            | Laptop 15-db0xxx            | [42879ce5cf](https://linux-hardware.org/?probe=42879ce5cf) | Aug 31, 2022 |
| HP            | Laptop 15-db0xxx            | [3c7e97b769](https://linux-hardware.org/?probe=3c7e97b769) | Aug 31, 2022 |
| Notebook      | N24_25JU                    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Acer          | Aspire E5-521               | [9ce49fc3a3](https://linux-hardware.org/?probe=9ce49fc3a3) | Aug 31, 2022 |
| HP            | Compaq 8510w                | [f7e1515654](https://linux-hardware.org/?probe=f7e1515654) | Aug 30, 2022 |
| ASUSTek       | F3F                         | [57c5732aaa](https://linux-hardware.org/?probe=57c5732aaa) | Aug 30, 2022 |
| HP            | Notebook                    | [b0b97c0ea3](https://linux-hardware.org/?probe=b0b97c0ea3) | Aug 30, 2022 |
| Chuwi         | GemiBook Pro                | [b85d2b0ec5](https://linux-hardware.org/?probe=b85d2b0ec5) | Aug 30, 2022 |
| Chuwi         | GemiBook                    | [abca00f582](https://linux-hardware.org/?probe=abca00f582) | Aug 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [52f02ff7f1](https://linux-hardware.org/?probe=52f02ff7f1) | Aug 29, 2022 |
| Apple         | MacBookPro5,5               | [97fdbc4a5b](https://linux-hardware.org/?probe=97fdbc4a5b) | Aug 29, 2022 |
| Notebook      | NL4x_NL5xLU                 | [df4630db27](https://linux-hardware.org/?probe=df4630db27) | Aug 28, 2022 |
| Notebook      | N2x0WU                      | [c7065dc0c9](https://linux-hardware.org/?probe=c7065dc0c9) | Aug 28, 2022 |
| Acer          | Aspire E5-521               | [a94da62004](https://linux-hardware.org/?probe=a94da62004) | Aug 28, 2022 |
| Dell          | Vostro 3500                 | [e4cd019582](https://linux-hardware.org/?probe=e4cd019582) | Aug 27, 2022 |
| Dell          | Vostro 3500                 | [634c973e53](https://linux-hardware.org/?probe=634c973e53) | Aug 27, 2022 |
| speedmaste... | E131x series                | [69d287c029](https://linux-hardware.org/?probe=69d287c029) | Aug 26, 2022 |
| ASUSTek       | K52Jc                       | [5c10927d11](https://linux-hardware.org/?probe=5c10927d11) | Aug 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [292f932c92](https://linux-hardware.org/?probe=292f932c92) | Aug 25, 2022 |
| LG Electro... | 14Z90P-G.AA89B              | [bccfbd256c](https://linux-hardware.org/?probe=bccfbd256c) | Aug 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [254b378771](https://linux-hardware.org/?probe=254b378771) | Aug 23, 2022 |
| Acer          | Aspire 5742                 | [97c61c3095](https://linux-hardware.org/?probe=97c61c3095) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [ae3bcc6b88](https://linux-hardware.org/?probe=ae3bcc6b88) | Aug 22, 2022 |
| MSI           | PS63 Modern 8RC             | [b45c0fb9fa](https://linux-hardware.org/?probe=b45c0fb9fa) | Aug 22, 2022 |
| Dell          | Vostro 3550                 | [230033da23](https://linux-hardware.org/?probe=230033da23) | Aug 22, 2022 |
| Lenovo        | M30-70 80H8                 | [d254ca63b4](https://linux-hardware.org/?probe=d254ca63b4) | Aug 22, 2022 |
| Chuwi         | GemiBook Pro                | [03ed2d6805](https://linux-hardware.org/?probe=03ed2d6805) | Aug 22, 2022 |
| SLIMBOOK      | PROX14-AMD                  | [f01fb4784c](https://linux-hardware.org/?probe=f01fb4784c) | Aug 21, 2022 |
| Acer          | Aspire A517-52              | [b61f6861a6](https://linux-hardware.org/?probe=b61f6861a6) | Aug 21, 2022 |
| VANT          | MOOVE3-15                   | [2b5a36a1e6](https://linux-hardware.org/?probe=2b5a36a1e6) | Aug 20, 2022 |
| HP            | 250 G7 Notebook PC          | [ec15e7b0c5](https://linux-hardware.org/?probe=ec15e7b0c5) | Aug 19, 2022 |
| Apple         | MacBookPro5,5               | [f429863c5f](https://linux-hardware.org/?probe=f429863c5f) | Aug 19, 2022 |
| HP            | EliteBook 840 G6            | [8af519565f](https://linux-hardware.org/?probe=8af519565f) | Aug 18, 2022 |
| Apple         | MacBookPro11,3              | [4e9e089c1a](https://linux-hardware.org/?probe=4e9e089c1a) | Aug 18, 2022 |
| Chuwi         | HeroBook Air                | [6e13e6abe8](https://linux-hardware.org/?probe=6e13e6abe8) | Aug 18, 2022 |
| Lenovo        | ThinkPad P15 Gen 2i 20YQ... | [0887012e66](https://linux-hardware.org/?probe=0887012e66) | Aug 18, 2022 |
| ASUSTek       | N75SF                       | [3b6f89e145](https://linux-hardware.org/?probe=3b6f89e145) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [f7102225ca](https://linux-hardware.org/?probe=f7102225ca) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [3a57a6329f](https://linux-hardware.org/?probe=3a57a6329f) | Aug 17, 2022 |
| MSI           | Modern 14 A10RAS            | [1cdee0174f](https://linux-hardware.org/?probe=1cdee0174f) | Aug 16, 2022 |
| Valve         | Jupiter                     | [5f3785b334](https://linux-hardware.org/?probe=5f3785b334) | Aug 16, 2022 |
| ASUSTek       | TUF Gaming FX705GE_FX705... | [6132aea83b](https://linux-hardware.org/?probe=6132aea83b) | Aug 16, 2022 |
| Valve         | Jupiter                     | [c3f38697a4](https://linux-hardware.org/?probe=c3f38697a4) | Aug 15, 2022 |
| GPD           | G1618-03                    | [64b056ddb1](https://linux-hardware.org/?probe=64b056ddb1) | Aug 14, 2022 |
| GPD           | G1618-03                    | [7316acf7a6](https://linux-hardware.org/?probe=7316acf7a6) | Aug 14, 2022 |
| Acer          | Aspire E5-521               | [c127df7597](https://linux-hardware.org/?probe=c127df7597) | Aug 13, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [40814201a2](https://linux-hardware.org/?probe=40814201a2) | Aug 12, 2022 |
| Lenovo        | ThinkPad X201 3626HMG       | [1d08c103c7](https://linux-hardware.org/?probe=1d08c103c7) | Aug 12, 2022 |
| Chuwi         | HeroBook Air                | [5640964630](https://linux-hardware.org/?probe=5640964630) | Aug 12, 2022 |
| HP            | Laptop 15-da0xxx            | [70ea8b51c8](https://linux-hardware.org/?probe=70ea8b51c8) | Aug 12, 2022 |
| Dell          | Latitude D630               | [3650f52bba](https://linux-hardware.org/?probe=3650f52bba) | Aug 11, 2022 |
| Toshiba       | TECRA R950                  | [d428bef65b](https://linux-hardware.org/?probe=d428bef65b) | Aug 10, 2022 |
| ASUSTek       | X555LAB                     | [9c41cf4c2c](https://linux-hardware.org/?probe=9c41cf4c2c) | Aug 10, 2022 |
| HP            | Laptop 15-da0xxx            | [0e35955798](https://linux-hardware.org/?probe=0e35955798) | Aug 07, 2022 |
| HP            | EliteBook 2540p             | [14e0900f42](https://linux-hardware.org/?probe=14e0900f42) | Aug 06, 2022 |
| Dell          | Latitude 5520               | [33888d0477](https://linux-hardware.org/?probe=33888d0477) | Aug 06, 2022 |
| Dynabook      | Satellite Pro C50-G         | [755f865912](https://linux-hardware.org/?probe=755f865912) | Aug 05, 2022 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | [d975e76a17](https://linux-hardware.org/?probe=d975e76a17) | Aug 05, 2022 |
| Lenovo        | ThinkPad T440p 20AW007QM... | [ca0e99f941](https://linux-hardware.org/?probe=ca0e99f941) | Aug 05, 2022 |
| HP            | Laptop 15-da0xxx            | [75c4deee10](https://linux-hardware.org/?probe=75c4deee10) | Aug 05, 2022 |
| Acer          | Aspire 9410                 | [0d433f48f4](https://linux-hardware.org/?probe=0d433f48f4) | Aug 05, 2022 |
| Fujitsu Si... | AMILO Li1705                | [af83e534ff](https://linux-hardware.org/?probe=af83e534ff) | Aug 04, 2022 |
| Dell          | Latitude 5420               | [d4717e9bb1](https://linux-hardware.org/?probe=d4717e9bb1) | Aug 04, 2022 |
| ASUSTek       | GL752VW                     | [ff8fd29d96](https://linux-hardware.org/?probe=ff8fd29d96) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [5ab3e7f74f](https://linux-hardware.org/?probe=5ab3e7f74f) | Aug 03, 2022 |
| HP            | Pavilion Aero Laptop 13-... | [a6f7e6086b](https://linux-hardware.org/?probe=a6f7e6086b) | Aug 03, 2022 |
| MSI           | Pulse GL76 12UEK            | [02d4876457](https://linux-hardware.org/?probe=02d4876457) | Aug 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | [f5d4fdde00](https://linux-hardware.org/?probe=f5d4fdde00) | Aug 02, 2022 |
| ASUSTek       | X540SA                      | [6adb003f2e](https://linux-hardware.org/?probe=6adb003f2e) | Aug 01, 2022 |
| ASUSTek       | X540SA                      | [4dbed1e983](https://linux-hardware.org/?probe=4dbed1e983) | Aug 01, 2022 |
| Dell          | Latitude 7420               | [d498af2db5](https://linux-hardware.org/?probe=d498af2db5) | Aug 01, 2022 |
| Acer          | Aspire E1-571               | [7102c56d5b](https://linux-hardware.org/?probe=7102c56d5b) | Aug 01, 2022 |
| Chuwi         | GemiBook Pro                | [458c2e644f](https://linux-hardware.org/?probe=458c2e644f) | Jul 31, 2022 |
| HP            | Compaq 8510p                | [2a005b06da](https://linux-hardware.org/?probe=2a005b06da) | Jul 28, 2022 |
| Toshiba       | Satellite P50-B-118         | [b46f72c280](https://linux-hardware.org/?probe=b46f72c280) | Jul 28, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LW... | [a05f5dc510](https://linux-hardware.org/?probe=a05f5dc510) | Jul 28, 2022 |
| Chuwi         | GemiBook Pro                | [bfed86a5c4](https://linux-hardware.org/?probe=bfed86a5c4) | Jul 28, 2022 |
| Unknown       | Unknown                     | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [94f1822d11](https://linux-hardware.org/?probe=94f1822d11) | Jul 26, 2022 |
| Dell          | XPS 15 7590                 | [f1c4c81832](https://linux-hardware.org/?probe=f1c4c81832) | Jul 26, 2022 |
| eMachines     | D730                        | [4cba9849a0](https://linux-hardware.org/?probe=4cba9849a0) | Jul 26, 2022 |
| Alienware     | m15 R4                      | [2f80ebdd19](https://linux-hardware.org/?probe=2f80ebdd19) | Jul 26, 2022 |
| Acer          | Aspire 5749                 | [fa3b08453b](https://linux-hardware.org/?probe=fa3b08453b) | Jul 25, 2022 |
| Dell          | Latitude E6540              | [281f1b4a30](https://linux-hardware.org/?probe=281f1b4a30) | Jul 24, 2022 |
| HP            | Notebook                    | [d5802ce082](https://linux-hardware.org/?probe=d5802ce082) | Jul 24, 2022 |
| HP            | Stream Notebook             | [8422abef44](https://linux-hardware.org/?probe=8422abef44) | Jul 23, 2022 |
| Unknown       | Unknown                     | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| Lenovo        | ThinkPad T450 20BUS04A0B    | [afc6d3d00a](https://linux-hardware.org/?probe=afc6d3d00a) | Jul 22, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [447161e791](https://linux-hardware.org/?probe=447161e791) | Jul 21, 2022 |
| HP            | ProBook 640 G8 Notebook ... | [75f71928fe](https://linux-hardware.org/?probe=75f71928fe) | Jul 21, 2022 |
| Dell          | XPS 15 9510                 | [cf3548c6b4](https://linux-hardware.org/?probe=cf3548c6b4) | Jul 20, 2022 |
| Notebook      | W350STQ/W370ST              | [613b1f9d19](https://linux-hardware.org/?probe=613b1f9d19) | Jul 20, 2022 |
| Acer          | Aspire 5750G                | [08beab61a7](https://linux-hardware.org/?probe=08beab61a7) | Jul 18, 2022 |
| HUAWEI        | MateBook D                  | [5d7a616dd1](https://linux-hardware.org/?probe=5d7a616dd1) | Jul 18, 2022 |
| Toshiba       | Satellite Pro A50-C         | [a94461714d](https://linux-hardware.org/?probe=a94461714d) | Jul 18, 2022 |
| ASUSTek       | GL752VW                     | [b13a184720](https://linux-hardware.org/?probe=b13a184720) | Jul 18, 2022 |
| HONOR         | HYM-WXX                     | [654a2a5950](https://linux-hardware.org/?probe=654a2a5950) | Jul 17, 2022 |
| Dell          | Latitude 7390               | [fca3ed2ef5](https://linux-hardware.org/?probe=fca3ed2ef5) | Jul 17, 2022 |
| Toshiba       | Satellite L670              | [d753323f22](https://linux-hardware.org/?probe=d753323f22) | Jul 16, 2022 |
| ASUSTek       | K53U                        | [20120e258a](https://linux-hardware.org/?probe=20120e258a) | Jul 16, 2022 |
| Acer          | Aspire A315-23              | [5f1ff52baa](https://linux-hardware.org/?probe=5f1ff52baa) | Jul 16, 2022 |
| Valve         | Jupiter                     | [6c954fab9d](https://linux-hardware.org/?probe=6c954fab9d) | Jul 16, 2022 |
| Chuwi         | HeroBook Air                | [8f50476a9d](https://linux-hardware.org/?probe=8f50476a9d) | Jul 15, 2022 |
| Standard      | Unknown                     | [3b4805163d](https://linux-hardware.org/?probe=3b4805163d) | Jul 15, 2022 |
| Notebook      | W350STQ/W370ST              | [86daf7b30d](https://linux-hardware.org/?probe=86daf7b30d) | Jul 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [046794ca90](https://linux-hardware.org/?probe=046794ca90) | Jul 15, 2022 |
| Apple         | MacBookAir7,2               | [19c5e2272a](https://linux-hardware.org/?probe=19c5e2272a) | Jul 14, 2022 |
| Dell          | Latitude E5540              | [d6a6448930](https://linux-hardware.org/?probe=d6a6448930) | Jul 14, 2022 |
| Chuwi         | HeroBook Air                | [d76b0db2ca](https://linux-hardware.org/?probe=d76b0db2ca) | Jul 13, 2022 |
| MSI           | Modern 15 A5M               | [40c6c77f2c](https://linux-hardware.org/?probe=40c6c77f2c) | Jul 13, 2022 |
| MSI           | Katana GF66 12UD            | [2822036910](https://linux-hardware.org/?probe=2822036910) | Jul 12, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [6231802178](https://linux-hardware.org/?probe=6231802178) | Jul 12, 2022 |
| MSI           | Katana GF66 12UD            | [470a18c94b](https://linux-hardware.org/?probe=470a18c94b) | Jul 12, 2022 |
| Apple         | MacBookPro15,3              | [a8f8224853](https://linux-hardware.org/?probe=a8f8224853) | Jul 11, 2022 |
| MSI           | GL73 8SE                    | [b39d9f7404](https://linux-hardware.org/?probe=b39d9f7404) | Jul 11, 2022 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [f3de47ac1f](https://linux-hardware.org/?probe=f3de47ac1f) | Jul 10, 2022 |
| MSI           | GL75 Leopard 10SEK          | [532348a02c](https://linux-hardware.org/?probe=532348a02c) | Jul 10, 2022 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [bb736b4d03](https://linux-hardware.org/?probe=bb736b4d03) | Jul 08, 2022 |
| Dell          | Latitude 5285               | [1faeae7b00](https://linux-hardware.org/?probe=1faeae7b00) | Jul 07, 2022 |
| Chuwi         | GemiBook Pro                | [06b9f15824](https://linux-hardware.org/?probe=06b9f15824) | Jul 06, 2022 |
| Acer          | Aspire 5742G                | [3d76189da7](https://linux-hardware.org/?probe=3d76189da7) | Jul 06, 2022 |
| Chuwi         | GemiBook Pro                | [ab630b447f](https://linux-hardware.org/?probe=ab630b447f) | Jul 06, 2022 |
| Acer          | Aspire 5738                 | [3b93414575](https://linux-hardware.org/?probe=3b93414575) | Jul 05, 2022 |
| Chuwi         | GemiBook                    | [881c250e4f](https://linux-hardware.org/?probe=881c250e4f) | Jul 04, 2022 |
| Valve         | Jupiter                     | [766a3583f0](https://linux-hardware.org/?probe=766a3583f0) | Jul 04, 2022 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60e5b2ef2c](https://linux-hardware.org/?probe=60e5b2ef2c) | Jul 04, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [903fedb0aa](https://linux-hardware.org/?probe=903fedb0aa) | Jul 03, 2022 |
| Unknown       | Unknown                     | [f7dd6e9a70](https://linux-hardware.org/?probe=f7dd6e9a70) | Jul 02, 2022 |
| Lenovo        | V110-15IAP 80TG             | [05d0271371](https://linux-hardware.org/?probe=05d0271371) | Jul 01, 2022 |
| Lenovo        | V110-15IAP 80TG             | [23519c6427](https://linux-hardware.org/?probe=23519c6427) | Jul 01, 2022 |
| Razer         | Blade 14 (2022) - RZ09-0... | [927dbb8452](https://linux-hardware.org/?probe=927dbb8452) | Jul 01, 2022 |
| ASUSTek       | F3JR                        | [b56d8007d7](https://linux-hardware.org/?probe=b56d8007d7) | Jul 01, 2022 |
| Dell          | XPS 9320                    | [f04b491e6d](https://linux-hardware.org/?probe=f04b491e6d) | Jun 30, 2022 |
| Valve         | Jupiter                     | [bee9822ef6](https://linux-hardware.org/?probe=bee9822ef6) | Jun 30, 2022 |
| Acer          | Aspire 5740                 | [1db26fc575](https://linux-hardware.org/?probe=1db26fc575) | Jun 29, 2022 |
| Acer          | Aspire 5740                 | [44a72b9a94](https://linux-hardware.org/?probe=44a72b9a94) | Jun 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | [6491230956](https://linux-hardware.org/?probe=6491230956) | Jun 27, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [13c3e19573](https://linux-hardware.org/?probe=13c3e19573) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [c99e2d656f](https://linux-hardware.org/?probe=c99e2d656f) | Jun 26, 2022 |
| Medion        | S6445 MD61351               | [d0e2e3232c](https://linux-hardware.org/?probe=d0e2e3232c) | Jun 26, 2022 |
| HP            | 15                          | [3d3ad576a2](https://linux-hardware.org/?probe=3d3ad576a2) | Jun 26, 2022 |
| HP            | Pavilion dv6700             | [352a224c3f](https://linux-hardware.org/?probe=352a224c3f) | Jun 26, 2022 |
| HONOR         | BBR-WAX9                    | [0cffb17bc7](https://linux-hardware.org/?probe=0cffb17bc7) | Jun 25, 2022 |
| HP            | Laptop 15s-fq2xxx           | [170f5de9e2](https://linux-hardware.org/?probe=170f5de9e2) | Jun 25, 2022 |
| Samsung       | RF510/RF410/RF710           | [c68de3d559](https://linux-hardware.org/?probe=c68de3d559) | Jun 23, 2022 |
| HP            | OMEN by Laptop 16-c0xxx     | [e0dfa460b6](https://linux-hardware.org/?probe=e0dfa460b6) | Jun 23, 2022 |
| Dell          | Precision 5540              | [d4a5611433](https://linux-hardware.org/?probe=d4a5611433) | Jun 22, 2022 |
| Lenovo        | ThinkPad T495 20NKS01W06    | [d1a1093555](https://linux-hardware.org/?probe=d1a1093555) | Jun 22, 2022 |
| Toshiba       | Satellite L50D-B            | [500756a7e3](https://linux-hardware.org/?probe=500756a7e3) | Jun 21, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b248434bc6](https://linux-hardware.org/?probe=b248434bc6) | Jun 21, 2022 |
| Acer          | Ferrari One 200             | [52ba124048](https://linux-hardware.org/?probe=52ba124048) | Jun 21, 2022 |
| HP            | 250 G5 Notebook PC          | [0b40800023](https://linux-hardware.org/?probe=0b40800023) | Jun 21, 2022 |
| Dell          | Latitude E4310              | [180f09a85f](https://linux-hardware.org/?probe=180f09a85f) | Jun 20, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [e281d05a2a](https://linux-hardware.org/?probe=e281d05a2a) | Jun 18, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [65359ef780](https://linux-hardware.org/?probe=65359ef780) | Jun 18, 2022 |
| Acer          | Aspire V3-572G              | [efef888970](https://linux-hardware.org/?probe=efef888970) | Jun 18, 2022 |
| Lenovo        | ThinkPad X240 20AMS75900    | [e0eb6f7475](https://linux-hardware.org/?probe=e0eb6f7475) | Jun 18, 2022 |
| Dell          | Latitude E7270              | [bdf2e224f1](https://linux-hardware.org/?probe=bdf2e224f1) | Jun 18, 2022 |
| Dell          | Inspiron 15 5510            | [286f8505c9](https://linux-hardware.org/?probe=286f8505c9) | Jun 17, 2022 |
| HP            | OMEN by Laptop 15-dc1xxx    | [17077cf1d8](https://linux-hardware.org/?probe=17077cf1d8) | Jun 14, 2022 |
| Primux Tec... | Primux_1402F_W10            | [c3cf4149c9](https://linux-hardware.org/?probe=c3cf4149c9) | Jun 14, 2022 |
| Dynabook      | TECRA A50-J                 | [3f4449202f](https://linux-hardware.org/?probe=3f4449202f) | Jun 14, 2022 |
| HP            | EliteBook 8460p             | [e65bd18434](https://linux-hardware.org/?probe=e65bd18434) | Jun 12, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [2599b4c75d](https://linux-hardware.org/?probe=2599b4c75d) | Jun 12, 2022 |
| Alienware     | m15 R4                      | [5299db8f70](https://linux-hardware.org/?probe=5299db8f70) | Jun 11, 2022 |
| Dell          | Latitude 7280               | [7900c8009a](https://linux-hardware.org/?probe=7900c8009a) | Jun 10, 2022 |
| HP            | Compaq 6715b (GR667ET#AB... | [44de2345bb](https://linux-hardware.org/?probe=44de2345bb) | Jun 09, 2022 |
| Lenovo        | V15 G2 ITL 82KB             | [e956f6b0b8](https://linux-hardware.org/?probe=e956f6b0b8) | Jun 09, 2022 |
| Dell          | Inspiron 13-7359            | [c46dcc9b6f](https://linux-hardware.org/?probe=c46dcc9b6f) | Jun 07, 2022 |
| HP            | Stream Notebook PC 13       | [47b55dbb68](https://linux-hardware.org/?probe=47b55dbb68) | Jun 06, 2022 |
| Toshiba       | Satellite M70               | [61617a3561](https://linux-hardware.org/?probe=61617a3561) | Jun 05, 2022 |
| ASUSTek       | 1000H                       | [b2ae36f165](https://linux-hardware.org/?probe=b2ae36f165) | Jun 05, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [3dd8394bb5](https://linux-hardware.org/?probe=3dd8394bb5) | Jun 04, 2022 |
| eMachines     | eME732                      | [c6d57c850c](https://linux-hardware.org/?probe=c6d57c850c) | Jun 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [605cbc489f](https://linux-hardware.org/?probe=605cbc489f) | Jun 03, 2022 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [caf55e4146](https://linux-hardware.org/?probe=caf55e4146) | Jun 03, 2022 |
| ASUSTek       | TX201LA                     | [ba677dadab](https://linux-hardware.org/?probe=ba677dadab) | Jun 01, 2022 |
| TEKNOSERVI... | PORTATIL TTL 14             | [7af14493e8](https://linux-hardware.org/?probe=7af14493e8) | Jun 01, 2022 |
| ASUSTek       | ROG Strix G713QM_G713QM     | [185587d5e1](https://linux-hardware.org/?probe=185587d5e1) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [65f67bae3c](https://linux-hardware.org/?probe=65f67bae3c) | Jun 01, 2022 |
| Acer          | Aspire 5742G                | [41cad28720](https://linux-hardware.org/?probe=41cad28720) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [84efabac8f](https://linux-hardware.org/?probe=84efabac8f) | Jun 01, 2022 |
| HP            | Laptop 14-dk1xxx            | [c996bce6b5](https://linux-hardware.org/?probe=c996bce6b5) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [2861999420](https://linux-hardware.org/?probe=2861999420) | Jun 01, 2022 |
| Dell          | Inspiron 7537               | [103bb197fa](https://linux-hardware.org/?probe=103bb197fa) | Jun 01, 2022 |
| HUAWEI        | BOHK-WAX9X                  | [c4468417e9](https://linux-hardware.org/?probe=c4468417e9) | Jun 01, 2022 |
| Lenovo        | ThinkPad X200s 74663RG      | [460e11ebe2](https://linux-hardware.org/?probe=460e11ebe2) | May 31, 2022 |
| HP            | Laptop 15s-fq1xxx           | [08fe1f2d0f](https://linux-hardware.org/?probe=08fe1f2d0f) | May 31, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [a1dfbe3337](https://linux-hardware.org/?probe=a1dfbe3337) | May 31, 2022 |
| Acer          | TravelMate P256-MG          | [22b617425d](https://linux-hardware.org/?probe=22b617425d) | May 31, 2022 |
| Fujitsu       | LIFEBOOK E5511              | [32317d8883](https://linux-hardware.org/?probe=32317d8883) | May 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4fadee73e4](https://linux-hardware.org/?probe=4fadee73e4) | May 29, 2022 |
| Chuwi         | GemiBook                    | [432c1135b8](https://linux-hardware.org/?probe=432c1135b8) | May 29, 2022 |
| Lenovo        | G580 20150                  | [60128f5782](https://linux-hardware.org/?probe=60128f5782) | May 29, 2022 |
| Valve         | Jupiter                     | [f3910c9796](https://linux-hardware.org/?probe=f3910c9796) | May 29, 2022 |
| Toshiba       | Satellite L10W-B-101        | [774d5a9eae](https://linux-hardware.org/?probe=774d5a9eae) | May 28, 2022 |
| MSI           | PR600                       | [09b736e706](https://linux-hardware.org/?probe=09b736e706) | May 27, 2022 |
| Medion        | S6421 MD60703               | [9fffed019c](https://linux-hardware.org/?probe=9fffed019c) | May 27, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [53dc0937af](https://linux-hardware.org/?probe=53dc0937af) | May 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B9400CEA... | [f5488ccb22](https://linux-hardware.org/?probe=f5488ccb22) | May 26, 2022 |
| HONOR         | HLYL-WXX9                   | [57d71fca8a](https://linux-hardware.org/?probe=57d71fca8a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [86f00d534a](https://linux-hardware.org/?probe=86f00d534a) | May 26, 2022 |
| Lenovo        | V145-15AST 81MT             | [3929f17532](https://linux-hardware.org/?probe=3929f17532) | May 26, 2022 |
| HP            | Laptop 15-bw0xx             | [f71c048a96](https://linux-hardware.org/?probe=f71c048a96) | May 25, 2022 |
| MSI           | GP62MVR 6RF                 | [1dd5741ea8](https://linux-hardware.org/?probe=1dd5741ea8) | May 25, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [93c67e62e7](https://linux-hardware.org/?probe=93c67e62e7) | May 24, 2022 |
| MSI           | Prestige 15 A11SCS          | [2433529434](https://linux-hardware.org/?probe=2433529434) | May 24, 2022 |
| Toshiba       | Satellite L10W-B-101        | [bb4ce9afdd](https://linux-hardware.org/?probe=bb4ce9afdd) | May 24, 2022 |
| Unknown       | Aspire E                    | [d437b15b97](https://linux-hardware.org/?probe=d437b15b97) | May 24, 2022 |
| Unknown       | Aspire E                    | [f46b38824f](https://linux-hardware.org/?probe=f46b38824f) | May 24, 2022 |
| HP            | Mini 5103                   | [aa7f4e957e](https://linux-hardware.org/?probe=aa7f4e957e) | May 23, 2022 |
| MSI           | GF63 Thin 9SC               | [a2a182a63e](https://linux-hardware.org/?probe=a2a182a63e) | May 23, 2022 |
| HP            | 15                          | [a61f6dd1eb](https://linux-hardware.org/?probe=a61f6dd1eb) | May 23, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [d972595598](https://linux-hardware.org/?probe=d972595598) | May 22, 2022 |
| Dell          | G15 5510                    | [0ca1f736f9](https://linux-hardware.org/?probe=0ca1f736f9) | May 22, 2022 |
| Samsung       | RF510/RF410/RF710           | [c146b79bd6](https://linux-hardware.org/?probe=c146b79bd6) | May 22, 2022 |
| Toshiba       | PORTEGE Z830                | [9a4ebfe8cf](https://linux-hardware.org/?probe=9a4ebfe8cf) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [48c8683aa8](https://linux-hardware.org/?probe=48c8683aa8) | May 21, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [8d30966279](https://linux-hardware.org/?probe=8d30966279) | May 20, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | [c273310228](https://linux-hardware.org/?probe=c273310228) | May 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8f9ca8d66b](https://linux-hardware.org/?probe=8f9ca8d66b) | May 20, 2022 |
| Toshiba       | PORTEGE Z830                | [8d4eb653b6](https://linux-hardware.org/?probe=8d4eb653b6) | May 19, 2022 |
| HP            | EliteBook 840 G5            | [48e5424ecb](https://linux-hardware.org/?probe=48e5424ecb) | May 19, 2022 |
| MSI           | Prestige 14 A12UC           | [189b62a372](https://linux-hardware.org/?probe=189b62a372) | May 19, 2022 |
| Dell          | Latitude E4310              | [79cda1608c](https://linux-hardware.org/?probe=79cda1608c) | May 19, 2022 |
| Valve         | Jupiter                     | [f849597120](https://linux-hardware.org/?probe=f849597120) | May 18, 2022 |
| Valve         | Jupiter                     | [48df6e5c71](https://linux-hardware.org/?probe=48df6e5c71) | May 18, 2022 |
| Lenovo        | V145-15AST 81MT             | [badf4d0a88](https://linux-hardware.org/?probe=badf4d0a88) | May 18, 2022 |
| Chuwi         | HeroBook Air                | [7d96e10672](https://linux-hardware.org/?probe=7d96e10672) | May 17, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [61e58bea6c](https://linux-hardware.org/?probe=61e58bea6c) | May 17, 2022 |
| Lenovo        | G580 2189                   | [e7de790c8a](https://linux-hardware.org/?probe=e7de790c8a) | May 16, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [a8fffad424](https://linux-hardware.org/?probe=a8fffad424) | May 16, 2022 |
| HP            | ENVY Notebook 13-ab0XX      | [26ed58e99a](https://linux-hardware.org/?probe=26ed58e99a) | May 16, 2022 |
| Dell          | Latitude 5480               | [bccdb55064](https://linux-hardware.org/?probe=bccdb55064) | May 16, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [70cde2437b](https://linux-hardware.org/?probe=70cde2437b) | May 15, 2022 |
| Lenovo        | ThinkPad X250 20CLS0LE00    | [59eecf466b](https://linux-hardware.org/?probe=59eecf466b) | May 15, 2022 |
| Acer          | Aspire E1-522               | [21a4fc80c7](https://linux-hardware.org/?probe=21a4fc80c7) | May 13, 2022 |
| Acer          | Aspire E1-522               | [77fdc036b0](https://linux-hardware.org/?probe=77fdc036b0) | May 13, 2022 |
| Dell          | Latitude 5420               | [ac04d4cb5b](https://linux-hardware.org/?probe=ac04d4cb5b) | May 12, 2022 |
| Samsung       | RF510/RF410/RF710           | [8134289438](https://linux-hardware.org/?probe=8134289438) | May 12, 2022 |
| HP            | Pavilion g6                 | [4f5ac891f4](https://linux-hardware.org/?probe=4f5ac891f4) | May 11, 2022 |
| Acer          | Aspire 5742G                | [f720d9e031](https://linux-hardware.org/?probe=f720d9e031) | May 11, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [e6d1749248](https://linux-hardware.org/?probe=e6d1749248) | May 10, 2022 |
| MSI           | Modern 14 B11MO             | [75bc7c18db](https://linux-hardware.org/?probe=75bc7c18db) | May 10, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [02925e8fac](https://linux-hardware.org/?probe=02925e8fac) | May 10, 2022 |
| Acer          | TravelMate 6592             | [353516147d](https://linux-hardware.org/?probe=353516147d) | May 10, 2022 |
| HP            | Laptop 15s-eq2xxx           | [ae80aa69fe](https://linux-hardware.org/?probe=ae80aa69fe) | May 09, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [ef9c4b3841](https://linux-hardware.org/?probe=ef9c4b3841) | May 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [65ef6677b9](https://linux-hardware.org/?probe=65ef6677b9) | May 09, 2022 |
| MSI           | GE62 6QE                    | [6a3161d4ee](https://linux-hardware.org/?probe=6a3161d4ee) | May 09, 2022 |
| HP            | Laptop 15s-eq2xxx           | [f269fd3294](https://linux-hardware.org/?probe=f269fd3294) | May 09, 2022 |
| Acer          | Aspire A515-54              | [1d37964706](https://linux-hardware.org/?probe=1d37964706) | May 08, 2022 |
| MSI           | GE62 2QD                    | [cef8637026](https://linux-hardware.org/?probe=cef8637026) | May 08, 2022 |
| SLIMBOOK      | Essential15L                | [1a244b5f4a](https://linux-hardware.org/?probe=1a244b5f4a) | May 07, 2022 |
| SLIMBOOK      | Essential15L                | [4f64e62082](https://linux-hardware.org/?probe=4f64e62082) | May 07, 2022 |
| Dell          | Inspiron 5515               | [aa0534d7af](https://linux-hardware.org/?probe=aa0534d7af) | May 07, 2022 |
| Chuwi         | HeroBook Air                | [255ff705ac](https://linux-hardware.org/?probe=255ff705ac) | May 07, 2022 |
| HP            | EliteBook 840 G5            | [a53b09a7f3](https://linux-hardware.org/?probe=a53b09a7f3) | May 07, 2022 |
| HP            | 340S G7 Notebook PC         | [c0d0f6435b](https://linux-hardware.org/?probe=c0d0f6435b) | May 06, 2022 |
| HP            | ProBook 6470b               | [7849fd57dc](https://linux-hardware.org/?probe=7849fd57dc) | May 06, 2022 |
| Dell          | Latitude 5420               | [dbe0cffc08](https://linux-hardware.org/?probe=dbe0cffc08) | May 06, 2022 |
| HP            | Compaq 6730s                | [d1902442d8](https://linux-hardware.org/?probe=d1902442d8) | May 06, 2022 |
| HP            | Compaq 6730s                | [2e53f00a60](https://linux-hardware.org/?probe=2e53f00a60) | May 06, 2022 |
| HP            | Compaq 15                   | [25db1ef15f](https://linux-hardware.org/?probe=25db1ef15f) | May 06, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K6... | [1467c3bb41](https://linux-hardware.org/?probe=1467c3bb41) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [e8556f4acf](https://linux-hardware.org/?probe=e8556f4acf) | May 05, 2022 |
| SLIMBOOK      | EXECUTIVE-14                | [917add86ab](https://linux-hardware.org/?probe=917add86ab) | May 05, 2022 |
| Lenovo        | Y520-15IKBN 80WK            | [5cba3c93ba](https://linux-hardware.org/?probe=5cba3c93ba) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [ae20ca4c7c](https://linux-hardware.org/?probe=ae20ca4c7c) | May 05, 2022 |
| ASUSTek       | N10Jc                       | [1f688a5b2d](https://linux-hardware.org/?probe=1f688a5b2d) | May 05, 2022 |
| Apple         | MacBookPro5,1               | [d6293e8334](https://linux-hardware.org/?probe=d6293e8334) | May 05, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [0afdbf373d](https://linux-hardware.org/?probe=0afdbf373d) | May 04, 2022 |
| Notebook      | PD5x_7xPNP_PNN_PNT          | [a30b11f1a0](https://linux-hardware.org/?probe=a30b11f1a0) | May 04, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4f2714e3fe](https://linux-hardware.org/?probe=4f2714e3fe) | May 04, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [ecc7f176ff](https://linux-hardware.org/?probe=ecc7f176ff) | May 03, 2022 |
| Chuwi         | Hi10 Go                     | [33ea61404a](https://linux-hardware.org/?probe=33ea61404a) | May 03, 2022 |
| Acer          | Aspire A315-56              | [4321ddf926](https://linux-hardware.org/?probe=4321ddf926) | May 03, 2022 |
| Acer          | Aspire one 1-131            | [ade813cf7f](https://linux-hardware.org/?probe=ade813cf7f) | May 03, 2022 |
| Acer          | Aspire 5742G                | [37dfe53a95](https://linux-hardware.org/?probe=37dfe53a95) | May 02, 2022 |
| Acer          | Aspire 5742G                | [aff42aff28](https://linux-hardware.org/?probe=aff42aff28) | May 02, 2022 |
| HP            | Notebook                    | [3bdd2a5e96](https://linux-hardware.org/?probe=3bdd2a5e96) | May 01, 2022 |
| HP            | Pavilion g6                 | [bc4107a3bf](https://linux-hardware.org/?probe=bc4107a3bf) | May 01, 2022 |
| HUAWEI        | KLVL-WXX9                   | [b152a1215a](https://linux-hardware.org/?probe=b152a1215a) | Apr 30, 2022 |
| HP            | 650                         | [1332a3196c](https://linux-hardware.org/?probe=1332a3196c) | Apr 30, 2022 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | [e14a2c047d](https://linux-hardware.org/?probe=e14a2c047d) | Apr 30, 2022 |
| HP            | Stream Notebook PC 13       | [f4eb2d351c](https://linux-hardware.org/?probe=f4eb2d351c) | Apr 30, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8383d306f3](https://linux-hardware.org/?probe=8383d306f3) | Apr 30, 2022 |
| Acer          | TravelMate 6592             | [7d4878ff33](https://linux-hardware.org/?probe=7d4878ff33) | Apr 29, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [dc1c531e45](https://linux-hardware.org/?probe=dc1c531e45) | Apr 29, 2022 |
| Lenovo        | ThinkPad T480 20L6S29D02    | [1eb07120eb](https://linux-hardware.org/?probe=1eb07120eb) | Apr 29, 2022 |
| HP            | Compaq 6730b (GW687AV)      | [96ee86a3c6](https://linux-hardware.org/?probe=96ee86a3c6) | Apr 28, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [c3dad3331c](https://linux-hardware.org/?probe=c3dad3331c) | Apr 28, 2022 |
| Dell          | XPS 13 9370                 | [349f8f5d64](https://linux-hardware.org/?probe=349f8f5d64) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [b72fe24642](https://linux-hardware.org/?probe=b72fe24642) | Apr 27, 2022 |
| ASUSTek       | X550VX                      | [4dc675b81c](https://linux-hardware.org/?probe=4dc675b81c) | Apr 27, 2022 |
| Lenovo        | Z50-70 20354                | [44714b01ff](https://linux-hardware.org/?probe=44714b01ff) | Apr 26, 2022 |
| Lenovo        | Z50-70 20354                | [75188b99b5](https://linux-hardware.org/?probe=75188b99b5) | Apr 26, 2022 |
| Dell          | G15 5510                    | [5126d58147](https://linux-hardware.org/?probe=5126d58147) | Apr 26, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [3fcb247b21](https://linux-hardware.org/?probe=3fcb247b21) | Apr 25, 2022 |
| Apple         | MacBookPro9,2               | [003f1099c2](https://linux-hardware.org/?probe=003f1099c2) | Apr 25, 2022 |
| MSI           | GX700                       | [b2cc52d381](https://linux-hardware.org/?probe=b2cc52d381) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [99e25e855e](https://linux-hardware.org/?probe=99e25e855e) | Apr 23, 2022 |
| Chuwi         | AeroBook Pro                | [a123315898](https://linux-hardware.org/?probe=a123315898) | Apr 23, 2022 |
| Lenovo        | Yoga 300-11IBY 80M0         | [998ea03b05](https://linux-hardware.org/?probe=998ea03b05) | Apr 22, 2022 |
| Lenovo        | ThinkPad P53 20QN000ESP     | [16b3189bd8](https://linux-hardware.org/?probe=16b3189bd8) | Apr 22, 2022 |
| Dell          | XPS 13 7390                 | [b2cc2161d3](https://linux-hardware.org/?probe=b2cc2161d3) | Apr 21, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e0d5f104b9](https://linux-hardware.org/?probe=e0d5f104b9) | Apr 21, 2022 |
| eMachines     | D730                        | [09350021b3](https://linux-hardware.org/?probe=09350021b3) | Apr 20, 2022 |
| Lenovo        | Z50-70 20354                | [a7fcc96eb5](https://linux-hardware.org/?probe=a7fcc96eb5) | Apr 19, 2022 |
| Toshiba       | Satellite Pro C660          | [678e3209cb](https://linux-hardware.org/?probe=678e3209cb) | Apr 18, 2022 |
| Chuwi         | Unknown                     | [a44bd392c5](https://linux-hardware.org/?probe=a44bd392c5) | Apr 18, 2022 |
| Lenovo        | Z50-70 20354                | [e693d05883](https://linux-hardware.org/?probe=e693d05883) | Apr 17, 2022 |
| HP            | 250 G7 Notebook PC          | [4058d0c1ca](https://linux-hardware.org/?probe=4058d0c1ca) | Apr 17, 2022 |
| Acer          | Aspire 5750                 | [4ce545cc86](https://linux-hardware.org/?probe=4ce545cc86) | Apr 16, 2022 |
| Toshiba       | Satellite L10W-B-101        | [65edd32378](https://linux-hardware.org/?probe=65edd32378) | Apr 16, 2022 |
| HP            | Pavilion dv6500             | [064748981e](https://linux-hardware.org/?probe=064748981e) | Apr 15, 2022 |
| HP            | Pavilion dv6500             | [48350ccc67](https://linux-hardware.org/?probe=48350ccc67) | Apr 15, 2022 |
| LG Electro... | 15Z95P-G.AA78B              | [f5ef9987a4](https://linux-hardware.org/?probe=f5ef9987a4) | Apr 15, 2022 |
| Toshiba       | Satellite U840              | [9468123a43](https://linux-hardware.org/?probe=9468123a43) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [23936e29bb](https://linux-hardware.org/?probe=23936e29bb) | Apr 15, 2022 |
| Packard Be... | EasyNote TN36               | [ae514187f2](https://linux-hardware.org/?probe=ae514187f2) | Apr 15, 2022 |
| Toshiba       | NB520                       | [105666a973](https://linux-hardware.org/?probe=105666a973) | Apr 15, 2022 |
| AMI           | Intel                       | [bfee32835f](https://linux-hardware.org/?probe=bfee32835f) | Apr 14, 2022 |
| AMI           | Intel                       | [b7c76035df](https://linux-hardware.org/?probe=b7c76035df) | Apr 14, 2022 |
| Acer          | TravelMate P256-MG          | [55b07b48b3](https://linux-hardware.org/?probe=55b07b48b3) | Apr 14, 2022 |
| HP            | Laptop 15s-fq1xxx           | [48794f7ff0](https://linux-hardware.org/?probe=48794f7ff0) | Apr 14, 2022 |
| SLIMBOOK      | PRO                         | [97f545c3d4](https://linux-hardware.org/?probe=97f545c3d4) | Apr 14, 2022 |
| Lenovo        | ThinkPad Edge E540 20C60... | [45b8eba74c](https://linux-hardware.org/?probe=45b8eba74c) | Apr 14, 2022 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [3e5c6ada15](https://linux-hardware.org/?probe=3e5c6ada15) | Apr 14, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | [4434290159](https://linux-hardware.org/?probe=4434290159) | Apr 14, 2022 |
| Lenovo        | IdeaPad S540-13ARE 82DL     | [17363a1a13](https://linux-hardware.org/?probe=17363a1a13) | Apr 14, 2022 |
| HP            | Presario C500 (RY512EA#A... | [558d84adac](https://linux-hardware.org/?probe=558d84adac) | Apr 13, 2022 |
| Toshiba       | Satellite U840              | [c6fe138c8f](https://linux-hardware.org/?probe=c6fe138c8f) | Apr 13, 2022 |
| Unknown       | Unknown                     | [63f76ffc2b](https://linux-hardware.org/?probe=63f76ffc2b) | Apr 13, 2022 |
| Unknown       | Unknown                     | [3a9245cdab](https://linux-hardware.org/?probe=3a9245cdab) | Apr 13, 2022 |
| Acer          | Aspire E5-573G              | [0fbee9d8dc](https://linux-hardware.org/?probe=0fbee9d8dc) | Apr 13, 2022 |
| Acer          | Nitro AN517-41              | [b10d1a135d](https://linux-hardware.org/?probe=b10d1a135d) | Apr 13, 2022 |
| HP            | Compaq Mini CQ10-100        | [1acc227c33](https://linux-hardware.org/?probe=1acc227c33) | Apr 13, 2022 |
| Sony          | VGN-NW21EF_S                | [4ade997baf](https://linux-hardware.org/?probe=4ade997baf) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| MSI           | Prestige 15 A11SCX          | [a5bf5ddddf](https://linux-hardware.org/?probe=a5bf5ddddf) | Apr 12, 2022 |
| MSI           | Prestige 15 A11UC           | [20517e7efc](https://linux-hardware.org/?probe=20517e7efc) | Apr 11, 2022 |
| MSI           | Prestige 15 A11UC           | [3f8b7b11a5](https://linux-hardware.org/?probe=3f8b7b11a5) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [19ccaef18f](https://linux-hardware.org/?probe=19ccaef18f) | Apr 11, 2022 |
| HP            | Pavilion g6                 | [dabfb4bb05](https://linux-hardware.org/?probe=dabfb4bb05) | Apr 11, 2022 |
| ASUSTek       | X540LJ                      | [2eb11881fa](https://linux-hardware.org/?probe=2eb11881fa) | Apr 09, 2022 |
| Dell          | Latitude D630               | [6c715d7619](https://linux-hardware.org/?probe=6c715d7619) | Apr 09, 2022 |
| HP            | Laptop 15s-fq2xxx           | [a0001e2492](https://linux-hardware.org/?probe=a0001e2492) | Apr 09, 2022 |
| HP            | Compaq 15                   | [e3c3ac6478](https://linux-hardware.org/?probe=e3c3ac6478) | Apr 09, 2022 |
| HP            | Presario C500 (RY512EA#A... | [4ef049d490](https://linux-hardware.org/?probe=4ef049d490) | Apr 09, 2022 |
| HP            | 250 G7 Notebook PC          | [6271f39c13](https://linux-hardware.org/?probe=6271f39c13) | Apr 08, 2022 |
| HP            | ProBook 650 G1              | [9bd404657b](https://linux-hardware.org/?probe=9bd404657b) | Apr 08, 2022 |
| HP            | Laptop 14s-dq1xxx           | [72c98b5e79](https://linux-hardware.org/?probe=72c98b5e79) | Apr 07, 2022 |
| Dell          | Studio 1749                 | [14d44c44fc](https://linux-hardware.org/?probe=14d44c44fc) | Apr 07, 2022 |
| Acer          | Nitro AN517-41              | [b7cc683cc7](https://linux-hardware.org/?probe=b7cc683cc7) | Apr 05, 2022 |
| Acer          | Extensa 2511                | [00d24bfb95](https://linux-hardware.org/?probe=00d24bfb95) | Apr 05, 2022 |
| Dell          | XPS 15 9570                 | [0437f62b89](https://linux-hardware.org/?probe=0437f62b89) | Apr 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [91bae7b644](https://linux-hardware.org/?probe=91bae7b644) | Apr 05, 2022 |
| Lenovo        | ThinkPad X250 20CLS2GD00    | [c5fcd04bc5](https://linux-hardware.org/?probe=c5fcd04bc5) | Apr 04, 2022 |
| HP            | Laptop 15-da0xxx            | [7894bcc256](https://linux-hardware.org/?probe=7894bcc256) | Apr 03, 2022 |
| Acer          | Aspire F5-571               | [68cb5f9f95](https://linux-hardware.org/?probe=68cb5f9f95) | Apr 03, 2022 |
| Lenovo        | G580 2189                   | [da5b37bf9f](https://linux-hardware.org/?probe=da5b37bf9f) | Apr 02, 2022 |
| Toshiba       | Satellite L300              | [d3d1814f5d](https://linux-hardware.org/?probe=d3d1814f5d) | Apr 01, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | [afd4df967a](https://linux-hardware.org/?probe=afd4df967a) | Mar 29, 2022 |
| HP            | 355 G2                      | [5a5271a7df](https://linux-hardware.org/?probe=5a5271a7df) | Mar 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [dddc946b70](https://linux-hardware.org/?probe=dddc946b70) | Mar 29, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [e2dcac3e1a](https://linux-hardware.org/?probe=e2dcac3e1a) | Mar 29, 2022 |
| Chuwi         | LapBook SE                  | [69b963a8c0](https://linux-hardware.org/?probe=69b963a8c0) | Mar 28, 2022 |
| LG Electro... | 14Z90N-V.AR55B              | [4942a692f0](https://linux-hardware.org/?probe=4942a692f0) | Mar 28, 2022 |
| Dell          | XPS 13 9360                 | [9579421df6](https://linux-hardware.org/?probe=9579421df6) | Mar 28, 2022 |
| Lenovo        | ThinkPad T61 6464W4J        | [5f73680acf](https://linux-hardware.org/?probe=5f73680acf) | Mar 28, 2022 |
| HP            | Pavilion g6                 | [954723d6f4](https://linux-hardware.org/?probe=954723d6f4) | Mar 27, 2022 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | [078c1af4c3](https://linux-hardware.org/?probe=078c1af4c3) | Mar 27, 2022 |
| HP            | Stream Notebook PC 14       | [9fc309dcaf](https://linux-hardware.org/?probe=9fc309dcaf) | Mar 27, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [ba743bbb3b](https://linux-hardware.org/?probe=ba743bbb3b) | Mar 27, 2022 |
| Apple         | MacBook10,1                 | [62a1f4a38b](https://linux-hardware.org/?probe=62a1f4a38b) | Mar 25, 2022 |
| Apple         | MacBook10,1                 | [b58112c801](https://linux-hardware.org/?probe=b58112c801) | Mar 25, 2022 |
| Acer          | Aspire 5750G                | [4a7e22384f](https://linux-hardware.org/?probe=4a7e22384f) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [2782b13510](https://linux-hardware.org/?probe=2782b13510) | Mar 25, 2022 |
| Toshiba       | Satellite L50D-C            | [a0c9b5a952](https://linux-hardware.org/?probe=a0c9b5a952) | Mar 25, 2022 |
| Toshiba       | Satellite L10W-B-101        | [8064b23bf4](https://linux-hardware.org/?probe=8064b23bf4) | Mar 25, 2022 |
| HP            | Laptop 17-cn0xxx            | [9400fdbebf](https://linux-hardware.org/?probe=9400fdbebf) | Mar 24, 2022 |
| HP            | Laptop 15-da0xxx            | [794139f740](https://linux-hardware.org/?probe=794139f740) | Mar 24, 2022 |
| Lenovo        | ThinkPad P51 20HHCTO1WW     | [5a64dc1855](https://linux-hardware.org/?probe=5a64dc1855) | Mar 23, 2022 |
| Dell          | XPS 13 9360                 | [30003161fe](https://linux-hardware.org/?probe=30003161fe) | Mar 23, 2022 |
| Dell          | XPS 13 9305                 | [1fb70f4b83](https://linux-hardware.org/?probe=1fb70f4b83) | Mar 23, 2022 |
| ASUSTek       | N550LF                      | [5e5462ce64](https://linux-hardware.org/?probe=5e5462ce64) | Mar 23, 2022 |
| Dell          | Latitude E6330              | [a8d483108b](https://linux-hardware.org/?probe=a8d483108b) | Mar 22, 2022 |
| Acer          | TravelMate P256-MG          | [ec8aff9fc7](https://linux-hardware.org/?probe=ec8aff9fc7) | Mar 21, 2022 |
| Timi          | RedmiBook 16                | [0d8a2d4ea4](https://linux-hardware.org/?probe=0d8a2d4ea4) | Mar 21, 2022 |
| DIODE         | MS-N014                     | [0b95290c21](https://linux-hardware.org/?probe=0b95290c21) | Mar 21, 2022 |
| ASUSTek       | X553MA                      | [56d8c8496b](https://linux-hardware.org/?probe=56d8c8496b) | Mar 20, 2022 |
| HUAWEI        | HN-WX9X                     | [ee3842bc8f](https://linux-hardware.org/?probe=ee3842bc8f) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [dd40ec296a](https://linux-hardware.org/?probe=dd40ec296a) | Mar 20, 2022 |
| Lenovo        | ThinkPad T450 20BUS06B00    | [fb3591c2f8](https://linux-hardware.org/?probe=fb3591c2f8) | Mar 20, 2022 |
| Dell          | Latitude E5430 non-vPro     | [28d7818dd8](https://linux-hardware.org/?probe=28d7818dd8) | Mar 19, 2022 |
| HP            | EliteBook 2740p             | [b0fbd4018d](https://linux-hardware.org/?probe=b0fbd4018d) | Mar 18, 2022 |
| HP            | Presario CQ57               | [d5985051c5](https://linux-hardware.org/?probe=d5985051c5) | Mar 18, 2022 |
| HP            | Laptop 17-cn0xxx            | [cf2893ebfd](https://linux-hardware.org/?probe=cf2893ebfd) | Mar 16, 2022 |
| Acer          | Aspire SW3-016              | [6988255f00](https://linux-hardware.org/?probe=6988255f00) | Mar 14, 2022 |
| HP            | Laptop 15-bs0xx             | [2dd60fe836](https://linux-hardware.org/?probe=2dd60fe836) | Mar 13, 2022 |
| HP            | Pavilion Notebook           | [1de76aac69](https://linux-hardware.org/?probe=1de76aac69) | Mar 12, 2022 |
| HP            | EliteBook 2540p             | [d07352bf9a](https://linux-hardware.org/?probe=d07352bf9a) | Mar 12, 2022 |
| ASUSTek       | K53U                        | [7f78b941ce](https://linux-hardware.org/?probe=7f78b941ce) | Mar 11, 2022 |
| Acer          | Aspire A114-31              | [aa9bcbb679](https://linux-hardware.org/?probe=aa9bcbb679) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [a7ca755c8e](https://linux-hardware.org/?probe=a7ca755c8e) | Mar 11, 2022 |
| HP            | ENVY Notebook               | [591f84e3bb](https://linux-hardware.org/?probe=591f84e3bb) | Mar 11, 2022 |
| Teclast       | F15S                        | [a92a5510ef](https://linux-hardware.org/?probe=a92a5510ef) | Mar 11, 2022 |
| Lenovo        | ThinkPad T440s 20ARS08Q0... | [10655c6e60](https://linux-hardware.org/?probe=10655c6e60) | Mar 11, 2022 |
| HP            | Pavilion g6                 | [570c07ee5c](https://linux-hardware.org/?probe=570c07ee5c) | Mar 10, 2022 |
| Acer          | Aspire S3                   | [6ae9c3b307](https://linux-hardware.org/?probe=6ae9c3b307) | Mar 10, 2022 |
| Dell          | Latitude 5520               | [bb234c5fd0](https://linux-hardware.org/?probe=bb234c5fd0) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [3df16e8d72](https://linux-hardware.org/?probe=3df16e8d72) | Mar 10, 2022 |
| ASUSTek       | K55VD                       | [a67d3468f1](https://linux-hardware.org/?probe=a67d3468f1) | Mar 10, 2022 |
| Quanta        | TW8/SW8/DW8                 | [463ca7f3a3](https://linux-hardware.org/?probe=463ca7f3a3) | Mar 10, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [c7825c54fc](https://linux-hardware.org/?probe=c7825c54fc) | Mar 10, 2022 |
| ASUSTek       | K52F                        | [8e1b16c60b](https://linux-hardware.org/?probe=8e1b16c60b) | Mar 09, 2022 |
| Timi          | TM1703                      | [f9a954eea3](https://linux-hardware.org/?probe=f9a954eea3) | Mar 09, 2022 |
| MSI           | Creator Z16 A11UET          | [1804e5eb77](https://linux-hardware.org/?probe=1804e5eb77) | Mar 09, 2022 |
| Toshiba       | Satellite L10W-B-101        | [4425801f5c](https://linux-hardware.org/?probe=4425801f5c) | Mar 09, 2022 |
| HP            | Laptop 14s-dq2xxx           | [92db061239](https://linux-hardware.org/?probe=92db061239) | Mar 09, 2022 |
| Notebook      | W517GU1                     | [6a4971b810](https://linux-hardware.org/?probe=6a4971b810) | Mar 09, 2022 |
| MSI           | Prestige 15 A11SCS          | [20757cc7e0](https://linux-hardware.org/?probe=20757cc7e0) | Mar 08, 2022 |
| Dell          | System XPS L322X            | [2aa0c05f64](https://linux-hardware.org/?probe=2aa0c05f64) | Mar 06, 2022 |
| Lenovo        | IdeaPad 330-14AST 81D5      | [6e8e3f12d0](https://linux-hardware.org/?probe=6e8e3f12d0) | Mar 06, 2022 |
| Dell          | Latitude E5430 non-vPro     | [04d9923f43](https://linux-hardware.org/?probe=04d9923f43) | Mar 06, 2022 |
| Toshiba       | Satellite Pro P200          | [6a8be21d50](https://linux-hardware.org/?probe=6a8be21d50) | Mar 06, 2022 |
| Chuwi         | HeroBook Air                | [77ffb9a5a6](https://linux-hardware.org/?probe=77ffb9a5a6) | Mar 05, 2022 |
| Chuwi         | HeroBook Air                | [167b8de1e1](https://linux-hardware.org/?probe=167b8de1e1) | Mar 05, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [2862f94170](https://linux-hardware.org/?probe=2862f94170) | Mar 05, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | [c480ac2c0f](https://linux-hardware.org/?probe=c480ac2c0f) | Mar 03, 2022 |
| Lenovo        | ThinkPad X220 Tablet 429... | [e8dd84a845](https://linux-hardware.org/?probe=e8dd84a845) | Mar 03, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [89e8399104](https://linux-hardware.org/?probe=89e8399104) | Mar 03, 2022 |
| ASUSTek       | GL553VD                     | [b3c5530f89](https://linux-hardware.org/?probe=b3c5530f89) | Mar 03, 2022 |
| Dell          | Latitude E5430 non-vPro     | [3f1e43c90c](https://linux-hardware.org/?probe=3f1e43c90c) | Mar 01, 2022 |
| HONOR         | HLYL-WXX9                   | [c2de0e3f1c](https://linux-hardware.org/?probe=c2de0e3f1c) | Feb 28, 2022 |
| Apple         | MacBookAir7,2               | [e2bc04b6f4](https://linux-hardware.org/?probe=e2bc04b6f4) | Feb 27, 2022 |
| Apple         | MacBookAir7,2               | [592d42e16c](https://linux-hardware.org/?probe=592d42e16c) | Feb 27, 2022 |
| ASUSTek       | ZenBook UX450FDX_UX480FD    | [a7fbe4b7c8](https://linux-hardware.org/?probe=a7fbe4b7c8) | Feb 27, 2022 |
| Packard Be... | EasyNote TK85               | [97ab51b64a](https://linux-hardware.org/?probe=97ab51b64a) | Feb 26, 2022 |
| HP            | Notebook                    | [51dbbe9d8d](https://linux-hardware.org/?probe=51dbbe9d8d) | Feb 26, 2022 |
| HUAWEI        | KLVL-WXX9                   | [efd62e1ed7](https://linux-hardware.org/?probe=efd62e1ed7) | Feb 26, 2022 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [0ac4073b44](https://linux-hardware.org/?probe=0ac4073b44) | Feb 26, 2022 |
| Teclast       | F15 Plus                    | [a14a5fd6eb](https://linux-hardware.org/?probe=a14a5fd6eb) | Feb 26, 2022 |
| MSI           | Bravo 15 B5DD               | [273737b3d7](https://linux-hardware.org/?probe=273737b3d7) | Feb 25, 2022 |
| Toshiba       | Satellite Pro C650          | [15fb8724cf](https://linux-hardware.org/?probe=15fb8724cf) | Feb 25, 2022 |
| HP            | ProBook 450 G8 Notebook ... | [928d2937db](https://linux-hardware.org/?probe=928d2937db) | Feb 25, 2022 |
| ASUSTek       | ROG Strix G531GV_G531GV     | [bee22eb4da](https://linux-hardware.org/?probe=bee22eb4da) | Feb 25, 2022 |
| ASUSTek       | X751LD                      | [7159c22bcd](https://linux-hardware.org/?probe=7159c22bcd) | Feb 25, 2022 |
| Teclast       | F15 Plus                    | [e8e8b2f6da](https://linux-hardware.org/?probe=e8e8b2f6da) | Feb 24, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [13b7868e73](https://linux-hardware.org/?probe=13b7868e73) | Feb 24, 2022 |
| ASUSTek       | X551MA                      | [4796f04ae9](https://linux-hardware.org/?probe=4796f04ae9) | Feb 24, 2022 |
| Packard Be... | DOT S                       | [e90543b727](https://linux-hardware.org/?probe=e90543b727) | Feb 24, 2022 |
| ASUSTek       | X551MA                      | [1a3cbf4e30](https://linux-hardware.org/?probe=1a3cbf4e30) | Feb 24, 2022 |
| Lenovo        | IdeaPad 3 14ITL6 82H7       | [15df5df598](https://linux-hardware.org/?probe=15df5df598) | Feb 24, 2022 |
| HP            | ProBook 4510s               | [83a16ef7f8](https://linux-hardware.org/?probe=83a16ef7f8) | Feb 23, 2022 |
| Acer          | Nitro AN517-41              | [47b906a661](https://linux-hardware.org/?probe=47b906a661) | Feb 23, 2022 |
| HP            | Pavilion Notebook 15-bc5... | [46b3194e02](https://linux-hardware.org/?probe=46b3194e02) | Feb 23, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [2394a1f3a8](https://linux-hardware.org/?probe=2394a1f3a8) | Feb 23, 2022 |
| HP            | Pavilion g6                 | [1c1f4685eb](https://linux-hardware.org/?probe=1c1f4685eb) | Feb 22, 2022 |
| Dell          | Inspiron 5515               | [883e979d85](https://linux-hardware.org/?probe=883e979d85) | Feb 22, 2022 |
| HP            | Mini 210-1100               | [fabcf91b6c](https://linux-hardware.org/?probe=fabcf91b6c) | Feb 22, 2022 |
| HP            | Mini 210-1100               | [55d5641a6b](https://linux-hardware.org/?probe=55d5641a6b) | Feb 22, 2022 |
| HP            | Laptop 15-db0xxx            | [32942f112f](https://linux-hardware.org/?probe=32942f112f) | Feb 21, 2022 |
| HP            | Notebook                    | [d734cd43d3](https://linux-hardware.org/?probe=d734cd43d3) | Feb 21, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [26dbfadfe1](https://linux-hardware.org/?probe=26dbfadfe1) | Feb 21, 2022 |
| HP            | 250 G4 Notebook PC          | [7d3c0014c0](https://linux-hardware.org/?probe=7d3c0014c0) | Feb 20, 2022 |
| HP            | Pavilion g6                 | [77bcf6cc10](https://linux-hardware.org/?probe=77bcf6cc10) | Feb 19, 2022 |
| Lenovo        | ThinkPad T420 4180DY4       | [88c3891424](https://linux-hardware.org/?probe=88c3891424) | Feb 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [a551128b45](https://linux-hardware.org/?probe=a551128b45) | Feb 18, 2022 |
| Chuwi         | HeroBook Air                | [1955975178](https://linux-hardware.org/?probe=1955975178) | Feb 18, 2022 |
| Unknown       | Unknown                     | [e0ce842fa6](https://linux-hardware.org/?probe=e0ce842fa6) | Feb 18, 2022 |
| Dell          | Latitude E5410              | [c60f9e4a42](https://linux-hardware.org/?probe=c60f9e4a42) | Feb 17, 2022 |
| Chuwi         | GemiBook                    | [596102e73f](https://linux-hardware.org/?probe=596102e73f) | Feb 17, 2022 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [bda7853dd1](https://linux-hardware.org/?probe=bda7853dd1) | Feb 17, 2022 |
| Acer          | Aspire M3-581T              | [1229cec202](https://linux-hardware.org/?probe=1229cec202) | Feb 16, 2022 |
| Notebook      | N141CU                      | [029f48bc53](https://linux-hardware.org/?probe=029f48bc53) | Feb 16, 2022 |
| HP            | EliteBook 2740p             | [30d2deeb07](https://linux-hardware.org/?probe=30d2deeb07) | Feb 16, 2022 |
| eMachines     | D730                        | [b1b46f9a2f](https://linux-hardware.org/?probe=b1b46f9a2f) | Feb 16, 2022 |
| Lenovo        | IdeaPad 320-15ISK 80XH      | [64d19bc64f](https://linux-hardware.org/?probe=64d19bc64f) | Feb 13, 2022 |
| Acer          | Extensa 2519                | [4da8d63710](https://linux-hardware.org/?probe=4da8d63710) | Feb 13, 2022 |
| Toshiba       | Satellite L755              | [0c388987dc](https://linux-hardware.org/?probe=0c388987dc) | Feb 13, 2022 |
| Dell          | Latitude 14 Rugged (5404... | [c15ba7893e](https://linux-hardware.org/?probe=c15ba7893e) | Feb 13, 2022 |
| ASUSTek       | S550CM                      | [a6605f0fa3](https://linux-hardware.org/?probe=a6605f0fa3) | Feb 13, 2022 |
| Acer          | Aspire V5-122               | [d516569472](https://linux-hardware.org/?probe=d516569472) | Feb 13, 2022 |
| Dell          | Latitude 14 Rugged (5404... | [37267c6596](https://linux-hardware.org/?probe=37267c6596) | Feb 13, 2022 |
| HP            | Laptop 15s-eq1xxx           | [574d71e586](https://linux-hardware.org/?probe=574d71e586) | Feb 13, 2022 |
| Dell          | Inspiron 5515               | [3213a8a116](https://linux-hardware.org/?probe=3213a8a116) | Feb 12, 2022 |
| HP            | ProBook 640 G1              | [1aeb3957c5](https://linux-hardware.org/?probe=1aeb3957c5) | Feb 12, 2022 |
| Toshiba       | TECRA M10                   | [69dc5e3118](https://linux-hardware.org/?probe=69dc5e3118) | Feb 11, 2022 |
| HP            | Pavilion g6                 | [da04806287](https://linux-hardware.org/?probe=da04806287) | Feb 11, 2022 |
| MSI           | Katana GF66 11UC            | [6c784517e1](https://linux-hardware.org/?probe=6c784517e1) | Feb 11, 2022 |
| MSI           | Prestige 14 A10RB           | [7195cacd54](https://linux-hardware.org/?probe=7195cacd54) | Feb 10, 2022 |
| ASUSTek       | X550LD                      | [65d1ec0733](https://linux-hardware.org/?probe=65d1ec0733) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M740... | [265a5ef9aa](https://linux-hardware.org/?probe=265a5ef9aa) | Feb 10, 2022 |
| Apple         | MacBookPro6,2               | [7208fba41e](https://linux-hardware.org/?probe=7208fba41e) | Feb 09, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | [b3067b4ba2](https://linux-hardware.org/?probe=b3067b4ba2) | Feb 09, 2022 |
| HP            | Pavilion dv2000 (RR100EA... | [fc786f9d3f](https://linux-hardware.org/?probe=fc786f9d3f) | Feb 09, 2022 |
| Compal        | PBL21                       | [7a0b26892e](https://linux-hardware.org/?probe=7a0b26892e) | Feb 09, 2022 |
| Acer          | TravelMate 5720             | [d0756aac7e](https://linux-hardware.org/?probe=d0756aac7e) | Feb 09, 2022 |
| HP            | Notebook                    | [7900320935](https://linux-hardware.org/?probe=7900320935) | Feb 09, 2022 |
| Samsung       | X420/X520                   | [cd4b91a032](https://linux-hardware.org/?probe=cd4b91a032) | Feb 08, 2022 |
| HP            | ProBook 6475b               | [770340d4f9](https://linux-hardware.org/?probe=770340d4f9) | Feb 08, 2022 |
| Samsung       | Q310                        | [a558af5b07](https://linux-hardware.org/?probe=a558af5b07) | Feb 08, 2022 |
| HP            | 250 G6 Notebook PC          | [40b0583970](https://linux-hardware.org/?probe=40b0583970) | Feb 08, 2022 |
| Toshiba       | Satellite U500              | [a5e6d93704](https://linux-hardware.org/?probe=a5e6d93704) | Feb 07, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | [f2719a9d26](https://linux-hardware.org/?probe=f2719a9d26) | Feb 07, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [9c3722a690](https://linux-hardware.org/?probe=9c3722a690) | Feb 07, 2022 |
| ASUSTek       | K73SV                       | [d02cd235da](https://linux-hardware.org/?probe=d02cd235da) | Feb 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [e5f7c593d7](https://linux-hardware.org/?probe=e5f7c593d7) | Feb 06, 2022 |
| Medion        | E4241 MD60996               | [d89f5e4089](https://linux-hardware.org/?probe=d89f5e4089) | Feb 05, 2022 |
| HP            | Compaq Mini CQ10-100        | [5a471683f7](https://linux-hardware.org/?probe=5a471683f7) | Feb 05, 2022 |
| Acer          | Aspire 5715Z                | [378fec89b1](https://linux-hardware.org/?probe=378fec89b1) | Feb 04, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [cba975e95c](https://linux-hardware.org/?probe=cba975e95c) | Feb 02, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [4a5841b0dc](https://linux-hardware.org/?probe=4a5841b0dc) | Feb 02, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [006670e3fd](https://linux-hardware.org/?probe=006670e3fd) | Feb 02, 2022 |
| HP            | OMEN by Laptop              | [196508f0aa](https://linux-hardware.org/?probe=196508f0aa) | Feb 01, 2022 |
| MSI           | GL73 8RC                    | [597e463fc8](https://linux-hardware.org/?probe=597e463fc8) | Feb 01, 2022 |
| HP            | Laptop 15-db0xxx            | [523a77cee7](https://linux-hardware.org/?probe=523a77cee7) | Feb 01, 2022 |
| Dell          | Inspiron 7352               | [f36de689e1](https://linux-hardware.org/?probe=f36de689e1) | Feb 01, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [7beeaf4687](https://linux-hardware.org/?probe=7beeaf4687) | Jan 31, 2022 |
| Lenovo        | V14-ADA 82C6                | [e8c4b3dfce](https://linux-hardware.org/?probe=e8c4b3dfce) | Jan 31, 2022 |
| HP            | OMEN by Laptop              | [67f194f1e2](https://linux-hardware.org/?probe=67f194f1e2) | Jan 29, 2022 |
| Acer          | Aspire V5-571               | [9c1e6c6a9e](https://linux-hardware.org/?probe=9c1e6c6a9e) | Jan 29, 2022 |
| Toshiba       | TECRA R950                  | [53fc5e9542](https://linux-hardware.org/?probe=53fc5e9542) | Jan 29, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [bc7f79d54b](https://linux-hardware.org/?probe=bc7f79d54b) | Jan 28, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [a7df57bad0](https://linux-hardware.org/?probe=a7df57bad0) | Jan 28, 2022 |
| Dell          | XPS 15 7590                 | [39e13d6eeb](https://linux-hardware.org/?probe=39e13d6eeb) | Jan 27, 2022 |
| ASUSTek       | ROG Strix G513QM_G513QM     | [3c241e8e7f](https://linux-hardware.org/?probe=3c241e8e7f) | Jan 27, 2022 |
| HUAWEI        | NBLB-WAX9N                  | [9c8d4276ff](https://linux-hardware.org/?probe=9c8d4276ff) | Jan 27, 2022 |
| Lenovo        | ThinkPad T470s 20HF0000M... | [a760b631d0](https://linux-hardware.org/?probe=a760b631d0) | Jan 26, 2022 |
| MSI           | GE60 2OC\2OE                | [dee5b3e5a3](https://linux-hardware.org/?probe=dee5b3e5a3) | Jan 25, 2022 |
| Lenovo        | ThinkPad E590 20NB002AMH    | [a97c44b274](https://linux-hardware.org/?probe=a97c44b274) | Jan 25, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | [df690ab5bd](https://linux-hardware.org/?probe=df690ab5bd) | Jan 25, 2022 |
| MSI           | Prestige 15 A11SC           | [71a31ddfac](https://linux-hardware.org/?probe=71a31ddfac) | Jan 25, 2022 |
| Fujitsu       | LIFEBOOK U748               | [cad36b0eba](https://linux-hardware.org/?probe=cad36b0eba) | Jan 24, 2022 |
| ASUSTek       | X550CC                      | [5fa0a123f4](https://linux-hardware.org/?probe=5fa0a123f4) | Jan 24, 2022 |
| MSI           | Summit E13FlipEvo A11MT     | [b59e4cbfef](https://linux-hardware.org/?probe=b59e4cbfef) | Jan 23, 2022 |
| Lenovo        | ThinkPad W541 20EG0005MS    | [f89a7895fc](https://linux-hardware.org/?probe=f89a7895fc) | Jan 23, 2022 |
| Toshiba       | TECRA A9                    | [7ba32a721d](https://linux-hardware.org/?probe=7ba32a721d) | Jan 23, 2022 |
| AZW           | SEi                         | [71b530bc33](https://linux-hardware.org/?probe=71b530bc33) | Jan 22, 2022 |
| Lenovo        | G50-45 80MQ                 | [6a21be0bff](https://linux-hardware.org/?probe=6a21be0bff) | Jan 22, 2022 |
| Acer          | Aspire VN7-791              | [2abf48de85](https://linux-hardware.org/?probe=2abf48de85) | Jan 21, 2022 |
| Lenovo        | G580 2189                   | [3f1adf101d](https://linux-hardware.org/?probe=3f1adf101d) | Jan 21, 2022 |
| ASUSTek       | E200HA                      | [0d0222d2e9](https://linux-hardware.org/?probe=0d0222d2e9) | Jan 21, 2022 |
| HP            | Laptop 15s-fq2xxx           | [172a8a48ad](https://linux-hardware.org/?probe=172a8a48ad) | Jan 21, 2022 |
| Lenovo        | ThinkPad 20FMCT01WW         | [4bd81196a0](https://linux-hardware.org/?probe=4bd81196a0) | Jan 21, 2022 |
| SLIMBOOK      | PROX15-AMD                  | [beb8fcc3cb](https://linux-hardware.org/?probe=beb8fcc3cb) | Jan 21, 2022 |
| ASUSTek       | X556UJ                      | [e45ce2cdc0](https://linux-hardware.org/?probe=e45ce2cdc0) | Jan 21, 2022 |
| ASUSTek       | X540YA                      | [99ff6cb58a](https://linux-hardware.org/?probe=99ff6cb58a) | Jan 20, 2022 |
| HP            | Laptop 15s-eq0xxx           | [ffedf62905](https://linux-hardware.org/?probe=ffedf62905) | Jan 20, 2022 |
| Lenovo        | Legion 5 15IMH05 82AU       | [e97b90d14b](https://linux-hardware.org/?probe=e97b90d14b) | Jan 20, 2022 |
| Dell          | Latitude E5430 vPro         | [279789817e](https://linux-hardware.org/?probe=279789817e) | Jan 20, 2022 |
| Lenovo        | ThinkBook 13s-IML 20RR      | [be84eb2443](https://linux-hardware.org/?probe=be84eb2443) | Jan 20, 2022 |
| Dell          | XPS 15 7590                 | [3bd2c0c4bf](https://linux-hardware.org/?probe=3bd2c0c4bf) | Jan 20, 2022 |
| Lenovo        | ThinkPad E560 20EVA02SSP    | [e9bebad8ef](https://linux-hardware.org/?probe=e9bebad8ef) | Jan 19, 2022 |
| HONOR         | HLYL-WXX9                   | [442f689118](https://linux-hardware.org/?probe=442f689118) | Jan 19, 2022 |
| MSI           | GL63 8RD                    | [86ea72af05](https://linux-hardware.org/?probe=86ea72af05) | Jan 17, 2022 |
| Lenovo        | IdeaPad 3 14ADA05 81W0      | [8a9370c34f](https://linux-hardware.org/?probe=8a9370c34f) | Jan 16, 2022 |
| HP            | 250 G4                      | [4de0cf1eb0](https://linux-hardware.org/?probe=4de0cf1eb0) | Jan 16, 2022 |
| Dell          | Inspiron 15-3573            | [306c4cc1ae](https://linux-hardware.org/?probe=306c4cc1ae) | Jan 16, 2022 |
| Acer          | Extensa 2510G               | [0e581165b2](https://linux-hardware.org/?probe=0e581165b2) | Jan 15, 2022 |
| HP            | 250 G4 Notebook PC          | [62299ae38a](https://linux-hardware.org/?probe=62299ae38a) | Jan 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [d19a03f3b4](https://linux-hardware.org/?probe=d19a03f3b4) | Jan 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [31cd8dd167](https://linux-hardware.org/?probe=31cd8dd167) | Jan 14, 2022 |
| Packard Be... | EasyNote MH36               | [6095b5edd5](https://linux-hardware.org/?probe=6095b5edd5) | Jan 14, 2022 |
| Lenovo        | V510-15IKB 80WQ             | [53c16c3d57](https://linux-hardware.org/?probe=53c16c3d57) | Jan 14, 2022 |
| Dell          | XPS 15 9570                 | [7d322f1491](https://linux-hardware.org/?probe=7d322f1491) | Jan 14, 2022 |
| ASUSTek       | X550CC                      | [0607e7f57e](https://linux-hardware.org/?probe=0607e7f57e) | Jan 14, 2022 |
| MSI           | GE60 2PE                    | [d74dcddae6](https://linux-hardware.org/?probe=d74dcddae6) | Jan 13, 2022 |
| MSI           | Creator Z16 A11UE           | [b37a0927fe](https://linux-hardware.org/?probe=b37a0927fe) | Jan 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [3f856caf75](https://linux-hardware.org/?probe=3f856caf75) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | [fb5417c823](https://linux-hardware.org/?probe=fb5417c823) | Jan 12, 2022 |
| Lenovo        | G50-70 20351                | [d0e05a158d](https://linux-hardware.org/?probe=d0e05a158d) | Jan 11, 2022 |
| MSI           | Prestige 14 A10SC           | [252cf46efb](https://linux-hardware.org/?probe=252cf46efb) | Jan 11, 2022 |
| Lenovo        | IdeaPad 330-17ICH 81FL      | [4013d5dc28](https://linux-hardware.org/?probe=4013d5dc28) | Jan 11, 2022 |
| HP            | ENVY 15                     | [30b86e16bf](https://linux-hardware.org/?probe=30b86e16bf) | Jan 10, 2022 |
| Unknown       | Unknown                     | [cc748aab6a](https://linux-hardware.org/?probe=cc748aab6a) | Jan 09, 2022 |
| HP            | Laptop 17-cn0xxx            | [3d5989c45f](https://linux-hardware.org/?probe=3d5989c45f) | Jan 08, 2022 |
| HP            | EliteBook 2740p             | [eaaa9e2ef5](https://linux-hardware.org/?probe=eaaa9e2ef5) | Jan 07, 2022 |
| MSI           | GE66 Raider 11UH            | [afb3d72f66](https://linux-hardware.org/?probe=afb3d72f66) | Jan 07, 2022 |
| MSI           | GE66 Raider 11UH            | [d189bf2b8c](https://linux-hardware.org/?probe=d189bf2b8c) | Jan 07, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [ca2b9fac6f](https://linux-hardware.org/?probe=ca2b9fac6f) | Jan 07, 2022 |
| Dynabook      | Satellite Pro A50-J         | [264714a784](https://linux-hardware.org/?probe=264714a784) | Jan 07, 2022 |
| MSI           | GE75 Raider 8SF             | [23aab4b14f](https://linux-hardware.org/?probe=23aab4b14f) | Jan 06, 2022 |
| HP            | Victus by Laptop 16-e0xx... | [bab91e3b63](https://linux-hardware.org/?probe=bab91e3b63) | Jan 06, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [14039ef983](https://linux-hardware.org/?probe=14039ef983) | Jan 05, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [1533754d35](https://linux-hardware.org/?probe=1533754d35) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [675eb28882](https://linux-hardware.org/?probe=675eb28882) | Jan 05, 2022 |
| LG Electro... | E500-S.AP17B                | [203577c78f](https://linux-hardware.org/?probe=203577c78f) | Jan 05, 2022 |
| ASUSTek       | X550CL                      | [129864c44e](https://linux-hardware.org/?probe=129864c44e) | Jan 05, 2022 |
| Unknown       | 1.0                         | [9a4ec4a899](https://linux-hardware.org/?probe=9a4ec4a899) | Jan 05, 2022 |
| ASUSTek       | K50AF                       | [b9dfc28776](https://linux-hardware.org/?probe=b9dfc28776) | Jan 04, 2022 |
| HP            | EliteBook 2740p             | [339900943a](https://linux-hardware.org/?probe=339900943a) | Jan 04, 2022 |
| Lenovo        | G50-70 20351                | [04b904c594](https://linux-hardware.org/?probe=04b904c594) | Jan 04, 2022 |
| Medion        | S6421 MD61010               | [88c3c7c11b](https://linux-hardware.org/?probe=88c3c7c11b) | Jan 03, 2022 |
| AZW           | SEi                         | [99d54c937c](https://linux-hardware.org/?probe=99d54c937c) | Jan 02, 2022 |
| ASUSTek       | F5RL                        | [a11c531cb9](https://linux-hardware.org/?probe=a11c531cb9) | Jan 02, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [4e5ce73412](https://linux-hardware.org/?probe=4e5ce73412) | Jan 02, 2022 |
| Fujitsu       | LIFEBOOK U748               | [9eb9340d47](https://linux-hardware.org/?probe=9eb9340d47) | Jan 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0d6aab7930](https://linux-hardware.org/?probe=0d6aab7930) | Jan 01, 2022 |
| ASUSTek       | F5RL                        | [d391bef603](https://linux-hardware.org/?probe=d391bef603) | Jan 01, 2022 |
| Jumper        | EZbook                      | [aed28b71f9](https://linux-hardware.org/?probe=aed28b71f9) | Jan 01, 2022 |
| Lenovo        | Flex 2-14 20404             | [1ddb6e11fb](https://linux-hardware.org/?probe=1ddb6e11fb) | Jan 01, 2022 |
| MSI           | Modern 14 A10RB             | [cd1279f86a](https://linux-hardware.org/?probe=cd1279f86a) | Dec 31, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [b93b965f55](https://linux-hardware.org/?probe=b93b965f55) | Dec 30, 2021 |
| ASUSTek       | K52JB                       | [0fbc72f8ae](https://linux-hardware.org/?probe=0fbc72f8ae) | Dec 30, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | [80f7308b7e](https://linux-hardware.org/?probe=80f7308b7e) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [9ba0058839](https://linux-hardware.org/?probe=9ba0058839) | Dec 29, 2021 |
| Lenovo        | ThinkPad T520 4243B96       | [dbcf70aced](https://linux-hardware.org/?probe=dbcf70aced) | Dec 29, 2021 |
| Samsung       | RV420/RV520/RV720/E3530/... | [f6bb9a1802](https://linux-hardware.org/?probe=f6bb9a1802) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [fa46d4f41a](https://linux-hardware.org/?probe=fa46d4f41a) | Dec 28, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [22fb358e03](https://linux-hardware.org/?probe=22fb358e03) | Dec 28, 2021 |
| HP            | Notebook                    | [e9244b8df5](https://linux-hardware.org/?probe=e9244b8df5) | Dec 28, 2021 |
| Toshiba       | Satellite L12-C-104         | [fae8f8e1f9](https://linux-hardware.org/?probe=fae8f8e1f9) | Dec 27, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86651ee07a](https://linux-hardware.org/?probe=86651ee07a) | Dec 26, 2021 |
| HP            | EliteBook 840 G2            | [fc8a9ce141](https://linux-hardware.org/?probe=fc8a9ce141) | Dec 26, 2021 |
| HP            | Victus by Laptop 16-e0xx... | [6cd5ebfce7](https://linux-hardware.org/?probe=6cd5ebfce7) | Dec 25, 2021 |
| MSI           | GP76 Leopard 11UG           | [a14e38d07e](https://linux-hardware.org/?probe=a14e38d07e) | Dec 24, 2021 |
| Dell          | Latitude E6410              | [04c36dc9c3](https://linux-hardware.org/?probe=04c36dc9c3) | Dec 24, 2021 |
| Dell          | Latitude E7470              | [60e3743a3c](https://linux-hardware.org/?probe=60e3743a3c) | Dec 23, 2021 |
| Dynabook      | TECRA A50-J                 | [b400d3ecc0](https://linux-hardware.org/?probe=b400d3ecc0) | Dec 23, 2021 |
| MSI           | GE66 Raider 10SFS           | [4ec46a91e4](https://linux-hardware.org/?probe=4ec46a91e4) | Dec 23, 2021 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8701ef7cd1](https://linux-hardware.org/?probe=8701ef7cd1) | Dec 23, 2021 |
| Timi          | RedmiBook 16                | [c9cd395256](https://linux-hardware.org/?probe=c9cd395256) | Dec 23, 2021 |
| SLIMBOOK      | PROX14-10                   | [d841e4d8aa](https://linux-hardware.org/?probe=d841e4d8aa) | Dec 23, 2021 |
| HP            | Laptop 15-da0xxx            | [7e520450ed](https://linux-hardware.org/?probe=7e520450ed) | Dec 22, 2021 |
| Lenovo        | IdeaPad 530S-15IKB 81EV     | [f92d9c0315](https://linux-hardware.org/?probe=f92d9c0315) | Dec 20, 2021 |
| Acer          | Aspire 5750                 | [ef0cdc90a5](https://linux-hardware.org/?probe=ef0cdc90a5) | Dec 19, 2021 |
| Samsung       | RV410/RV510/S3510/E3510     | [9c38b95aa0](https://linux-hardware.org/?probe=9c38b95aa0) | Dec 19, 2021 |
| Acer          | Aspire VN7-791              | [6a9cdea468](https://linux-hardware.org/?probe=6a9cdea468) | Dec 19, 2021 |
| HP            | ProBook 6460b               | [37d39f8c88](https://linux-hardware.org/?probe=37d39f8c88) | Dec 18, 2021 |
| Chuwi         | GemiBook Pro                | [09acae6206](https://linux-hardware.org/?probe=09acae6206) | Dec 18, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ce1a1eb460](https://linux-hardware.org/?probe=ce1a1eb460) | Dec 17, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [bfdb06c0ae](https://linux-hardware.org/?probe=bfdb06c0ae) | Dec 17, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | [6bf6c57117](https://linux-hardware.org/?probe=6bf6c57117) | Dec 17, 2021 |
| Acer          | Aspire ES1-571              | [972c765b35](https://linux-hardware.org/?probe=972c765b35) | Dec 17, 2021 |
| Toshiba       | TECRA A9                    | [53cba6b9d1](https://linux-hardware.org/?probe=53cba6b9d1) | Dec 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [90bcb2d802](https://linux-hardware.org/?probe=90bcb2d802) | Dec 15, 2021 |
| Acer          | AOD255                      | [08a007120e](https://linux-hardware.org/?probe=08a007120e) | Dec 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [48b6785452](https://linux-hardware.org/?probe=48b6785452) | Dec 14, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [0705e530b4](https://linux-hardware.org/?probe=0705e530b4) | Dec 14, 2021 |
| Acer          | Aspire one                  | [32fd744f46](https://linux-hardware.org/?probe=32fd744f46) | Dec 14, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [a0a907bbb9](https://linux-hardware.org/?probe=a0a907bbb9) | Dec 13, 2021 |
| HP            | Pavilion g6                 | [71beb2c4f4](https://linux-hardware.org/?probe=71beb2c4f4) | Dec 13, 2021 |
| HP            | Pavilion g6                 | [f3bba6973b](https://linux-hardware.org/?probe=f3bba6973b) | Dec 13, 2021 |
| Lenovo        | V15 G2 ALC 82KD             | [d391c926e7](https://linux-hardware.org/?probe=d391c926e7) | Dec 13, 2021 |
| HP            | Pavilion x2 Detachable      | [2639de91f7](https://linux-hardware.org/?probe=2639de91f7) | Dec 12, 2021 |
| HP            | Pavilion x2 Detachable      | [4d39f71d78](https://linux-hardware.org/?probe=4d39f71d78) | Dec 12, 2021 |
| MSI           | PS42 8RB                    | [539899e0d0](https://linux-hardware.org/?probe=539899e0d0) | Dec 12, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | [0fb07d458a](https://linux-hardware.org/?probe=0fb07d458a) | Dec 12, 2021 |
| Dell          | XPS 15 7590                 | [c6cd419023](https://linux-hardware.org/?probe=c6cd419023) | Dec 10, 2021 |
| Razer         | Blade                       | [4fb43417d3](https://linux-hardware.org/?probe=4fb43417d3) | Dec 09, 2021 |
| Lenovo        | ThinkPad X201 Tablet 311... | [31e281d91b](https://linux-hardware.org/?probe=31e281d91b) | Dec 09, 2021 |
| HP            | 620                         | [7612676b9a](https://linux-hardware.org/?probe=7612676b9a) | Dec 08, 2021 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [993ad702ec](https://linux-hardware.org/?probe=993ad702ec) | Dec 08, 2021 |
| LG Electro... | 15Z95N-G.AA78B              | [b1dc899c99](https://linux-hardware.org/?probe=b1dc899c99) | Dec 07, 2021 |
| Unknown       | Unknown                     | [2070780ca9](https://linux-hardware.org/?probe=2070780ca9) | Dec 07, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X430... | [8ef0bff5e1](https://linux-hardware.org/?probe=8ef0bff5e1) | Dec 07, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S0S... | [027f8c5de6](https://linux-hardware.org/?probe=027f8c5de6) | Dec 06, 2021 |
| Lenovo        | ThinkPad L390 20NR0013SP    | [493a0cc63e](https://linux-hardware.org/?probe=493a0cc63e) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire V3-571G              | [3acb23e27c](https://linux-hardware.org/?probe=3acb23e27c) | Dec 05, 2021 |
| Chuwi         | GemiBook Pro                | [664d1dc278](https://linux-hardware.org/?probe=664d1dc278) | Dec 04, 2021 |
| HP            | ENVY Laptop 17-ce1xxx       | [dfc664e15c](https://linux-hardware.org/?probe=dfc664e15c) | Dec 03, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [0bf68cd7ca](https://linux-hardware.org/?probe=0bf68cd7ca) | Dec 03, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [a662735265](https://linux-hardware.org/?probe=a662735265) | Dec 03, 2021 |
| MSI           | Prestige 14 A11SCX          | [4a80117f70](https://linux-hardware.org/?probe=4a80117f70) | Dec 03, 2021 |
| HP            | Notebook                    | [0582d239e9](https://linux-hardware.org/?probe=0582d239e9) | Dec 03, 2021 |
| Medion        | Akoya E1317T                | [0d8103d7b7](https://linux-hardware.org/?probe=0d8103d7b7) | Dec 02, 2021 |
| Toshiba       | Satellite L870-196          | [15ed850b16](https://linux-hardware.org/?probe=15ed850b16) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [1a9657cd2d](https://linux-hardware.org/?probe=1a9657cd2d) | Dec 02, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [f5bb8c7988](https://linux-hardware.org/?probe=f5bb8c7988) | Dec 02, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [2f41cc3d6c](https://linux-hardware.org/?probe=2f41cc3d6c) | Dec 02, 2021 |
| Primux        | 15R5A                       | [3aef7d25e8](https://linux-hardware.org/?probe=3aef7d25e8) | Dec 01, 2021 |
| MSI           | Prestige 15 A11SCS          | [1de5756d09](https://linux-hardware.org/?probe=1de5756d09) | Dec 01, 2021 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | [933ffd0145](https://linux-hardware.org/?probe=933ffd0145) | Dec 01, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [6728a312c9](https://linux-hardware.org/?probe=6728a312c9) | Dec 01, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | [c178662e84](https://linux-hardware.org/?probe=c178662e84) | Dec 01, 2021 |
| HP            | Laptop 15s-eq1xxx           | [9b11575394](https://linux-hardware.org/?probe=9b11575394) | Dec 01, 2021 |
| Lenovo        | IdeaPad 3 14ALC6 82KT       | [ecec60b455](https://linux-hardware.org/?probe=ecec60b455) | Dec 01, 2021 |
| Acer          | Aspire 5610                 | [853aee060d](https://linux-hardware.org/?probe=853aee060d) | Nov 28, 2021 |
| Acer          | Extensa 5635ZG              | [cb88e7d734](https://linux-hardware.org/?probe=cb88e7d734) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [911b855817](https://linux-hardware.org/?probe=911b855817) | Nov 28, 2021 |
| Chuwi         | GemiBook                    | [b8f87029fa](https://linux-hardware.org/?probe=b8f87029fa) | Nov 28, 2021 |
| Apple         | MacBookPro9,2               | [65ba69012d](https://linux-hardware.org/?probe=65ba69012d) | Nov 28, 2021 |
| HP            | Laptop 15s-fq2xxx           | [d559f82ee3](https://linux-hardware.org/?probe=d559f82ee3) | Nov 28, 2021 |
| Sony          | VGN-FE31B                   | [9c79f90f8d](https://linux-hardware.org/?probe=9c79f90f8d) | Nov 27, 2021 |
| Apple         | MacBookPro8,2               | [d9d656a35c](https://linux-hardware.org/?probe=d9d656a35c) | Nov 27, 2021 |
| MSI           | GF63 Thin 9SC               | [c3a2a79baa](https://linux-hardware.org/?probe=c3a2a79baa) | Nov 26, 2021 |
| Dell          | Studio 1555                 | [7de9da3676](https://linux-hardware.org/?probe=7de9da3676) | Nov 26, 2021 |
| Toshiba       | Satellite A300              | [fc12a71dfe](https://linux-hardware.org/?probe=fc12a71dfe) | Nov 26, 2021 |
| Lenovo        | B50-10 80QR                 | [5e57df0c06](https://linux-hardware.org/?probe=5e57df0c06) | Nov 26, 2021 |
| HP            | Presario CQ57               | [3d75609ad0](https://linux-hardware.org/?probe=3d75609ad0) | Nov 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [56195a9398](https://linux-hardware.org/?probe=56195a9398) | Nov 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [02d3578274](https://linux-hardware.org/?probe=02d3578274) | Nov 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 2 20X3C... | [7959daf419](https://linux-hardware.org/?probe=7959daf419) | Nov 26, 2021 |
| Acer          | Aspire A315-41              | [377c2f032d](https://linux-hardware.org/?probe=377c2f032d) | Nov 24, 2021 |
| Unknown       | Unknown                     | [b862ee20d9](https://linux-hardware.org/?probe=b862ee20d9) | Nov 24, 2021 |
| Unknown       | Unknown                     | [0555569b70](https://linux-hardware.org/?probe=0555569b70) | Nov 24, 2021 |
| HP            | OMEN by Laptop              | [54c37833db](https://linux-hardware.org/?probe=54c37833db) | Nov 23, 2021 |
| Acer          | Aspire 5610                 | [8fa3c5f33c](https://linux-hardware.org/?probe=8fa3c5f33c) | Nov 23, 2021 |
| Lenovo        | ThinkPad T530 2392AHG       | [b0bd22b9b3](https://linux-hardware.org/?probe=b0bd22b9b3) | Nov 23, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [f1620f693d](https://linux-hardware.org/?probe=f1620f693d) | Nov 22, 2021 |
| Dell          | Precision 5560              | [aa3dbdc6bb](https://linux-hardware.org/?probe=aa3dbdc6bb) | Nov 22, 2021 |
| Acer          | Predator PH315-52           | [ce6d0a4e47](https://linux-hardware.org/?probe=ce6d0a4e47) | Nov 22, 2021 |
| Lenovo        | V145-15AST 81MT             | [941396daf4](https://linux-hardware.org/?probe=941396daf4) | Nov 22, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [b7acd26b0b](https://linux-hardware.org/?probe=b7acd26b0b) | Nov 22, 2021 |
| Dell          | Vostro 1700                 | [86f23cb2f4](https://linux-hardware.org/?probe=86f23cb2f4) | Nov 22, 2021 |
| Toshiba       | PORTEGE R705                | [47688cd36a](https://linux-hardware.org/?probe=47688cd36a) | Nov 21, 2021 |
| HP            | ZBook Firefly 14 G7 Mobi... | [0dc4672364](https://linux-hardware.org/?probe=0dc4672364) | Nov 21, 2021 |
| Packard Be... | EasyNote TK85               | [84c8b3cd54](https://linux-hardware.org/?probe=84c8b3cd54) | Nov 21, 2021 |
| Medion        | P6687 MD60815               | [228a05b70f](https://linux-hardware.org/?probe=228a05b70f) | Nov 21, 2021 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [08b2395aa0](https://linux-hardware.org/?probe=08b2395aa0) | Nov 21, 2021 |
| Dell          | Vostro 1700                 | [2aee39d91c](https://linux-hardware.org/?probe=2aee39d91c) | Nov 21, 2021 |
| Notebook      | NL4x_NL5xLU                 | [c92420f30b](https://linux-hardware.org/?probe=c92420f30b) | Nov 20, 2021 |
| Apple         | MacBookPro5,4               | [ccd5a782d0](https://linux-hardware.org/?probe=ccd5a782d0) | Nov 20, 2021 |
| Toshiba       | Satellite A300              | [d07c2a84f3](https://linux-hardware.org/?probe=d07c2a84f3) | Nov 19, 2021 |
| Dell          | Inspiron 14 5410            | [4d36ab3db6](https://linux-hardware.org/?probe=4d36ab3db6) | Nov 19, 2021 |
| Dell          | Latitude 3510               | [9d4db04732](https://linux-hardware.org/?probe=9d4db04732) | Nov 19, 2021 |
| Chuwi         | CoreBook XPro               | [0052e1b593](https://linux-hardware.org/?probe=0052e1b593) | Nov 19, 2021 |
| Acer          | Aspire VN7-791              | [e99650cf11](https://linux-hardware.org/?probe=e99650cf11) | Nov 18, 2021 |
| Acer          | Aspire VN7-791              | [1a82a6615b](https://linux-hardware.org/?probe=1a82a6615b) | Nov 18, 2021 |
| Acer          | Aspire ES1-111M             | [7b2d514d80](https://linux-hardware.org/?probe=7b2d514d80) | Nov 18, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | [427ee1a6de](https://linux-hardware.org/?probe=427ee1a6de) | Nov 17, 2021 |
| Acer          | Swift SF315-41              | [6720bdb10e](https://linux-hardware.org/?probe=6720bdb10e) | Nov 16, 2021 |
| HP            | 250 G4 Notebook PC          | [795371d9ce](https://linux-hardware.org/?probe=795371d9ce) | Nov 15, 2021 |
| Acer          | Aspire 5733Z                | [4ad1aba70f](https://linux-hardware.org/?probe=4ad1aba70f) | Nov 15, 2021 |
| MSI           | GE75 Raider 10SF            | [140e781aa9](https://linux-hardware.org/?probe=140e781aa9) | Nov 14, 2021 |
| Timi          | A35S                        | [68a0b2e6bd](https://linux-hardware.org/?probe=68a0b2e6bd) | Nov 14, 2021 |
| HP            | Pavilion dv6                | [0f0cd3dd6d](https://linux-hardware.org/?probe=0f0cd3dd6d) | Nov 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [ce33b6d1ca](https://linux-hardware.org/?probe=ce33b6d1ca) | Nov 10, 2021 |
| HP            | Laptop 15s-fq2xxx           | [c8fb558bb7](https://linux-hardware.org/?probe=c8fb558bb7) | Nov 09, 2021 |
| Dell          | Vostro 5568                 | [8efc2ed27a](https://linux-hardware.org/?probe=8efc2ed27a) | Nov 08, 2021 |
| Dell          | Vostro 5568                 | [b247ac9f61](https://linux-hardware.org/?probe=b247ac9f61) | Nov 08, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c8b67f9143](https://linux-hardware.org/?probe=c8b67f9143) | Nov 08, 2021 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b6fee79f67](https://linux-hardware.org/?probe=b6fee79f67) | Nov 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [3f7d56c8c6](https://linux-hardware.org/?probe=3f7d56c8c6) | Nov 07, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [ade3eca2bc](https://linux-hardware.org/?probe=ade3eca2bc) | Nov 07, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [af116b7c35](https://linux-hardware.org/?probe=af116b7c35) | Nov 06, 2021 |
| Acer          | TravelMate 5720             | [8e19effec8](https://linux-hardware.org/?probe=8e19effec8) | Nov 06, 2021 |
| Apple         | MacBookPro6,2               | [bde89fd503](https://linux-hardware.org/?probe=bde89fd503) | Nov 06, 2021 |
| HP            | ENVY Notebook               | [bd814d20f6](https://linux-hardware.org/?probe=bd814d20f6) | Nov 05, 2021 |
| HP            | ZBook 14u G5                | [ec192642ba](https://linux-hardware.org/?probe=ec192642ba) | Nov 05, 2021 |
| HP            | Pavilion dv7                | [a271e1ffce](https://linux-hardware.org/?probe=a271e1ffce) | Nov 04, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [cee62f51d7](https://linux-hardware.org/?probe=cee62f51d7) | Nov 03, 2021 |
| ASUSTek       | X550VX                      | [5718178f4b](https://linux-hardware.org/?probe=5718178f4b) | Nov 03, 2021 |
| Acer          | AOA150                      | [dfb785e90a](https://linux-hardware.org/?probe=dfb785e90a) | Nov 03, 2021 |
| HUAWEI        | BOHK-WAX9X                  | [54b32173dd](https://linux-hardware.org/?probe=54b32173dd) | Nov 03, 2021 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | [bbb421a462](https://linux-hardware.org/?probe=bbb421a462) | Nov 03, 2021 |
| Acer          | Aspire 7750G                | [03654ef318](https://linux-hardware.org/?probe=03654ef318) | Nov 02, 2021 |
| HP            | ProBook 450 G8 Notebook ... | [f5a1f78297](https://linux-hardware.org/?probe=f5a1f78297) | Nov 02, 2021 |
| Samsung       | R40/R41                     | [5c44d1e88b](https://linux-hardware.org/?probe=5c44d1e88b) | Nov 01, 2021 |
| Samsung       | R40/R41                     | [186644e32e](https://linux-hardware.org/?probe=186644e32e) | Nov 01, 2021 |
| Packard Be... | EasyNote TJ66               | [9b324d7185](https://linux-hardware.org/?probe=9b324d7185) | Oct 31, 2021 |
| eMachines     | E720                        | [82e0c7193f](https://linux-hardware.org/?probe=82e0c7193f) | Oct 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [cfa4e16d46](https://linux-hardware.org/?probe=cfa4e16d46) | Oct 31, 2021 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [35234144fa](https://linux-hardware.org/?probe=35234144fa) | Oct 30, 2021 |
| HP            | Compaq 15                   | [22807cb857](https://linux-hardware.org/?probe=22807cb857) | Oct 30, 2021 |
| HP            | 250 G3                      | [870a2260ff](https://linux-hardware.org/?probe=870a2260ff) | Oct 30, 2021 |
| Unknown       | Unknown                     | [dd20de340c](https://linux-hardware.org/?probe=dd20de340c) | Oct 30, 2021 |
| HP            | Laptop 17-cn0xxx            | [78304b1155](https://linux-hardware.org/?probe=78304b1155) | Oct 29, 2021 |
| ASUSTek       | X550LD                      | [50b1b1a6c5](https://linux-hardware.org/?probe=50b1b1a6c5) | Oct 29, 2021 |
| HP            | OMEN Laptop 15-en1xxx       | [9f4e0e6da5](https://linux-hardware.org/?probe=9f4e0e6da5) | Oct 29, 2021 |
| HP            | EliteBook 850 G3            | [71f0d8f5bb](https://linux-hardware.org/?probe=71f0d8f5bb) | Oct 29, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Spain/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 377       | 15.07%  |
| Ubuntu 18.04       | 251       | 10.03%  |
| Debian 11          | 106       | 4.24%   |
| OpenMandriva 4.2   | 83        | 3.32%   |
| Ubuntu 22.04       | 64        | 2.56%   |
| KDE neon 20.04     | 63        | 2.52%   |
| OpenMandriva 4.3   | 47        | 1.88%   |
| Zorin 16           | 42        | 1.68%   |
| Arch               | 41        | 1.64%   |
| Ubuntu 20.10       | 39        | 1.56%   |
| Xubuntu 20.04      | 37        | 1.48%   |
| Linux Mint 20.3    | 37        | 1.48%   |
| Linux Mint 19.3    | 36        | 1.44%   |
| Debian 10          | 35        | 1.4%    |
| Ubuntu 19.10       | 34        | 1.36%   |
| Ubuntu 21.04       | 32        | 1.28%   |
| Ubuntu 19.04       | 32        | 1.28%   |
| Manjaro            | 31        | 1.24%   |
| Linux Mint 20.1    | 31        | 1.24%   |
| Linux Mint 20      | 30        | 1.2%    |
| Ubuntu 21.10       | 29        | 1.16%   |
| Kubuntu 20.04      | 28        | 1.12%   |
| Xubuntu 18.04      | 27        | 1.08%   |
| Linux Mint 20.2    | 26        | 1.04%   |
| Zorin 15           | 25        | 1%      |
| Fedora 35          | 25        | 1%      |
| Fedora 36          | 24        | 0.96%   |
| Fedora 34          | 24        | 0.96%   |
| Fedora 33          | 23        | 0.92%   |
| ROSA R10           | 22        | 0.88%   |
| Ubuntu 18.10       | 21        | 0.84%   |
| Pop!_OS 20.04      | 21        | 0.84%   |
| Arch Rolling       | 21        | 0.84%   |
| Pop!_OS 20.10      | 19        | 0.76%   |
| Linux Mint 19.2    | 17        | 0.68%   |
| Debian Testing     | 17        | 0.68%   |
| Ubuntu 16.04       | 16        | 0.64%   |
| Ubuntu MATE 20.04  | 15        | 0.6%    |
| BlackPanther 18.1  | 15        | 0.6%    |
| Ubuntu Unity 16.04 | 13        | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| Ubuntu        | 860       | 36.07%  |
| Linux Mint    | 192       | 8.05%   |
| Debian        | 165       | 6.92%   |
| OpenMandriva  | 142       | 5.96%   |
| Fedora        | 119       | 4.99%   |
| Endless       | 98        | 4.11%   |
| Manjaro       | 84        | 3.52%   |
| Xubuntu       | 72        | 3.02%   |
| Zorin         | 70        | 2.94%   |
| KDE neon      | 68        | 2.85%   |
| Pop!_OS       | 66        | 2.77%   |
| Arch          | 61        | 2.56%   |
| Kubuntu       | 56        | 2.35%   |
| ROSA          | 54        | 2.27%   |
| Ubuntu MATE   | 28        | 1.17%   |
| Elementary    | 23        | 0.96%   |
| Ubuntu Unity  | 21        | 0.88%   |
| openSUSE      | 19        | 0.8%    |
| BlackPanther  | 16        | 0.67%   |
| Lubuntu       | 14        | 0.59%   |
| Kali          | 13        | 0.55%   |
| Gentoo        | 13        | 0.55%   |
| ArcoLinux     | 12        | 0.5%    |
| Parrot        | 11        | 0.46%   |
| LMDE          | 11        | 0.46%   |
| SteamOS       | 9         | 0.38%   |
| EndeavourOS   | 9         | 0.38%   |
| MX            | 7         | 0.29%   |
| Ubuntu Budgie | 6         | 0.25%   |
| Clear Linux   | 6         | 0.25%   |
| Deepin        | 5         | 0.21%   |
| CentOS        | 5         | 0.21%   |
| RHEL          | 4         | 0.17%   |
| Solus         | 3         | 0.13%   |
| Reborn OS     | 3         | 0.13%   |
| Q4OS          | 3         | 0.13%   |
| Peppermint    | 3         | 0.13%   |
| Linux Lite    | 3         | 0.13%   |
| UbuntuDDE     | 2         | 0.08%   |
| LinuxFX       | 2         | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Notebooks | Percent |
|---------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002        | 81        | 3%      |
| 5.4.0-42-generic                | 48        | 1.78%   |
| 5.16.7-desktop-1omv4003         | 47        | 1.74%   |
| 5.10.0-8-amd64                  | 34        | 1.26%   |
| 5.4.0-58-generic                | 33        | 1.22%   |
| 5.3.0-28-generic                | 31        | 1.15%   |
| 5.4.0-54-generic                | 27        | 1%      |
| 5.4.0-52-generic                | 26        | 0.96%   |
| 5.4.0-26-generic                | 26        | 0.96%   |
| 5.0.0-37-generic                | 22        | 0.81%   |
| 5.3.0-46-generic                | 21        | 0.78%   |
| 5.3.0-40-generic                | 21        | 0.78%   |
| 5.11.0-27-generic               | 21        | 0.78%   |
| 5.10.0-18-amd64                 | 21        | 0.78%   |
| 5.4.0-48-generic                | 20        | 0.74%   |
| 5.4.0-65-generic                | 19        | 0.7%    |
| 5.15.0-52-generic               | 19        | 0.7%    |
| 5.11.0-41-generic               | 19        | 0.7%    |
| 5.4.0-72-generic                | 18        | 0.67%   |
| 5.4.0-40-generic                | 18        | 0.67%   |
| 5.15.0-48-generic               | 18        | 0.67%   |
| 5.11.0-43-generic               | 18        | 0.67%   |
| 5.0.0-32-generic                | 18        | 0.67%   |
| 5.8.0-44-generic                | 17        | 0.63%   |
| 5.4.0-19-generic                | 16        | 0.59%   |
| 5.3.0-45-generic                | 16        | 0.59%   |
| 5.8.0-14-generic                | 15        | 0.55%   |
| 5.4.0-29-generic                | 15        | 0.55%   |
| 5.15.0-47-generic               | 15        | 0.55%   |
| 5.13.0-28-generic               | 15        | 0.55%   |
| 5.8.0-43-generic                | 14        | 0.52%   |
| 5.4.0-70-generic                | 14        | 0.52%   |
| 5.4.0-53-generic                | 14        | 0.52%   |
| 5.3.0-51-generic                | 14        | 0.52%   |
| 5.3.0-42-generic                | 14        | 0.52%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 14        | 0.52%   |
| 5.4.0-91-generic                | 13        | 0.48%   |
| 5.4.0-37-generic                | 13        | 0.48%   |
| 5.13.0-27-generic               | 13        | 0.48%   |
| 5.8.0-48-generic                | 12        | 0.44%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 523       | 20.49%  |
| 4.15.0  | 200       | 7.83%   |
| 5.11.0  | 163       | 6.38%   |
| 5.3.0   | 153       | 5.99%   |
| 5.8.0   | 150       | 5.88%   |
| 5.10.0  | 129       | 5.05%   |
| 5.15.0  | 126       | 4.94%   |
| 5.13.0  | 120       | 4.7%    |
| 5.0.0   | 109       | 4.27%   |
| 5.10.14 | 82        | 3.21%   |
| 4.18.0  | 71        | 2.78%   |
| 5.16.7  | 51        | 2%      |
| 4.19.0  | 40        | 1.57%   |
| 5.19.0  | 15        | 0.59%   |
| 4.9.60  | 15        | 0.59%   |
| 5.14.0  | 14        | 0.55%   |
| 4.4.0   | 13        | 0.51%   |
| 4.18.16 | 13        | 0.51%   |
| 5.9.16  | 10        | 0.39%   |
| 5.18.0  | 10        | 0.39%   |
| 5.3.18  | 7         | 0.27%   |
| 5.17.5  | 7         | 0.27%   |
| 5.17.1  | 7         | 0.27%   |
| 5.16.0  | 7         | 0.27%   |
| 5.13.12 | 7         | 0.27%   |
| 5.11.12 | 7         | 0.27%   |
| 5.9.0   | 6         | 0.24%   |
| 5.16.11 | 6         | 0.24%   |
| 5.12.4  | 6         | 0.24%   |
| 5.7.0   | 5         | 0.2%    |
| 5.19.2  | 5         | 0.2%    |
| 5.16.9  | 5         | 0.2%    |
| 5.15.12 | 5         | 0.2%    |
| 5.10.7  | 5         | 0.2%    |
| 4.9.20  | 5         | 0.2%    |
| 4.9.0   | 5         | 0.2%    |
| 4.16.0  | 5         | 0.2%    |
| 6.0.2   | 4         | 0.16%   |
| 5.7.9   | 4         | 0.16%   |
| 5.7.1   | 4         | 0.16%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 554       | 21.92%  |
| 5.10    | 248       | 9.81%   |
| 4.15    | 200       | 7.91%   |
| 5.11    | 191       | 7.56%   |
| 5.8     | 176       | 6.96%   |
| 5.15    | 173       | 6.85%   |
| 5.3     | 168       | 6.65%   |
| 5.13    | 140       | 5.54%   |
| 5.0     | 111       | 4.39%   |
| 5.16    | 86        | 3.4%    |
| 4.18    | 84        | 3.32%   |
| 4.19    | 48        | 1.9%    |
| 5.19    | 44        | 1.74%   |
| 5.14    | 38        | 1.5%    |
| 4.9     | 38        | 1.5%    |
| 5.18    | 32        | 1.27%   |
| 5.9     | 29        | 1.15%   |
| 5.17    | 28        | 1.11%   |
| 5.6     | 25        | 0.99%   |
| 5.7     | 24        | 0.95%   |
| 5.12    | 23        | 0.91%   |
| 5.5     | 14        | 0.55%   |
| 4.4     | 14        | 0.55%   |
| 6.0     | 9         | 0.36%   |
| 4.16    | 5         | 0.2%    |
| 5.2     | 4         | 0.16%   |
| 4.1     | 4         | 0.16%   |
| 3.10    | 4         | 0.16%   |
| 5.1     | 3         | 0.12%   |
| 4.20    | 3         | 0.12%   |
| 4.13    | 3         | 0.12%   |
| 6.1     | 1         | 0.04%   |
| 4.8     | 1         | 0.04%   |
| 4.17    | 1         | 0.04%   |
| 3.16    | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 2195      | 94.98%  |
| i686   | 116       | 5.02%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 1065      | 43.95%  |
| KDE5            | 372       | 15.35%  |
| Unknown         | 320       | 13.21%  |
| XFCE            | 186       | 7.68%   |
| X-Cinnamon      | 144       | 5.94%   |
| KDE             | 76        | 3.14%   |
| MATE            | 75        | 3.1%    |
| Cinnamon        | 28        | 1.16%   |
| Pantheon        | 22        | 0.91%   |
| KDE4            | 22        | 0.91%   |
| Unity           | 20        | 0.83%   |
| LXQt            | 18        | 0.74%   |
| LXDE            | 14        | 0.58%   |
| i3              | 14        | 0.58%   |
| GNOME Flashback | 10        | 0.41%   |
| Budgie          | 10        | 0.41%   |
| Deepin          | 9         | 0.37%   |
| openbox         | 4         | 0.17%   |
| GNOME Classic   | 2         | 0.08%   |
| DWM             | 2         | 0.08%   |
| bspwm           | 2         | 0.08%   |
| trinity         | 1         | 0.04%   |
| river           | 1         | 0.04%   |
| qtile           | 1         | 0.04%   |
| Lubuntu         | 1         | 0.04%   |
| i3-with-shmlog  | 1         | 0.04%   |
| enlightenment   | 1         | 0.04%   |
| Cutefish        | 1         | 0.04%   |
| awesome         | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1898      | 79.88%  |
| Wayland | 281       | 11.83%  |
| Unknown | 182       | 7.66%   |
| Tty     | 15        | 0.63%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1313      | 54.87%  |
| SDDM    | 326       | 13.62%  |
| GDM     | 317       | 13.25%  |
| LightDM | 166       | 6.94%   |
| GDM3    | 146       | 6.1%    |
| TDM     | 90        | 3.76%   |
| KDM     | 23        | 0.96%   |
| XDM     | 7         | 0.29%   |
| Ly      | 3         | 0.13%   |
| SLiM    | 2         | 0.08%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang           | Notebooks | Percent |
|----------------|-----------|---------|
| es_ES          | 1357      | 57.21%  |
| en_US          | 399       | 16.82%  |
| Unknown        | 332       | 14%     |
| ca_ES          | 92        | 3.88%   |
| en_GB          | 55        | 2.32%   |
| C              | 23        | 0.97%   |
| de_DE          | 17        | 0.72%   |
| gl_ES          | 11        | 0.46%   |
| fr_FR          | 9         | 0.38%   |
| eu_ES          | 9         | 0.38%   |
| ru_RU          | 8         | 0.34%   |
| it_IT          | 6         | 0.25%   |
| an_ES          | 6         | 0.25%   |
| es_MX          | 5         | 0.21%   |
| es_AR          | 5         | 0.21%   |
| pt_BR          | 4         | 0.17%   |
| ca_AD          | 4         | 0.17%   |
| fr_BE          | 3         | 0.13%   |
| en_AG          | 3         | 0.13%   |
| pl_PL          | 2         | 0.08%   |
| nl_NL          | 2         | 0.08%   |
| es_US          | 2         | 0.08%   |
| es_BO          | 2         | 0.08%   |
| en_IE          | 2         | 0.08%   |
| sp_SP          | 1         | 0.04%   |
| POSIX          | 1         | 0.04%   |
| nb_NO          | 1         | 0.04%   |
| fr_CH          | 1         | 0.04%   |
| et_EE          | 1         | 0.04%   |
| es_VE          | 1         | 0.04%   |
| es_PE          | 1         | 0.04%   |
| en_NZ          | 1         | 0.04%   |
| en_HK          | 1         | 0.04%   |
| en_CA          | 1         | 0.04%   |
| en_AU          | 1         | 0.04%   |
| de_CH          | 1         | 0.04%   |
| ca_ES@valencia | 1         | 0.04%   |
| C.UTF8         | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 1256      | 53.33%  |
| BIOS | 1099      | 46.67%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 1890      | 80.12%  |
| Overlay | 162       | 6.87%   |
| Btrfs   | 131       | 5.55%   |
| Unknown | 111       | 4.71%   |
| Xfs     | 31        | 1.31%   |
| Zfs     | 13        | 0.55%   |
| Ext2    | 9         | 0.38%   |
| Tmpfs   | 4         | 0.17%   |
| Ext3    | 3         | 0.13%   |
| Jfs     | 2         | 0.08%   |
| Aufs    | 2         | 0.08%   |
| F2fs    | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1414      | 60.02%  |
| GPT     | 710       | 30.14%  |
| MBR     | 232       | 9.85%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 2090      | 89.05%  |
| Yes       | 257       | 10.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1652      | 70.33%  |
| Yes       | 697       | 29.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 442       | 19.13%  |
| Lenovo              | 394       | 17.06%  |
| ASUSTek Computer    | 350       | 15.15%  |
| Acer                | 233       | 10.09%  |
| Dell                | 191       | 8.27%   |
| MSI                 | 141       | 6.1%    |
| Toshiba             | 98        | 4.24%   |
| Apple               | 55        | 2.38%   |
| Sony                | 35        | 1.52%   |
| Packard Bell        | 31        | 1.34%   |
| HUAWEI              | 28        | 1.21%   |
| Unknown             | 27        | 1.17%   |
| Notebook            | 25        | 1.08%   |
| Chuwi               | 25        | 1.08%   |
| SLIMBOOK            | 24        | 1.04%   |
| Samsung Electronics | 24        | 1.04%   |
| LG Electronics      | 18        | 0.78%   |
| Medion              | 13        | 0.56%   |
| Fujitsu             | 13        | 0.56%   |
| Timi                | 11        | 0.48%   |
| Fujitsu Siemens     | 11        | 0.48%   |
| Valve               | 9         | 0.39%   |
| eMachines           | 9         | 0.39%   |
| Teclast             | 7         | 0.3%    |
| Clevo               | 7         | 0.3%    |
| Dynabook            | 5         | 0.22%   |
| HONOR               | 4         | 0.17%   |
| Gigabyte Technology | 4         | 0.17%   |
| Intel               | 3         | 0.13%   |
| IBM                 | 3         | 0.13%   |
| Compal              | 3         | 0.13%   |
| TUXEDO              | 2         | 0.09%   |
| Thomson             | 2         | 0.09%   |
| TEKNOSERVICE        | 2         | 0.09%   |
| Razer               | 2         | 0.09%   |
| Qilive              | 2         | 0.09%   |
| PC Specialist       | 2         | 0.09%   |
| OEM                 | 2         | 0.09%   |
| Minix               | 2         | 0.09%   |
| INFINITY            | 2         | 0.09%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 46        | 1.99%   |
| HP Pavilion g6                             | 20        | 0.87%   |
| HP Pavilion dv6                            | 19        | 0.82%   |
| ASUS ZenBook UX431DA_UM431DA               | 18        | 0.78%   |
| HP Notebook                                | 16        | 0.69%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_R540MA | 15        | 0.65%   |
| Lenovo IdeaPad 330-15IKB 81DE              | 14        | 0.61%   |
| HP Laptop 15-da0xxx                        | 10        | 0.43%   |
| HP G62                                     | 10        | 0.43%   |
| Dell XPS 13 7390                           | 10        | 0.43%   |
| Valve Jupiter                              | 9         | 0.39%   |
| HP Laptop 15s-eq1xxx                       | 9         | 0.39%   |
| MSI Prestige 15 A11SCS                     | 8         | 0.35%   |
| Lenovo IdeaPad 3 15ITL6 82H8               | 8         | 0.35%   |
| HP Pavilion 15                             | 8         | 0.35%   |
| ASUS X540NA                                | 8         | 0.35%   |
| Lenovo IdeaPad S145-15AST 81N3             | 7         | 0.3%    |
| Lenovo G50-70 20351                        | 7         | 0.3%    |
| HP ProBook 450 G8 Notebook PC              | 7         | 0.3%    |
| HP Pavilion dv7                            | 7         | 0.3%    |
| HP Laptop 15s-fq1xxx                       | 7         | 0.3%    |
| ASUS X555LAB                               | 7         | 0.3%    |
| ASUS VivoBook 15_ASUS Laptop X540BA        | 7         | 0.3%    |
| Acer Aspire 5750G                          | 7         | 0.3%    |
| Acer Aspire 5738                           | 7         | 0.3%    |
| Lenovo Y520-15IKBN 80WK                    | 6         | 0.26%   |
| Lenovo IdeaPad 3 15ADA05 81W1              | 6         | 0.26%   |
| HUAWEI NBLK-WAX9X                          | 6         | 0.26%   |
| HP OMEN by Laptop                          | 6         | 0.26%   |
| HP Laptop 15-bw0xx                         | 6         | 0.26%   |
| HP 250 G7 Notebook PC                      | 6         | 0.26%   |
| HP 250 G6 Notebook PC                      | 6         | 0.26%   |
| Dell XPS 13 9370                           | 6         | 0.26%   |
| ASUS X550VX                                | 6         | 0.26%   |
| SLIMBOOK PROX15-AMD                        | 5         | 0.22%   |
| MSI Prestige 15 A10SC                      | 5         | 0.22%   |
| Lenovo Z50-70 20354                        | 5         | 0.22%   |
| Lenovo Legion Y530-15ICH 81FV              | 5         | 0.22%   |
| HUAWEI BOHK-WAX9X                          | 5         | 0.22%   |
| HP Stream Notebook PC 13                   | 5         | 0.22%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 170       | 7.36%   |
| Lenovo ThinkPad       | 149       | 6.45%   |
| Lenovo IdeaPad        | 114       | 4.94%   |
| HP Pavilion           | 113       | 4.89%   |
| Dell Latitude         | 79        | 3.42%   |
| Toshiba Satellite     | 78        | 3.38%   |
| HP Laptop             | 64        | 2.77%   |
| ASUS VivoBook         | 63        | 2.73%   |
| HP EliteBook          | 50        | 2.16%   |
| Dell XPS              | 47        | 2.03%   |
| Unknown               | 46        | 1.99%   |
| HP Compaq             | 36        | 1.56%   |
| HP ProBook            | 35        | 1.52%   |
| Dell Inspiron         | 31        | 1.34%   |
| ASUS ZenBook          | 30        | 1.3%    |
| Packard Bell EasyNote | 28        | 1.21%   |
| HP 250                | 28        | 1.21%   |
| MSI Prestige          | 24        | 1.04%   |
| ASUS ROG              | 23        | 1%      |
| MSI Modern            | 16        | 0.69%   |
| Lenovo Legion         | 16        | 0.69%   |
| HP OMEN               | 16        | 0.69%   |
| HP Notebook           | 16        | 0.69%   |
| Acer TravelMate       | 16        | 0.69%   |
| Acer Extensa          | 16        | 0.69%   |
| Lenovo ThinkBook      | 15        | 0.65%   |
| ASUS TUF              | 14        | 0.61%   |
| HP ENVY               | 13        | 0.56%   |
| Fujitsu LIFEBOOK      | 12        | 0.52%   |
| ASUS ASUS             | 12        | 0.52%   |
| Dell Vostro           | 11        | 0.48%   |
| Lenovo Yoga           | 10        | 0.43%   |
| HP G62                | 10        | 0.43%   |
| Valve Jupiter         | 9         | 0.39%   |
| Toshiba PORTEGE       | 8         | 0.35%   |
| Chuwi GemiBook        | 8         | 0.35%   |
| ASUS X540NA           | 8         | 0.35%   |
| Apple MacBookPro8     | 8         | 0.35%   |
| Apple MacBookPro11    | 8         | 0.35%   |
| Toshiba TECRA         | 7         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2018    | 248       | 10.74%  |
| 2019    | 235       | 10.17%  |
| 2020    | 226       | 9.78%   |
| 2014    | 163       | 7.06%   |
| 2021    | 152       | 6.58%   |
| 2015    | 151       | 6.54%   |
| 2011    | 149       | 6.45%   |
| 2017    | 139       | 6.02%   |
| 2010    | 124       | 5.37%   |
| 2008    | 124       | 5.37%   |
| 2013    | 123       | 5.32%   |
| 2012    | 114       | 4.94%   |
| 2016    | 103       | 4.46%   |
| 2009    | 98        | 4.24%   |
| 2007    | 75        | 3.25%   |
| 2022    | 35        | 1.52%   |
| 2006    | 28        | 1.21%   |
| 2005    | 10        | 0.43%   |
| 2004    | 5         | 0.22%   |
| 2003    | 3         | 0.13%   |
| Unknown | 3         | 0.13%   |
| 2002    | 1         | 0.04%   |
| 2001    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 2310      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 2118      | 91.02%  |
| Enabled  | 209       | 8.98%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2305      | 99.78%  |
| Yes  | 5         | 0.22%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 595       | 25.51%  |
| 3.01-4.0    | 542       | 23.24%  |
| 16.01-24.0  | 421       | 18.05%  |
| 8.01-16.0   | 419       | 17.97%  |
| 1.01-2.0    | 124       | 5.32%   |
| 32.01-64.0  | 121       | 5.19%   |
| 2.01-3.0    | 46        | 1.97%   |
| 0.51-1.0    | 41        | 1.76%   |
| 64.01-256.0 | 12        | 0.51%   |
| 24.01-32.0  | 9         | 0.39%   |
| 0.01-0.5    | 2         | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 1012      | 39.86%  |
| 2.01-3.0   | 659       | 25.96%  |
| 4.01-8.0   | 291       | 11.46%  |
| 3.01-4.0   | 262       | 10.32%  |
| 0.51-1.0   | 209       | 8.23%   |
| 8.01-16.0  | 79        | 3.11%   |
| 0.01-0.5   | 23        | 0.91%   |
| 24.01-32.0 | 2         | 0.08%   |
| 16.01-24.0 | 2         | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1781      | 75.95%  |
| 2      | 488       | 20.81%  |
| 3      | 50        | 2.13%   |
| 0      | 21        | 0.9%    |
| 4      | 3         | 0.13%   |
| 5      | 2         | 0.09%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1458      | 62.82%  |
| Yes       | 863       | 37.18%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1871      | 80.68%  |
| No        | 448       | 19.32%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 2262      | 97.92%  |
| No        | 48        | 2.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1689      | 72.46%  |
| No        | 642       | 27.54%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Spain   | 2310      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                       | Notebooks | Percent |
|----------------------------|-----------|---------|
| Madrid                     | 381       | 15.19%  |
| Barcelona                  | 270       | 10.77%  |
| Seville                    | 89        | 3.55%   |
| Valencia                   | 77        | 3.07%   |
| Zaragoza                   | 40        | 1.59%   |
| Granada                    | 36        | 1.44%   |
| Alcobendas                 | 30        | 1.2%    |
| Palma                      | 29        | 1.16%   |
| Málaga                    | 29        | 1.16%   |
| Sabadell                   | 27        | 1.08%   |
| Vigo                       | 24        | 0.96%   |
| Córdoba                   | 22        | 0.88%   |
| Valladolid                 | 21        | 0.84%   |
| Alcalá de Henares         | 20        | 0.8%    |
| Pamplona                   | 19        | 0.76%   |
| Bilbao                     | 19        | 0.76%   |
| Las Palmas de Gran Canaria | 18        | 0.72%   |
| Santiago de Compostela     | 17        | 0.68%   |
| Donostia / San Sebastian   | 17        | 0.68%   |
| Alicante                   | 16        | 0.64%   |
| A Coruña                  | 16        | 0.64%   |
| León                      | 15        | 0.6%    |
| Gijón                     | 15        | 0.6%    |
| Mostoles                   | 14        | 0.56%   |
| Murcia                     | 13        | 0.52%   |
| Burgos                     | 13        | 0.52%   |
| Barakaldo                  | 13        | 0.52%   |
| Vitoria-Gasteiz            | 12        | 0.48%   |
| Reus                       | 12        | 0.48%   |
| Oviedo                     | 12        | 0.48%   |
| Getxo                      | 11        | 0.44%   |
| Salamanca                  | 10        | 0.4%    |
| Pontevedra                 | 10        | 0.4%    |
| Ourense                    | 10        | 0.4%    |
| Cartagena                  | 10        | 0.4%    |
| Almería                   | 10        | 0.4%    |
| Alcorcón                  | 10        | 0.4%    |
| Albacete                   | 10        | 0.4%    |
| Santander                  | 9         | 0.36%   |
| Montornès del Vallès     | 9         | 0.36%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Notebooks | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 382       | 466    | 13.78%  |
| WDC                       | 315       | 390    | 11.36%  |
| Seagate                   | 298       | 355    | 10.75%  |
| Kingston                  | 285       | 361    | 10.28%  |
| Toshiba                   | 254       | 313    | 9.16%   |
| SanDisk                   | 183       | 230    | 6.6%    |
| Unknown                   | 137       | 177    | 4.94%   |
| SK hynix                  | 123       | 148    | 4.44%   |
| Hitachi                   | 110       | 131    | 3.97%   |
| Intel                     | 88        | 116    | 3.17%   |
| HGST                      | 88        | 109    | 3.17%   |
| Crucial                   | 81        | 97     | 2.92%   |
| Micron Technology         | 75        | 86     | 2.7%    |
| Fujitsu                   | 32        | 36     | 1.15%   |
| KIOXIA                    | 28        | 32     | 1.01%   |
| Phison                    | 23        | 25     | 0.83%   |
| China                     | 22        | 33     | 0.79%   |
| Apple                     | 19        | 26     | 0.69%   |
| LITEON                    | 16        | 17     | 0.58%   |
| KingSpec                  | 14        | 18     | 0.5%    |
| Netac                     | 13        | 19     | 0.47%   |
| A-DATA Technology         | 11        | 13     | 0.4%    |
| Micron/Crucial Technology | 10        | 11     | 0.36%   |
| OCZ                       | 8         | 9      | 0.29%   |
| JMicron Technology        | 8         | 8      | 0.29%   |
| Transcend                 | 7         | 13     | 0.25%   |
| USB30                     | 6         | 7      | 0.22%   |
| PNY                       | 6         | 10     | 0.22%   |
| FORESEE                   | 6         | 7      | 0.22%   |
| Teclast                   | 5         | 5      | 0.18%   |
| Patriot                   | 5         | 6      | 0.18%   |
| KingDian                  | 5         | 5      | 0.18%   |
| Unknown                   | 5         | 5      | 0.18%   |
| LITEONIT                  | 4         | 5      | 0.14%   |
| EMTEC                     | 4         | 4      | 0.14%   |
| Corsair                   | 4         | 5      | 0.14%   |
| USB3.0                    | 3         | 3      | 0.11%   |
| Union Memory (Shenzhen)   | 3         | 3      | 0.11%   |
| Union Memory              | 3         | 3      | 0.11%   |
| TCSUNBOW                  | 3         | 3      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD        | 104       | 3.64%   |
| Seagate ST500LT012-1DG142 500GB        | 38        | 1.33%   |
| Kingston SA400S37480G 480GB SSD        | 35        | 1.23%   |
| Unknown MMC Card  32GB                 | 34        | 1.19%   |
| SK hynix NVMe SSD Drive 512GB          | 34        | 1.19%   |
| Samsung NVMe SSD Drive 512GB           | 31        | 1.09%   |
| HGST HTS721010A9E630 1TB               | 31        | 1.09%   |
| Unknown MMC Card  64GB                 | 29        | 1.02%   |
| Toshiba MQ01ABF050 500GB               | 29        | 1.02%   |
| Toshiba MQ01ABD100 1TB                 | 28        | 0.98%   |
| Seagate ST9500325AS 500GB              | 28        | 0.98%   |
| Seagate ST1000LM024 HN-M101MBB 1TB     | 27        | 0.95%   |
| Toshiba MQ04ABF100 1TB                 | 26        | 0.91%   |
| SanDisk NVMe SSD Drive 512GB           | 26        | 0.91%   |
| Seagate ST1000LM035-1RK172 1TB         | 25        | 0.88%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 22        | 0.77%   |
| Intel NVMe SSD Drive 512GB             | 21        | 0.74%   |
| Toshiba MQ01ABD050 500GB               | 19        | 0.67%   |
| Samsung SSD 860 EVO 500GB              | 19        | 0.67%   |
| Samsung SSD 850 EVO 250GB              | 19        | 0.67%   |
| Kingston RBUSC180DS37256GJ 256GB SSD   | 19        | 0.67%   |
| WDC WD10JPVX-22JC3T0 1TB               | 17        | 0.6%    |
| Kingston SUV400S37240G 240GB SSD       | 17        | 0.6%    |
| Kingston SA400S37120G 120GB SSD        | 17        | 0.6%    |
| SanDisk SSD PLUS 480GB                 | 16        | 0.56%   |
| SanDisk NVMe SSD Drive 256GB           | 16        | 0.56%   |
| HGST HTS545050A7E680 500GB             | 16        | 0.56%   |
| HGST HTS541010A9E680 1TB               | 16        | 0.56%   |
| Unknown MMC Card  128GB                | 14        | 0.49%   |
| Seagate ST1000LM049-2GH172 1TB         | 13        | 0.46%   |
| Samsung SSD 850 EVO 500GB              | 13        | 0.46%   |
| Micron NVMe SSD Drive 512GB            | 13        | 0.46%   |
| Crucial CT500MX500SSD1 500GB           | 13        | 0.46%   |
| SK hynix NVMe SSD Drive 256GB          | 11        | 0.39%   |
| Seagate Expansion 2TB                  | 11        | 0.39%   |
| SanDisk SSD PLUS 1000GB                | 11        | 0.39%   |
| SanDisk NVMe SSD Drive 1024GB          | 11        | 0.39%   |
| Samsung NVMe SSD Drive 1024GB          | 11        | 0.39%   |
| Seagate ST9500420AS 500GB              | 10        | 0.35%   |
| WDC WD5000LPVX-22V0TT0 500GB           | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 296       | 353    | 31.32%  |
| WDC                 | 205       | 249    | 21.69%  |
| Toshiba             | 174       | 203    | 18.41%  |
| Hitachi             | 110       | 131    | 11.64%  |
| HGST                | 88        | 109    | 9.31%   |
| Fujitsu             | 32        | 36     | 3.39%   |
| Samsung Electronics | 23        | 24     | 2.43%   |
| Unknown             | 5         | 8      | 0.53%   |
| USB3.0              | 3         | 3      | 0.32%   |
| Apple               | 3         | 3      | 0.32%   |
| USB                 | 1         | 1      | 0.11%   |
| PHD 3.0             | 1         | 1      | 0.11%   |
| OEM                 | 1         | 1      | 0.11%   |
| Maxone              | 1         | 1      | 0.11%   |
| LaCie               | 1         | 1      | 0.11%   |
| IBM                 | 1         | 1      | 0.11%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 248       | 314    | 27.16%  |
| Samsung Electronics | 150       | 181    | 16.43%  |
| SanDisk             | 108       | 131    | 11.83%  |
| Crucial             | 73        | 87     | 8%      |
| Toshiba             | 38        | 48     | 4.16%   |
| WDC                 | 35        | 45     | 3.83%   |
| SK hynix            | 30        | 33     | 3.29%   |
| Micron Technology   | 29        | 35     | 3.18%   |
| China               | 22        | 33     | 2.41%   |
| Intel               | 19        | 32     | 2.08%   |
| LITEON              | 15        | 15     | 1.64%   |
| KingSpec            | 14        | 18     | 1.53%   |
| Netac               | 13        | 19     | 1.42%   |
| Apple               | 11        | 13     | 1.2%    |
| A-DATA Technology   | 9         | 11     | 0.99%   |
| OCZ                 | 8         | 9      | 0.88%   |
| USB30               | 6         | 7      | 0.66%   |
| Transcend           | 6         | 12     | 0.66%   |
| FORESEE             | 6         | 7      | 0.66%   |
| Teclast             | 5         | 5      | 0.55%   |
| PNY                 | 5         | 9      | 0.55%   |
| Patriot             | 4         | 5      | 0.44%   |
| LITEONIT            | 4         | 5      | 0.44%   |
| KingDian            | 4         | 4      | 0.44%   |
| Corsair             | 4         | 5      | 0.44%   |
| Unknown             | 3         | 3      | 0.33%   |
| Emtec               | 3         | 3      | 0.33%   |
| ASMT                | 3         | 3      | 0.33%   |
| TCSUNBOW            | 2         | 2      | 0.22%   |
| ShanDianZhe         | 2         | 2      | 0.22%   |
| Plextor             | 2         | 3      | 0.22%   |
| KIOXIA-EXCERIA      | 2         | 3      | 0.22%   |
| Dogfish             | 2         | 2      | 0.22%   |
| Unknown             | 2         | 2      | 0.22%   |
| Yeyian              | 1         | 1      | 0.11%   |
| W800S               | 1         | 2      | 0.11%   |
| Vaseky              | 1         | 1      | 0.11%   |
| Union Memory        | 1         | 1      | 0.11%   |
| SPCC                | 1         | 1      | 0.11%   |
| SOLIDATA            | 1         | 3      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 924       | 1125   | 34.68%  |
| SSD     | 859       | 1143   | 32.24%  |
| NVMe    | 718       | 934    | 26.95%  |
| MMC     | 135       | 174    | 5.07%   |
| Unknown | 28        | 33     | 1.05%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1589      | 2212   | 62.98%  |
| NVMe | 715       | 927    | 28.34%  |
| MMC  | 135       | 174    | 5.35%   |
| SAS  | 84        | 96     | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1286      | 1716   | 73.95%  |
| 0.51-1.0   | 404       | 493    | 23.23%  |
| 1.01-2.0   | 43        | 52     | 2.47%   |
| 3.01-4.0   | 4         | 5      | 0.23%   |
| 2.01-3.0   | 1         | 1      | 0.06%   |
| 4.01-10.0  | 1         | 1      | 0.06%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 760       | 31.63%  |
| 251-500        | 684       | 28.46%  |
| 501-1000       | 284       | 11.82%  |
| 51-100         | 187       | 7.78%   |
| 1-20           | 170       | 7.07%   |
| 21-50          | 119       | 4.95%   |
| 1001-2000      | 96        | 4%      |
| Unknown        | 50        | 2.08%   |
| 2001-3000      | 31        | 1.29%   |
| More than 3000 | 22        | 0.92%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 1061      | 42.12%  |
| 21-50          | 478       | 18.98%  |
| 101-250        | 346       | 13.74%  |
| 51-100         | 282       | 11.19%  |
| 251-500        | 173       | 6.87%   |
| 501-1000       | 89        | 3.53%   |
| Unknown        | 50        | 1.98%   |
| 1001-2000      | 25        | 0.99%   |
| 2001-3000      | 8         | 0.32%   |
| More than 3000 | 5         | 0.2%    |
| 0              | 2         | 0.08%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Notebooks | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB                | 6         | 7      | 4.51%   |
| Seagate ST9500420AS 500GB                | 4         | 4      | 3.01%   |
| Seagate ST9250827AS 250GB                | 4         | 4      | 3.01%   |
| Seagate ST500LT012-1DG142 500GB          | 4         | 4      | 3.01%   |
| SanDisk SSD PLUS 480GB                   | 4         | 5      | 3.01%   |
| HGST HTS545050A7E680 500GB               | 4         | 6      | 3.01%   |
| Seagate ST1000LM035-1RK172 1TB           | 3         | 3      | 2.26%   |
| Hitachi HTS545050A7E380 500GB            | 3         | 3      | 2.26%   |
| HGST HTS721010A9E630 1TB                 | 3         | 3      | 2.26%   |
| HGST HTS541010A9E680 1TB                 | 3         | 3      | 2.26%   |
| WDC WD5000BPVT-60HXZT3 500GB             | 2         | 2      | 1.5%    |
| Toshiba Q300. 240GB SSD                  | 2         | 2      | 1.5%    |
| Toshiba MK5076GSX 500GB                  | 2         | 2      | 1.5%    |
| Seagate ST500LM021-1KJ152 500GB          | 2         | 2      | 1.5%    |
| Seagate ST320LT012-9WS14C 320GB          | 2         | 2      | 1.5%    |
| Seagate ST1000LM024 HN-M101MBB 1TB       | 2         | 2      | 1.5%    |
| Intel SSDSC2BF180A5H SED 180GB           | 2         | 2      | 1.5%    |
| Fujitsu MHZ2250BH G2 250GB               | 2         | 2      | 1.5%    |
| WDC WDS240G2G0A-00JH30 240GB SSD         | 1         | 1      | 0.75%   |
| WDC WD7500BPVT-60HXZT1 752GB             | 1         | 1      | 0.75%   |
| WDC WD5000BEVT-22ZAT0 500GB              | 1         | 1      | 0.75%   |
| WDC WD3200BEVT-00A0RT0 320GB             | 1         | 1      | 0.75%   |
| WDC WD3200BEKT-60F3T1 320GB              | 1         | 2      | 0.75%   |
| WDC WD2500BEVS-60UST0 250GB              | 1         | 1      | 0.75%   |
| WDC WD2500BEVS-22UST0 250GB              | 1         | 1      | 0.75%   |
| WDC WD1600BEVT-60ZCT0 160GB              | 1         | 1      | 0.75%   |
| WDC WD1600BEVS-60RST0 160GB              | 1         | 1      | 0.75%   |
| WDC WD1600BEVS-22RST0 160GB              | 1         | 1      | 0.75%   |
| WDC WD1200BEVS-60UST0 120GB              | 1         | 1      | 0.75%   |
| WDC WD10JPCX-24UE4T0 1TB                 | 1         | 1      | 0.75%   |
| Toshiba THNSNK256GVN8 M.2 2280 256GB SSD | 1         | 1      | 0.75%   |
| Toshiba THNSNK256GCS8 SATA 256GB SSD     | 1         | 1      | 0.75%   |
| Toshiba THNSNJ256G8NY 256GB SSD          | 1         | 1      | 0.75%   |
| Toshiba MQ04ABF100 1TB                   | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD100 1TB                   | 1         | 1      | 0.75%   |
| Toshiba MQ01ABD075 752GB                 | 1         | 2      | 0.75%   |
| Toshiba MK8052GSX 80GB                   | 1         | 1      | 0.75%   |
| Toshiba MK5065GSXN 500GB                 | 1         | 1      | 0.75%   |
| Toshiba MK3256GSY 320GB                  | 1         | 1      | 0.75%   |
| Toshiba MK2575GSX 250GB                  | 1         | 1      | 0.75%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 40     | 28.57%  |
| Hitachi             | 18        | 19     | 13.53%  |
| Toshiba             | 17        | 18     | 12.78%  |
| WDC                 | 14        | 15     | 10.53%  |
| HGST                | 12        | 15     | 9.02%   |
| Samsung Electronics | 8         | 8      | 6.02%   |
| Intel               | 6         | 6      | 4.51%   |
| SanDisk             | 5         | 6      | 3.76%   |
| Kingston            | 4         | 5      | 3.01%   |
| Fujitsu             | 4         | 4      | 3.01%   |
| Micron Technology   | 2         | 2      | 1.5%    |
| Crucial             | 2         | 3      | 1.5%    |
| SK hynix            | 1         | 1      | 0.75%   |
| OCZ                 | 1         | 1      | 0.75%   |
| IBM                 | 1         | 1      | 0.75%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 38        | 40     | 37.25%  |
| Hitachi             | 18        | 19     | 17.65%  |
| WDC                 | 13        | 14     | 12.75%  |
| Toshiba             | 12        | 13     | 11.76%  |
| HGST                | 12        | 15     | 11.76%  |
| Samsung Electronics | 4         | 4      | 3.92%   |
| Fujitsu             | 4         | 4      | 3.92%   |
| IBM                 | 1         | 1      | 0.98%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 100       | 110    | 76.92%  |
| SSD  | 28        | 32     | 21.54%  |
| NVMe | 2         | 2      | 1.54%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                           | Notebooks | Drives | Percent |
|---------------------------------|-----------|--------|---------|
| Seagate ST500LT012-1DG142 500GB | 1         | 1      | 100%    |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 1         | 1      | 100%    |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1477      | 2221   | 60.78%  |
| Works    | 823       | 1043   | 33.87%  |
| Malfunc  | 129       | 144    | 5.31%   |
| Failed   | 1         | 1      | 0.04%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1646      | 62.23%  |
| AMD                              | 255       | 9.64%   |
| Samsung Electronics              | 233       | 8.81%   |
| SanDisk                          | 143       | 5.41%   |
| SK hynix                         | 87        | 3.29%   |
| Micron Technology                | 46        | 1.74%   |
| Toshiba America Info Systems     | 43        | 1.63%   |
| Kingston Technology Company      | 39        | 1.47%   |
| KIOXIA                           | 33        | 1.25%   |
| Phison Electronics               | 28        | 1.06%   |
| Nvidia                           | 24        | 0.91%   |
| Micron/Crucial Technology        | 16        | 0.6%    |
| Silicon Integrated Systems [SiS] | 13        | 0.49%   |
| Silicon Motion                   | 6         | 0.23%   |
| VIA Technologies                 | 5         | 0.19%   |
| JMicron Technology               | 5         | 0.19%   |
| Apple                            | 5         | 0.19%   |
| Union Memory (Shenzhen)          | 4         | 0.15%   |
| Solid State Storage Technology   | 3         | 0.11%   |
| O2 Micro                         | 2         | 0.08%   |
| MAXIO Technology (Hangzhou)      | 2         | 0.08%   |
| Lite-On Technology               | 2         | 0.08%   |
| ADATA Technology                 | 2         | 0.08%   |
| Silicon Image                    | 1         | 0.04%   |
| Lenovo                           | 1         | 0.04%   |
| Biwin Storage Technology         | 1         | 0.04%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 214       | 7.44%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 185       | 6.43%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 124       | 4.31%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 121       | 4.21%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 115       | 4%      |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 113       | 3.93%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 111       | 3.86%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 94        | 3.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 82        | 2.85%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 76        | 2.64%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 70        | 2.43%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 66        | 2.3%    |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 63        | 2.19%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 60        | 2.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 57        | 1.98%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 57        | 1.98%   |
| Samsung NVMe SSD Controller 980                                                | 55        | 1.91%   |
| Intel Volume Management Device NVMe RAID Controller                            | 55        | 1.91%   |
| Intel SSD 660P Series                                                          | 47        | 1.63%   |
| Micron Non-Volatile memory controller                                          | 46        | 1.6%    |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 43        | 1.5%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 35        | 1.22%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 35        | 1.22%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 30        | 1.04%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 29        | 1.01%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 28        | 0.97%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 28        | 0.97%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 27        | 0.94%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 27        | 0.94%   |
| SK hynix Gold P31 SSD                                                          | 26        | 0.9%    |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                             | 26        | 0.9%    |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                  | 26        | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 26        | 0.9%    |
| Intel Tiger Lake-LP SATA Controller                                            | 25        | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 24        | 0.83%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 22        | 0.77%   |
| Intel Comet Lake SATA AHCI Controller                                          | 22        | 0.77%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 22        | 0.77%   |
| Kingston Company U-SNS8154P3 NVMe SSD                                          | 21        | 0.73%   |
| SanDisk Non-Volatile memory controller                                         | 20        | 0.7%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1648      | 59.37%  |
| NVMe | 724       | 26.08%  |
| IDE  | 221       | 7.96%   |
| RAID | 183       | 6.59%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1934      | 83.72%  |
| AMD          | 375       | 16.23%  |
| CentaurHauls | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8750H CPU @ 2.20GHz             | 54        | 2.34%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 49        | 2.12%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 46        | 1.99%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 39        | 1.69%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 36        | 1.56%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 34        | 1.47%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 33        | 1.43%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 32        | 1.38%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 31        | 1.34%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 31        | 1.34%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 31        | 1.34%   |
| Intel Celeron N4000 CPU @ 1.10GHz             | 30        | 1.3%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 29        | 1.25%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 28        | 1.21%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 25        | 1.08%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 23        | 1%      |
| Intel Celeron CPU N2840 @ 2.16GHz             | 23        | 1%      |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 23        | 1%      |
| Intel Core i7-7500U CPU @ 2.70GHz             | 22        | 0.95%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 21        | 0.91%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 21        | 0.91%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 21        | 0.91%   |
| Intel Core i7-4510U CPU @ 2.00GHz             | 20        | 0.87%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 18        | 0.78%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 18        | 0.78%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 17        | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 17        | 0.74%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 17        | 0.74%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 17        | 0.74%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 17        | 0.74%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 16        | 0.69%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 15        | 0.65%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 15        | 0.65%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 14        | 0.61%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 14        | 0.61%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 14        | 0.61%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 14        | 0.61%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 14        | 0.61%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 14        | 0.61%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 14        | 0.61%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 566       | 24.49%  |
| Intel Core i5           | 475       | 20.55%  |
| Intel Celeron           | 177       | 7.66%   |
| Other                   | 170       | 7.36%   |
| Intel Core i3           | 170       | 7.36%   |
| Intel Core 2 Duo        | 147       | 6.36%   |
| AMD Ryzen 7             | 103       | 4.46%   |
| Intel Atom              | 88        | 3.81%   |
| AMD Ryzen 5             | 69        | 2.99%   |
| Intel Pentium           | 30        | 1.3%    |
| Intel Pentium Dual-Core | 28        | 1.21%   |
| Intel Pentium Dual      | 27        | 1.17%   |
| AMD A4                  | 25        | 1.08%   |
| AMD A6                  | 23        | 1%      |
| Intel Genuine           | 22        | 0.95%   |
| Intel Core 2            | 22        | 0.95%   |
| AMD E1                  | 18        | 0.78%   |
| AMD A8                  | 15        | 0.65%   |
| AMD Ryzen 7 PRO         | 10        | 0.43%   |
| AMD E                   | 10        | 0.43%   |
| Intel Pentium M         | 9         | 0.39%   |
| AMD Ryzen 3             | 9         | 0.39%   |
| AMD Athlon              | 9         | 0.39%   |
| AMD A10                 | 8         | 0.35%   |
| Intel Core i9           | 7         | 0.3%    |
| Intel Celeron M         | 7         | 0.3%    |
| AMD Ryzen 9             | 6         | 0.26%   |
| Intel Core m3           | 5         | 0.22%   |
| Intel Pentium 4         | 4         | 0.17%   |
| AMD Turion II Dual-Core | 4         | 0.17%   |
| AMD Turion 64 X2 Mobile | 4         | 0.17%   |
| AMD Turion 64 Mobile    | 3         | 0.13%   |
| AMD FX                  | 3         | 0.13%   |
| AMD Athlon II           | 3         | 0.13%   |
| AMD A12                 | 3         | 0.13%   |
| Intel Xeon              | 2         | 0.09%   |
| Intel Pentium Silver    | 2         | 0.09%   |
| Intel Core Duo          | 2         | 0.09%   |
| AMD Ryzen 5 PRO         | 2         | 0.09%   |
| AMD C-60                | 2         | 0.09%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1189      | 51.43%  |
| 4       | 726       | 31.4%   |
| 6       | 152       | 6.57%   |
| 8       | 125       | 5.41%   |
| 1       | 102       | 4.41%   |
| 14      | 9         | 0.39%   |
| 10      | 4         | 0.17%   |
| Unknown | 4         | 0.17%   |
| 12      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 2309      | 99.96%  |
| 2      | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 1610      | 69.64%  |
| 1       | 698       | 30.19%  |
| Unknown | 4         | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2200      | 94.66%  |
| 32-bit         | 56        | 2.41%   |
| Unknown        | 54        | 2.32%   |
| 64-bit         | 14        | 0.6%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 406       | 17.06%  |
| 0x206a7    | 127       | 5.34%   |
| 0x306a9    | 105       | 4.41%   |
| 0x806c1    | 89        | 3.74%   |
| 0x906ea    | 87        | 3.66%   |
| 0x806ea    | 84        | 3.53%   |
| 0x40651    | 83        | 3.49%   |
| 0x806ec    | 79        | 3.32%   |
| 0x1067a    | 71        | 2.98%   |
| 0x20655    | 70        | 2.94%   |
| 0x6fd      | 69        | 2.9%    |
| 0x406e3    | 68        | 2.86%   |
| 0x806e9    | 65        | 2.73%   |
| 0x306d4    | 63        | 2.65%   |
| 0x306c3    | 59        | 2.48%   |
| 0x30678    | 46        | 1.93%   |
| 0x706e5    | 35        | 1.47%   |
| 0x10676    | 35        | 1.47%   |
| 0xa0652    | 34        | 1.43%   |
| 0x706a1    | 34        | 1.43%   |
| 0x08108109 | 34        | 1.43%   |
| 0x06006705 | 30        | 1.26%   |
| 0x08108102 | 29        | 1.22%   |
| 0x20652    | 28        | 1.18%   |
| 0x506e3    | 26        | 1.09%   |
| 0x0a50000c | 26        | 1.09%   |
| 0x806eb    | 24        | 1.01%   |
| 0x906e9    | 23        | 0.97%   |
| 0x08600106 | 23        | 0.97%   |
| 0x506c9    | 22        | 0.92%   |
| 0x406c4    | 22        | 0.92%   |
| 0x406c3    | 20        | 0.84%   |
| 0x106ca    | 20        | 0.84%   |
| 0x106c2    | 19        | 0.8%    |
| 0x08600103 | 19        | 0.8%    |
| 0x706a8    | 17        | 0.71%   |
| 0x6f6      | 17        | 0.71%   |
| 0x08608103 | 13        | 0.55%   |
| 0x08600104 | 13        | 0.55%   |
| 0x0700010f | 13        | 0.55%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 432       | 18.7%   |
| Haswell          | 180       | 7.79%   |
| SandyBridge      | 146       | 6.32%   |
| Penryn           | 130       | 5.63%   |
| Core             | 126       | 5.45%   |
| IvyBridge        | 115       | 4.98%   |
| Skylake          | 113       | 4.89%   |
| TigerLake        | 110       | 4.76%   |
| Westmere         | 107       | 4.63%   |
| Silvermont       | 104       | 4.5%    |
| Broadwell        | 76        | 3.29%   |
| Zen+             | 70        | 3.03%   |
| Zen 2            | 65        | 2.81%   |
| Goldmont plus    | 60        | 2.6%    |
| Excavator        | 53        | 2.29%   |
| Bonnell          | 51        | 2.21%   |
| CometLake        | 49        | 2.12%   |
| IceLake          | 46        | 1.99%   |
| Unknown          | 41        | 1.77%   |
| Zen 3            | 36        | 1.56%   |
| P6               | 27        | 1.17%   |
| Goldmont         | 27        | 1.17%   |
| Puma             | 23        | 1%      |
| Jaguar           | 21        | 0.91%   |
| Zen              | 19        | 0.82%   |
| Bobcat           | 16        | 0.69%   |
| K8 Hammer        | 14        | 0.61%   |
| K10              | 13        | 0.56%   |
| Alderlake Hybrid | 9         | 0.39%   |
| Nehalem          | 8         | 0.35%   |
| Piledriver       | 6         | 0.26%   |
| NetBurst         | 5         | 0.22%   |
| Tremont          | 3         | 0.13%   |
| Steamroller      | 3         | 0.13%   |
| K8 & K10 hybrid  | 3         | 0.13%   |
| K10 Llano        | 3         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1716      | 58.27%  |
| Nvidia                           | 676       | 22.95%  |
| AMD                              | 540       | 18.34%  |
| Silicon Integrated Systems [SiS] | 8         | 0.27%   |
| VIA Technologies                 | 5         | 0.17%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 131       | 4.29%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 110       | 3.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 105       | 3.43%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 104       | 3.4%    |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 100       | 3.27%   |
| Intel UHD Graphics 620                                                                   | 92        | 3.01%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 81        | 2.65%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 76        | 2.49%   |
| Intel Core Processor Integrated Graphics Controller                                      | 75        | 2.45%   |
| Intel HD Graphics 620                                                                    | 71        | 2.32%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 69        | 2.26%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 67        | 2.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 66        | 2.16%   |
| Intel HD Graphics 5500                                                                   | 65        | 2.13%   |
| AMD Renoir                                                                               | 63        | 2.06%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 58        | 1.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 58        | 1.9%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 54        | 1.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 50        | 1.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 46        | 1.5%    |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 43        | 1.41%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 41        | 1.34%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 41        | 1.34%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 40        | 1.31%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 38        | 1.24%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 37        | 1.21%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 36        | 1.18%   |
| AMD Cezanne                                                                              | 35        | 1.14%   |
| Intel HD Graphics 530                                                                    | 34        | 1.11%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 28        | 0.92%   |
| Intel HD Graphics 630                                                                    | 27        | 0.88%   |
| Intel HD Graphics 500                                                                    | 25        | 0.82%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 23        | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 23        | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 23        | 0.75%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 22        | 0.72%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 22        | 0.72%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 21        | 0.69%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 20        | 0.65%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/545v]                                        | 20        | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1140      | 49.29%  |
| Intel + Nvidia | 495       | 21.4%   |
| 1 x AMD        | 370       | 16%     |
| 1 x Nvidia     | 120       | 5.19%   |
| Intel + AMD    | 80        | 3.46%   |
| AMD + Nvidia   | 58        | 2.51%   |
| 2 x AMD        | 31        | 1.34%   |
| 1 x SiS        | 8         | 0.35%   |
| 1 x VIA        | 5         | 0.22%   |
| 2 x Nvidia     | 4         | 0.17%   |
| Other          | 2         | 0.09%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1948      | 83.32%  |
| Proprietary | 316       | 13.52%  |
| Unknown     | 74        | 3.17%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1409      | 59.48%  |
| 0.01-0.5   | 303       | 12.79%  |
| 1.01-2.0   | 300       | 12.66%  |
| 3.01-4.0   | 170       | 7.18%   |
| 0.51-1.0   | 133       | 5.61%   |
| 5.01-6.0   | 33        | 1.39%   |
| 7.01-8.0   | 17        | 0.72%   |
| 2.01-3.0   | 3         | 0.13%   |
| 8.01-16.0  | 1         | 0.04%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 462       | 17.89%  |
| Chimei Innolux          | 413       | 15.99%  |
| LG Display              | 374       | 14.48%  |
| BOE                     | 274       | 10.61%  |
| Samsung Electronics     | 254       | 9.83%   |
| Chi Mei Optoelectronics | 77        | 2.98%   |
| Sharp                   | 73        | 2.83%   |
| Goldstar                | 67        | 2.59%   |
| Dell                    | 59        | 2.28%   |
| PANDA                   | 53        | 2.05%   |
| Apple                   | 53        | 2.05%   |
| Hewlett-Packard         | 52        | 2.01%   |
| LG Philips              | 38        | 1.47%   |
| Lenovo                  | 38        | 1.47%   |
| BenQ                    | 34        | 1.32%   |
| Acer                    | 25        | 0.97%   |
| Philips                 | 22        | 0.85%   |
| Ancor Communications    | 18        | 0.7%    |
| HannStar                | 17        | 0.66%   |
| AOC                     | 17        | 0.66%   |
| Sony                    | 15        | 0.58%   |
| InfoVision              | 14        | 0.54%   |
| ASUSTek Computer        | 10        | 0.39%   |
| CPT                     | 9         | 0.35%   |
| Quanta Display          | 7         | 0.27%   |
| Unknown                 | 6         | 0.23%   |
| CSO                     | 6         | 0.23%   |
| Seiko/Epson             | 5         | 0.19%   |
| Panasonic               | 5         | 0.19%   |
| ANX                     | 5         | 0.19%   |
| MSI                     | 4         | 0.15%   |
| Analogix                | 4         | 0.15%   |
| ViewSonic               | 3         | 0.12%   |
| Toshiba                 | 3         | 0.12%   |
| TMX                     | 3         | 0.12%   |
| Mi                      | 3         | 0.12%   |
| Hitachi                 | 3         | 0.12%   |
| AGO                     | 3         | 0.12%   |
| ___                     | 2         | 0.08%   |
| Unknown (XXX)           | 2         | 0.08%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 62        | 2.37%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 32        | 1.22%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 26        | 1%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 26        | 1%      |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 23        | 0.88%   |
| PANDA LCD Monitor NCP0035 1920x1080 309x174mm 14.0-inch                  | 21        | 0.8%    |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 21        | 0.8%    |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 18        | 0.69%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 18        | 0.69%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 16        | 0.61%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 16        | 0.61%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 15        | 0.57%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch         | 14        | 0.54%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 14        | 0.54%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 14        | 0.54%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 13        | 0.5%    |
| LG Display LCD Monitor LGD045C 1366x768 345x194mm 15.6-inch              | 12        | 0.46%   |
| LG Display LCD Monitor LGD0456 1366x768 344x194mm 15.5-inch              | 12        | 0.46%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 12        | 0.46%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 12        | 0.46%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 11        | 0.42%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 11        | 0.42%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch         | 11        | 0.42%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 11        | 0.42%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch             | 10        | 0.38%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15F4 1920x1080 344x193mm 15.5-inch         | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch          | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 10        | 0.38%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 10        | 0.38%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                    | 10        | 0.38%   |
| Samsung Electronics LCD Monitor SEC3945 1280x800 331x207mm 15.4-inch     | 9         | 0.34%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 9         | 0.34%   |
| LG Display LCD Monitor LGD0259 1920x1080 345x194mm 15.6-inch             | 9         | 0.34%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch          | 9         | 0.34%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 8         | 0.31%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 8         | 0.31%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 8         | 0.31%   |
| AU Optronics LCD Monitor AUO8174 1280x800 331x207mm 15.4-inch            | 8         | 0.31%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 968       | 40.17%  |
| 1366x768 (WXGA)    | 825       | 34.23%  |
| 1280x800 (WXGA)    | 146       | 6.06%   |
| 1600x900 (HD+)     | 66        | 2.74%   |
| 3840x2160 (4K)     | 64        | 2.66%   |
| 1440x900 (WXGA+)   | 56        | 2.32%   |
| 2560x1440 (QHD)    | 41        | 1.7%    |
| 1024x600           | 37        | 1.54%   |
| 1280x1024 (SXGA)   | 25        | 1.04%   |
| 1920x1200 (WUXGA)  | 22        | 0.91%   |
| 1680x1050 (WSXGA+) | 22        | 0.91%   |
| 2560x1600          | 17        | 0.71%   |
| 2160x1440          | 16        | 0.66%   |
| 3440x1440          | 11        | 0.46%   |
| 2880x1800          | 11        | 0.46%   |
| 2560x1080          | 11        | 0.46%   |
| 800x1280           | 9         | 0.37%   |
| 1360x768           | 7         | 0.29%   |
| 1024x768 (XGA)     | 7         | 0.29%   |
| 3200x1800 (QHD+)   | 6         | 0.25%   |
| 3840x2400          | 4         | 0.17%   |
| Unknown            | 4         | 0.17%   |
| 2288x1287          | 3         | 0.12%   |
| 1920x540           | 3         | 0.12%   |
| 1600x1200          | 3         | 0.12%   |
| 1400x1050          | 3         | 0.12%   |
| 1280x768           | 3         | 0.12%   |
| 3840x1080          | 2         | 0.08%   |
| 3456x2160          | 2         | 0.08%   |
| 3200x2000          | 2         | 0.08%   |
| 3840x1600          | 1         | 0.04%   |
| 3200x1080          | 1         | 0.04%   |
| 3072x1920          | 1         | 0.04%   |
| 3000x2000          | 1         | 0.04%   |
| 2880x1920          | 1         | 0.04%   |
| 2736x1824          | 1         | 0.04%   |
| 2304x1440          | 1         | 0.04%   |
| 2240x1400          | 1         | 0.04%   |
| 1920x1440          | 1         | 0.04%   |
| 1920x1280          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1294      | 50.08%  |
| 13      | 298       | 11.53%  |
| 14      | 203       | 7.86%   |
| 17      | 143       | 5.53%   |
| 24      | 83        | 3.21%   |
| 27      | 72        | 2.79%   |
| 21      | 69        | 2.67%   |
| 23      | 67        | 2.59%   |
| 12      | 51        | 1.97%   |
| Unknown | 43        | 1.66%   |
| 11      | 42        | 1.63%   |
| 10      | 41        | 1.59%   |
| 16      | 24        | 0.93%   |
| 34      | 23        | 0.89%   |
| 31      | 21        | 0.81%   |
| 19      | 17        | 0.66%   |
| 18      | 14        | 0.54%   |
| 20      | 12        | 0.46%   |
| 84      | 11        | 0.43%   |
| 72      | 7         | 0.27%   |
| 54      | 6         | 0.23%   |
| 22      | 6         | 0.23%   |
| 40      | 5         | 0.19%   |
| 25      | 5         | 0.19%   |
| 52      | 3         | 0.12%   |
| 46      | 3         | 0.12%   |
| 26      | 3         | 0.12%   |
| 8       | 3         | 0.12%   |
| 142     | 2         | 0.08%   |
| 32      | 2         | 0.08%   |
| 65      | 1         | 0.04%   |
| 57      | 1         | 0.04%   |
| 47      | 1         | 0.04%   |
| 42      | 1         | 0.04%   |
| 37      | 1         | 0.04%   |
| 36      | 1         | 0.04%   |
| 35      | 1         | 0.04%   |
| 33      | 1         | 0.04%   |
| 28      | 1         | 0.04%   |
| 7       | 1         | 0.04%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1616      | 63.03%  |
| 201-300        | 311       | 12.13%  |
| 501-600        | 215       | 8.39%   |
| 351-400        | 172       | 6.71%   |
| 401-500        | 108       | 4.21%   |
| Unknown        | 43        | 1.68%   |
| 601-700        | 26        | 1.01%   |
| 701-800        | 25        | 0.98%   |
| 1501-2000      | 18        | 0.7%    |
| 1001-1500      | 15        | 0.59%   |
| 801-900        | 7         | 0.27%   |
| 101-200        | 3         | 0.12%   |
| More than 2000 | 2         | 0.08%   |
| 1-100          | 2         | 0.08%   |
| 901-1000       | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1870      | 81.98%  |
| 16/10   | 280       | 12.28%  |
| 3/2     | 27        | 1.18%   |
| Unknown | 27        | 1.18%   |
| 5/4     | 24        | 1.05%   |
| 21/9    | 23        | 1.01%   |
| 4/3     | 14        | 0.61%   |
| 0.62    | 10        | 0.44%   |
| 1.00    | 2         | 0.09%   |
| 32/9    | 1         | 0.04%   |
| 1.03    | 1         | 0.04%   |
| 0.67    | 1         | 0.04%   |
| 0.56    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1299      | 50.31%  |
| 81-90          | 353       | 13.67%  |
| 201-250        | 189       | 7.32%   |
| 71-80          | 145       | 5.62%   |
| 121-130        | 100       | 3.87%   |
| 301-350        | 72        | 2.79%   |
| 61-70          | 48        | 1.86%   |
| 351-500        | 45        | 1.74%   |
| 151-200        | 45        | 1.74%   |
| Unknown        | 43        | 1.67%   |
| 51-60          | 42        | 1.63%   |
| 41-50          | 41        | 1.59%   |
| More than 1000 | 31        | 1.2%    |
| 131-140        | 31        | 1.2%    |
| 251-300        | 27        | 1.05%   |
| 141-150        | 26        | 1.01%   |
| 91-100         | 14        | 0.54%   |
| 111-120        | 13        | 0.5%    |
| 501-1000       | 13        | 0.5%    |
| 1-40           | 5         | 0.19%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 905       | 35.81%  |
| 101-120       | 849       | 33.6%   |
| 51-100        | 499       | 19.75%  |
| 161-240       | 149       | 5.9%    |
| More than 240 | 47        | 1.86%   |
| Unknown       | 43        | 1.7%    |
| 1-50          | 35        | 1.39%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1872      | 79.25%  |
| 2     | 363       | 15.37%  |
| 0     | 80        | 3.39%   |
| 3     | 44        | 1.86%   |
| 4     | 3         | 0.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1280      | 34.2%   |
| Intel                                  | 1091      | 29.15%  |
| Qualcomm Atheros                       | 616       | 16.46%  |
| Broadcom                               | 286       | 7.64%   |
| Broadcom Limited                       | 65        | 1.74%   |
| Marvell Technology Group               | 58        | 1.55%   |
| Ralink                                 | 41        | 1.1%    |
| TP-Link                                | 37        | 0.99%   |
| Ralink Technology                      | 34        | 0.91%   |
| MediaTek                               | 27        | 0.72%   |
| Nvidia                                 | 18        | 0.48%   |
| Samsung Electronics                    | 16        | 0.43%   |
| Xiaomi                                 | 15        | 0.4%    |
| Silicon Integrated Systems [SiS]       | 13        | 0.35%   |
| ASIX Electronics                       | 13        | 0.35%   |
| Dell                                   | 11        | 0.29%   |
| Sierra Wireless                        | 9         | 0.24%   |
| Lenovo                                 | 9         | 0.24%   |
| JMicron Technology                     | 9         | 0.24%   |
| Hewlett-Packard                        | 9         | 0.24%   |
| Ericsson Business Mobile Networks      | 9         | 0.24%   |
| Qualcomm Atheros Communications        | 8         | 0.21%   |
| Qualcomm                               | 8         | 0.21%   |
| DisplayLink                            | 8         | 0.21%   |
| D-Link                                 | 5         | 0.13%   |
| VIA Technologies                       | 4         | 0.11%   |
| LSI                                    | 4         | 0.11%   |
| Huawei Technologies                    | 4         | 0.11%   |
| Attansic Technology                    | 4         | 0.11%   |
| ASUSTek Computer                       | 4         | 0.11%   |
| Toshiba                                | 3         | 0.08%   |
| Edimax Technology                      | 3         | 0.08%   |
| Google                                 | 2         | 0.05%   |
| Arduino SA                             | 2         | 0.05%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.03%   |
| Sitecom Europe                         | 1         | 0.03%   |
| OPPO Electronics                       | 1         | 0.03%   |
| OnePlus Technology (Shenzhen)          | 1         | 0.03%   |
| OnePlus                                | 1         | 0.03%   |
| National Semiconductor                 | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 742       | 16.86%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 241       | 5.48%   |
| Intel Wi-Fi 6 AX200                                                     | 100       | 2.27%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 99        | 2.25%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 2.09%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 88        | 2%      |
| Intel Wireless 8265 / 8275                                              | 88        | 2%      |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 87        | 1.98%   |
| Intel Wi-Fi 6 AX201                                                     | 83        | 1.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 82        | 1.86%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 80        | 1.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 71        | 1.61%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 69        | 1.57%   |
| Intel Wireless 7265                                                     | 65        | 1.48%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 55        | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 1.23%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 1.23%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 52        | 1.18%   |
| Intel Wireless 7260                                                     | 51        | 1.16%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 49        | 1.11%   |
| Intel Wireless 3165                                                     | 47        | 1.07%   |
| Broadcom BCM43142 802.11b/g/n                                           | 42        | 0.95%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 0.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 0.93%   |
| Intel WiFi Link 5100                                                    | 37        | 0.84%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 0.82%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 0.7%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 31        | 0.7%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 0.68%   |
| Intel Wireless 8260                                                     | 30        | 0.68%   |
| Intel Wireless 3160                                                     | 30        | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 0.68%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                         | 30        | 0.68%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 26        | 0.59%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 26        | 0.59%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 25        | 0.57%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 24        | 0.55%   |
| Intel Centrino Advanced-N 6200                                          | 24        | 0.55%   |
| Intel 82577LM Gigabit Network Connection                                | 24        | 0.55%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.52%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1050      | 43.86%  |
| Qualcomm Atheros                | 517       | 21.6%   |
| Realtek Semiconductor           | 416       | 17.38%  |
| Broadcom                        | 190       | 7.94%   |
| Broadcom Limited                | 46        | 1.92%   |
| Ralink                          | 41        | 1.71%   |
| Ralink Technology               | 34        | 1.42%   |
| MediaTek                        | 27        | 1.13%   |
| TP-Link                         | 24        | 1%      |
| Sierra Wireless                 | 9         | 0.38%   |
| Qualcomm Atheros Communications | 8         | 0.33%   |
| Dell                            | 6         | 0.25%   |
| D-Link                          | 5         | 0.21%   |
| Qualcomm                        | 4         | 0.17%   |
| ASUSTek Computer                | 4         | 0.17%   |
| Edimax Technology               | 3         | 0.13%   |
| Hewlett-Packard                 | 2         | 0.08%   |
| Sitecom Europe                  | 1         | 0.04%   |
| Linksys                         | 1         | 0.04%   |
| Gemtek                          | 1         | 0.04%   |
| FIBOCOM                         | 1         | 0.04%   |
| D-Link System                   | 1         | 0.04%   |
| Belkin Components               | 1         | 0.04%   |
| AirTies Wireless Networks       | 1         | 0.04%   |
| Accton Technology               | 1         | 0.04%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 100       | 4.15%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 92        | 3.82%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 88        | 3.66%   |
| Intel Wireless 8265 / 8275                                              | 88        | 3.66%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 87        | 3.61%   |
| Intel Wi-Fi 6 AX201                                                     | 83        | 3.45%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 82        | 3.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 80        | 3.32%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 71        | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 69        | 2.87%   |
| Intel Wireless 7265                                                     | 65        | 2.7%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 55        | 2.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 54        | 2.24%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 54        | 2.24%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 52        | 2.16%   |
| Intel Wireless 7260                                                     | 51        | 2.12%   |
| Intel Wireless 3165                                                     | 47        | 1.95%   |
| Broadcom BCM43142 802.11b/g/n                                           | 42        | 1.74%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 42        | 1.74%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 41        | 1.7%    |
| Intel WiFi Link 5100                                                    | 37        | 1.54%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 36        | 1.5%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 31        | 1.29%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 31        | 1.29%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 30        | 1.25%   |
| Intel Wireless 8260                                                     | 30        | 1.25%   |
| Intel Wireless 3160                                                     | 30        | 1.25%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 30        | 1.25%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 26        | 1.08%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 24        | 1%      |
| Intel Centrino Advanced-N 6200                                          | 24        | 1%      |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 23        | 0.96%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 22        | 0.91%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 21        | 0.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 21        | 0.87%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 19        | 0.79%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 19        | 0.79%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 17        | 0.71%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 16        | 0.66%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 16        | 0.66%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1104      | 57.41%  |
| Intel                                  | 298       | 15.5%   |
| Qualcomm Atheros                       | 167       | 8.68%   |
| Broadcom                               | 131       | 6.81%   |
| Marvell Technology Group               | 58        | 3.02%   |
| Broadcom Limited                       | 21        | 1.09%   |
| Nvidia                                 | 18        | 0.94%   |
| Samsung Electronics                    | 16        | 0.83%   |
| Xiaomi                                 | 15        | 0.78%   |
| TP-Link                                | 13        | 0.68%   |
| Silicon Integrated Systems [SiS]       | 13        | 0.68%   |
| ASIX Electronics                       | 13        | 0.68%   |
| Lenovo                                 | 9         | 0.47%   |
| JMicron Technology                     | 9         | 0.47%   |
| DisplayLink                            | 8         | 0.42%   |
| VIA Technologies                       | 4         | 0.21%   |
| Qualcomm                               | 4         | 0.21%   |
| LSI                                    | 4         | 0.21%   |
| Attansic Technology                    | 4         | 0.21%   |
| Hewlett-Packard                        | 3         | 0.16%   |
| Google                                 | 2         | 0.1%    |
| Sony Ericsson Mobile Communications AB | 1         | 0.05%   |
| OPPO Electronics                       | 1         | 0.05%   |
| OnePlus                                | 1         | 0.05%   |
| National Semiconductor                 | 1         | 0.05%   |
| Microchip Technology                   | 1         | 0.05%   |
| Huawei Technologies                    | 1         | 0.05%   |
| Davicom Semiconductor                  | 1         | 0.05%   |
| Apple                                  | 1         | 0.05%   |
| ADMtek                                 | 1         | 0.05%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 742       | 38.01%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 241       | 12.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 99        | 5.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 49        | 2.51%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 30        | 1.54%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 26        | 1.33%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25        | 1.28%   |
| Intel 82577LM Gigabit Network Connection                          | 24        | 1.23%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 20        | 1.02%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 19        | 0.97%   |
| Intel Ethernet Connection I218-LM                                 | 17        | 0.87%   |
| Intel Ethernet Connection (4) I219-LM                             | 17        | 0.87%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 16        | 0.82%   |
| Intel Ethernet Connection (3) I218-LM                             | 16        | 0.82%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 15        | 0.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 14        | 0.72%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 14        | 0.72%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 14        | 0.72%   |
| Intel Ethernet Connection (4) I219-V                              | 14        | 0.72%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                   | 14        | 0.72%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 13        | 0.67%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 13        | 0.67%   |
| Nvidia MCP79 Ethernet                                             | 13        | 0.67%   |
| Intel Ethernet Connection (13) I219-V                             | 13        | 0.67%   |
| Intel 82567LM Gigabit Network Connection                          | 13        | 0.67%   |
| Intel 82579V Gigabit Network Connection                           | 12        | 0.61%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 12        | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 11        | 0.56%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 11        | 0.56%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller           | 11        | 0.56%   |
| ASIX AX88179 Gigabit Ethernet                                     | 11        | 0.56%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter     | 10        | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 10        | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 10        | 0.51%   |
| Intel Ethernet Connection I219-V                                  | 10        | 0.51%   |
| Intel Ethernet Connection I217-LM                                 | 10        | 0.51%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 10        | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 9         | 0.46%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller              | 9         | 0.46%   |
| Intel Ethernet Connection I219-LM                                 | 9         | 0.46%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 2262      | 54.19%  |
| Ethernet | 1871      | 44.83%  |
| Modem    | 40        | 0.96%   |
| Unknown  | 1         | 0.02%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1846      | 75.56%  |
| Ethernet | 597       | 24.44%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1697      | 73.4%   |
| 1     | 553       | 23.92%  |
| 0     | 50        | 2.16%   |
| 3     | 11        | 0.48%   |
| 4     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 2253      | 97.03%  |
| Yes  | 69        | 2.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 776       | 45.57%  |
| Realtek Semiconductor           | 211       | 12.39%  |
| Qualcomm Atheros Communications | 125       | 7.34%   |
| IMC Networks                    | 121       | 7.11%   |
| Broadcom                        | 79        | 4.64%   |
| Lite-On Technology              | 77        | 4.52%   |
| Foxconn / Hon Hai               | 70        | 4.11%   |
| Apple                           | 50        | 2.94%   |
| Cambridge Silicon Radio         | 34        | 2%      |
| Toshiba                         | 33        | 1.94%   |
| Realtek                         | 27        | 1.59%   |
| Dell                            | 24        | 1.41%   |
| Hewlett-Packard                 | 22        | 1.29%   |
| Ralink                          | 17        | 1%      |
| ASUSTek Computer                | 12        | 0.7%    |
| Alps Electric                   | 12        | 0.7%    |
| Foxconn International           | 6         | 0.35%   |
| Ralink Technology               | 3         | 0.18%   |
| Askey Computer                  | 2         | 0.12%   |
| Taiyo Yuden                     | 1         | 0.06%   |
| Chicony Electronics             | 1         | 0.06%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 303       | 17.79%  |
| Intel AX201 Bluetooth                               | 150       | 8.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 145       | 8.51%   |
| Realtek Bluetooth Radio                             | 140       | 8.22%   |
| Intel AX200 Bluetooth                               | 98        | 5.75%   |
| IMC Networks Bluetooth Radio                        | 57        | 3.35%   |
| Qualcomm Atheros  Bluetooth Device                  | 50        | 2.94%   |
| Realtek  Bluetooth 4.2 Adapter                      | 44        | 2.58%   |
| IMC Networks Bluetooth Device                       | 37        | 2.17%   |
| Foxconn / Hon Hai Bluetooth Device                  | 34        | 2%      |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 34        | 2%      |
| Apple Bluetooth Host Controller                     | 31        | 1.82%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 29        | 1.7%    |
| Realtek Bluetooth Radio                             | 27        | 1.59%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 27        | 1.59%   |
| Lite-On Bluetooth Device                            | 22        | 1.29%   |
| Lite-On Atheros AR3012 Bluetooth                    | 19        | 1.12%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.12%   |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 1.06%   |
| Ralink RT3290 Bluetooth                             | 17        | 1%      |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 17        | 1%      |
| Intel AX210 Bluetooth                               | 15        | 0.88%   |
| IMC Networks Wireless_Device                        | 15        | 0.88%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 14        | 0.82%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 14        | 0.82%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 14        | 0.82%   |
| Apple Bluetooth USB Host Controller                 | 12        | 0.7%    |
| HP Broadcom 2070 Bluetooth Combo                    | 11        | 0.65%   |
| Realtek RTL8723B Bluetooth                          | 10        | 0.59%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 10        | 0.59%   |
| Broadcom BCM2045B (BDC-2.1)                         | 10        | 0.59%   |
| Toshiba Integrated Bluetooth HCI                    | 9         | 0.53%   |
| Foxconn / Hon Hai Wireless_Device                   | 9         | 0.53%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 8         | 0.47%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 8         | 0.47%   |
| Foxconn / Hon Hai BCM20702A0                        | 8         | 0.47%   |
| Broadcom BCM2045 Bluetooth                          | 8         | 0.47%   |
| Realtek RTL8821A Bluetooth                          | 7         | 0.41%   |
| Dell DW375 Bluetooth Module                         | 7         | 0.41%   |
| Alps Electric BCM2046 Bluetooth Device              | 7         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1855      | 67.21%  |
| AMD                                  | 451       | 16.34%  |
| Nvidia                               | 298       | 10.8%   |
| C-Media Electronics                  | 22        | 0.8%    |
| Logitech                             | 15        | 0.54%   |
| Silicon Integrated Systems [SiS]     | 13        | 0.47%   |
| Lenovo                               | 9         | 0.33%   |
| GN Netcom                            | 8         | 0.29%   |
| Plantronics                          | 7         | 0.25%   |
| VIA Technologies                     | 5         | 0.18%   |
| Realtek Semiconductor                | 5         | 0.18%   |
| JMTek                                | 5         | 0.18%   |
| Kingston Technology                  | 4         | 0.14%   |
| Generalplus Technology               | 4         | 0.14%   |
| Corsair                              | 4         | 0.14%   |
| SteelSeries ApS                      | 3         | 0.11%   |
| Hewlett-Packard                      | 3         | 0.11%   |
| Creative Technology                  | 3         | 0.11%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.07%   |
| Texas Instruments                    | 2         | 0.07%   |
| Sennheiser Communications            | 2         | 0.07%   |
| No brand                             | 2         | 0.07%   |
| Guillemot                            | 2         | 0.07%   |
| CMX Systems                          | 2         | 0.07%   |
| Blue Microphones                     | 2         | 0.07%   |
| BEHRINGER International              | 2         | 0.07%   |
| Apple                                | 2         | 0.07%   |
| Alesis                               | 2         | 0.07%   |
| Vestax                               | 1         | 0.04%   |
| Veho                                 | 1         | 0.04%   |
| Trust                                | 1         | 0.04%   |
| ThrustMaster                         | 1         | 0.04%   |
| Tenx Technology                      | 1         | 0.04%   |
| Sony                                 | 1         | 0.04%   |
| Signalpath International             | 1         | 0.04%   |
| Razer USA                            | 1         | 0.04%   |
| PreSonus Audio Electronics           | 1         | 0.04%   |
| Nordic Semiconductor ASA             | 1         | 0.04%   |
| Native Instruments                   | 1         | 0.04%   |
| LG Electronics                       | 1         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 248       | 7.45%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 207       | 6.21%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 139       | 4.17%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 126       | 3.78%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 122       | 3.66%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 115       | 3.45%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 110       | 3.3%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 106       | 3.18%   |
| Intel Cannon Lake PCH cAVS                                                                        | 106       | 3.18%   |
| Intel 8 Series HD Audio Controller                                                                | 106       | 3.18%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 90        | 2.7%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 85        | 2.55%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 84        | 2.52%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 78        | 2.34%   |
| Intel Broadwell-U Audio Controller                                                                | 76        | 2.28%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 75        | 2.25%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 74        | 2.22%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 71        | 2.13%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 65        | 1.95%   |
| AMD FCH Azalia Controller                                                                         | 61        | 1.83%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 60        | 1.8%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 57        | 1.71%   |
| AMD Kabini HDMI/DP Audio                                                                          | 54        | 1.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 52        | 1.56%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 44        | 1.32%   |
| AMD High Definition Audio Controller                                                              | 43        | 1.29%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 41        | 1.23%   |
| Intel Comet Lake PCH cAVS                                                                         | 41        | 1.23%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 35        | 1.05%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 35        | 1.05%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 35        | 1.05%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 31        | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 30        | 0.9%    |
| Nvidia GP107GL High Definition Audio Controller                                                   | 29        | 0.87%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 27        | 0.81%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 27        | 0.81%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 25        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 23        | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 23        | 0.69%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 20        | 0.6%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 419       | 30.79%  |
| SK hynix                     | 288       | 21.16%  |
| Micron Technology            | 165       | 12.12%  |
| Kingston                     | 130       | 9.55%   |
| Unknown                      | 109       | 8.01%   |
| Crucial                      | 62        | 4.56%   |
| Ramaxel Technology           | 48        | 3.53%   |
| Unknown (ABCD)               | 22        | 1.62%   |
| Elpida                       | 21        | 1.54%   |
| A-DATA Technology            | 16        | 1.18%   |
| Nanya Technology             | 13        | 0.96%   |
| G.Skill                      | 10        | 0.73%   |
| Corsair                      | 10        | 0.73%   |
| Silicon Power                | 7         | 0.51%   |
| Transcend                    | 5         | 0.37%   |
| GOODRAM                      | 5         | 0.37%   |
| Unknown                      | 4         | 0.29%   |
| Wilk                         | 3         | 0.22%   |
| Apacer                       | 3         | 0.22%   |
| SHARETRONIC                  | 2         | 0.15%   |
| Patriot                      | 2         | 0.15%   |
| KomputerBay                  | 2         | 0.15%   |
| Avant                        | 2         | 0.15%   |
| Unifosa                      | 1         | 0.07%   |
| Toshiba                      | 1         | 0.07%   |
| Timetec                      | 1         | 0.07%   |
| Team                         | 1         | 0.07%   |
| Qimonda                      | 1         | 0.07%   |
| PNY                          | 1         | 0.07%   |
| Patriot Memory (PDP Systems) | 1         | 0.07%   |
| Netlist                      | 1         | 0.07%   |
| Kllisre                      | 1         | 0.07%   |
| Kembona                      | 1         | 0.07%   |
| CSX                          | 1         | 0.07%   |
| Atermiter                    | 1         | 0.07%   |
| ASint Technology             | 1         | 0.07%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s              | 26        | 1.82%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s              | 21        | 1.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 20        | 1.4%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s               | 19        | 1.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s    | 18        | 1.26%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s               | 17        | 1.19%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s               | 17        | 1.19%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s               | 16        | 1.12%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s               | 15        | 1.05%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s               | 15        | 1.05%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 14        | 0.98%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 14        | 0.98%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s               | 13        | 0.91%   |
| SK hynix RAM H9CCNNNCLGALAR-NVD 8192MB Row Of Chips LPDDR3 2133MT/s | 12        | 0.84%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 11        | 0.77%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s           | 11        | 0.77%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 11        | 0.77%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s               | 11        | 0.77%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 11        | 0.77%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 10        | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                | 10        | 0.7%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 10        | 0.7%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s              | 9         | 0.63%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 9         | 0.63%   |
| Samsung RAM M471A2G43AB2-CWE 16GB SODIMM DDR4 3200MT/s              | 9         | 0.63%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s         | 9         | 0.63%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s                       | 8         | 0.56%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s              | 8         | 0.56%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s               | 8         | 0.56%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s               | 8         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                | 8         | 0.56%   |
| Micron RAM 8ATF1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s                | 8         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s               | 8         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.49%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 7         | 0.49%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 7         | 0.49%   |
| SK hynix RAM HMAA2GS6AJR8N-XN 16384MB SODIMM DDR4 3200MT/s          | 7         | 0.49%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s              | 7         | 0.49%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.49%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s              | 7         | 0.49%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 552       | 48.13%  |
| DDR3    | 378       | 32.96%  |
| DDR2    | 71        | 6.19%   |
| LPDDR4  | 53        | 4.62%   |
| LPDDR3  | 43        | 3.75%   |
| SDRAM   | 26        | 2.27%   |
| DDR     | 7         | 0.61%   |
| Unknown | 7         | 0.61%   |
| DRAM    | 6         | 0.52%   |
| DDR5    | 3         | 0.26%   |
| LPDDR5  | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1038      | 89.41%  |
| Row Of Chips | 107       | 9.22%   |
| DIMM         | 8         | 0.69%   |
| Chip         | 8         | 0.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 472       | 37.58%  |
| 4096  | 379       | 30.18%  |
| 16384 | 175       | 13.93%  |
| 2048  | 150       | 11.94%  |
| 1024  | 50        | 3.98%   |
| 32768 | 23        | 1.83%   |
| 512   | 4         | 0.32%   |
| 256   | 2         | 0.16%   |
| 3072  | 1         | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 2667    | 260       | 20.98%  |
| 1600    | 253       | 20.42%  |
| 3200    | 218       | 17.59%  |
| 2400    | 91        | 7.34%   |
| 1334    | 61        | 4.92%   |
| 2133    | 60        | 4.84%   |
| 667     | 51        | 4.12%   |
| 1333    | 46        | 3.71%   |
| Unknown | 36        | 2.91%   |
| 8400    | 26        | 2.1%    |
| 1067    | 22        | 1.78%   |
| 4267    | 21        | 1.69%   |
| 3266    | 13        | 1.05%   |
| 1867    | 12        | 0.97%   |
| 800     | 12        | 0.97%   |
| 4199    | 10        | 0.81%   |
| 533     | 10        | 0.81%   |
| 2048    | 8         | 0.65%   |
| 1066    | 5         | 0.4%    |
| 975     | 5         | 0.4%    |
| 4800    | 3         | 0.24%   |
| 4266    | 3         | 0.24%   |
| 6400    | 2         | 0.16%   |
| 2933    | 2         | 0.16%   |
| 3733    | 1         | 0.08%   |
| 3000    | 1         | 0.08%   |
| 1777    | 1         | 0.08%   |
| 1776    | 1         | 0.08%   |
| 1639    | 1         | 0.08%   |
| 1200    | 1         | 0.08%   |
| 666     | 1         | 0.08%   |
| 333     | 1         | 0.08%   |
| 266     | 1         | 0.08%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Hewlett-Packard    | 9         | 47.37%  |
| Canon              | 4         | 21.05%  |
| Seiko Epson        | 3         | 15.79%  |
| Brother Industries | 3         | 15.79%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Canon PIXMA MG2500 Series        | 3         | 15.79%  |
| Seiko Epson XP-230 Series        | 1         | 5.26%   |
| Seiko Epson Printer              | 1         | 5.26%   |
| Seiko Epson L555 Series          | 1         | 5.26%   |
| HP PSC 1500 series               | 1         | 5.26%   |
| HP Printing Support              | 1         | 5.26%   |
| HP LaserJet Professional P 1102w | 1         | 5.26%   |
| HP LaserJet Pro M404-M405        | 1         | 5.26%   |
| HP LaserJet 1320                 | 1         | 5.26%   |
| HP LaserJet 1020                 | 1         | 5.26%   |
| HP LaserJet 1018                 | 1         | 5.26%   |
| HP LaserJet 1000                 | 1         | 5.26%   |
| HP DeskJet F300 series           | 1         | 5.26%   |
| Canon TS3100 series              | 1         | 5.26%   |
| Brother MFC-J5330DW              | 1         | 5.26%   |
| Brother HL-2030 Laser Printer    | 1         | 5.26%   |
| Brother HL-1210W series          | 1         | 5.26%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Notebooks | Percent |
|-----------------|-----------|---------|
| Canon           | 2         | 66.67%  |
| Hewlett-Packard | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                         | Notebooks | Percent |
|-------------------------------|-----------|---------|
| HP ScanJet 4300c              | 1         | 33.33%  |
| Canon CanoScan N1240U/LiDE 30 | 1         | 33.33%  |
| Canon CanoScan LiDE 210       | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 528       | 26.49%  |
| IMC Networks                           | 249       | 12.49%  |
| Acer                                   | 218       | 10.94%  |
| Realtek Semiconductor                  | 132       | 6.62%   |
| Microdia                               | 129       | 6.47%   |
| Suyin                                  | 109       | 5.47%   |
| Quanta                                 | 98        | 4.92%   |
| Sunplus Innovation Technology          | 83        | 4.16%   |
| Cheng Uei Precision Industry (Foxlink) | 80        | 4.01%   |
| Syntek                                 | 57        | 2.86%   |
| Alcor Micro                            | 37        | 1.86%   |
| Lite-On Technology                     | 33        | 1.66%   |
| Apple                                  | 31        | 1.56%   |
| Ricoh                                  | 28        | 1.4%    |
| Luxvisions Innotech Limited            | 22        | 1.1%    |
| Silicon Motion                         | 18        | 0.9%    |
| Logitech                               | 16        | 0.8%    |
| Samsung Electronics                    | 11        | 0.55%   |
| Importek                               | 9         | 0.45%   |
| Lenovo                                 | 8         | 0.4%    |
| ALi                                    | 8         | 0.4%    |
| icSpring                               | 7         | 0.35%   |
| GEMBIRD                                | 7         | 0.35%   |
| Z-Star Microelectronics                | 6         | 0.3%    |
| Sonix Technology                       | 6         | 0.3%    |
| Sunplus Technology                     | 5         | 0.25%   |
| Primax Electronics                     | 5         | 0.25%   |
| KYE Systems (Mouse Systems)            | 5         | 0.25%   |
| Intel                                  | 5         | 0.25%   |
| OmniVision Technologies                | 4         | 0.2%    |
| Genesys Logic                          | 4         | 0.2%    |
| DigiTech                               | 4         | 0.2%    |
| ARC International                      | 4         | 0.2%    |
| Trust                                  | 2         | 0.1%    |
| Novatek Microelectronics               | 2         | 0.1%    |
| Microsoft                              | 2         | 0.1%    |
| Creative Technology                    | 2         | 0.1%    |
| 2M UVC CAMERA                          | 2         | 0.1%    |
| Xiaomi                                 | 1         | 0.05%   |
| WaveRider Communications               | 1         | 0.05%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                       | 67        | 3.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 61        | 3.05%   |
| Chicony HD Webcam                                       | 59        | 2.95%   |
| Microdia Integrated_Webcam_HD                           | 50        | 2.5%    |
| Chicony Integrated Camera                               | 49        | 2.45%   |
| Acer Integrated Camera                                  | 48        | 2.4%    |
| Acer HD Webcam                                          | 45        | 2.25%   |
| IMC Networks Integrated Camera                          | 38        | 1.9%    |
| Chicony USB2.0 VGA UVC WebCam                           | 37        | 1.85%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 30        | 1.5%    |
| Quanta HP TrueVision HD Camera                          | 29        | 1.45%   |
| Realtek Integrated_Webcam_HD                            | 28        | 1.4%    |
| Chicony TOSHIBA Web Camera - HD                         | 26        | 1.3%    |
| Sunplus HD WebCam                                       | 22        | 1.1%    |
| Chicony USB 2.0 Camera                                  | 22        | 1.1%    |
| Realtek USB Camera                                      | 21        | 1.05%   |
| Chicony EasyCamera                                      | 21        | 1.05%   |
| Acer HD Camera                                          | 19        | 0.95%   |
| Syntek Integrated Camera                                | 18        | 0.9%    |
| Chicony USB2.0 HD UVC WebCam                            | 18        | 0.9%    |
| Acer EasyCamera                                         | 18        | 0.9%    |
| Lite-On Integrated Camera                               | 16        | 0.8%    |
| Chicony HP Truevision HD                                | 16        | 0.8%    |
| Acer Lenovo EasyCamera                                  | 16        | 0.8%    |
| Syntek EasyCamera                                       | 15        | 0.75%   |
| Realtek Lenovo EasyCamera                               | 15        | 0.75%   |
| Chicony Integrated Camera (1280x720@30)                 | 15        | 0.75%   |
| Apple Built-in iSight                                   | 15        | 0.75%   |
| Syntek Lenovo EasyCamera                                | 14        | 0.7%    |
| Chicony VGA Webcam                                      | 14        | 0.7%    |
| Chicony USB2.0 Camera                                   | 14        | 0.7%    |
| Suyin HP TrueVision HD                                  | 13        | 0.65%   |
| Quanta HP Webcam                                        | 13        | 0.65%   |
| Quanta HP HD Camera                                     | 13        | 0.65%   |
| Microdia USB 2.0 Camera                                 | 13        | 0.65%   |
| Microdia Integrated Webcam                              | 13        | 0.65%   |
| Chicony HP HD Camera                                    | 13        | 0.65%   |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 13        | 0.65%   |
| Acer BisonCam, NB Pro                                   | 13        | 0.65%   |
| Sunplus Integrated_Webcam_HD                            | 12        | 0.6%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 86        | 27.22%  |
| Validity Sensors           | 77        | 24.37%  |
| Shenzhen Goodix Technology | 51        | 16.14%  |
| Elan Microelectronics      | 34        | 10.76%  |
| AuthenTec                  | 33        | 10.44%  |
| Upek                       | 21        | 6.65%   |
| LighTuning Technology      | 8         | 2.53%   |
| STMicroelectronics         | 6         | 1.9%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Unknown                                                                    | 39        | 12.34%  |
| Shenzhen Goodix  FingerPrint Device                                        | 36        | 11.39%  |
| Elan ELAN:Fingerprint                                                      | 32        | 10.13%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 24        | 7.59%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 17        | 5.38%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 16        | 5.06%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 14        | 4.43%   |
| Shenzhen Goodix Fingerprint Reader                                         | 12        | 3.8%    |
| Validity Sensors VFS 5011 fingerprint sensor                               | 11        | 3.48%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 11        | 3.48%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 8         | 2.53%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 6         | 1.9%    |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 6         | 1.9%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 6         | 1.9%    |
| STMicroelectronics Fingerprint Reader                                      | 6         | 1.9%    |
| AuthenTec AES1600                                                          | 6         | 1.9%    |
| Validity Sensors VFS471 Fingerprint Reader                                 | 5         | 1.58%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 5         | 1.58%   |
| AuthenTec Fingerprint Sensor                                               | 5         | 1.58%   |
| AuthenTec AES2810                                                          | 5         | 1.58%   |
| Validity Sensors VFS491                                                    | 4         | 1.27%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 4         | 1.27%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 1.27%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 1.27%   |
| LighTuning EgisTec_ES603                                                   | 4         | 1.27%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 4         | 1.27%   |
| Synaptics  WBDI                                                            | 3         | 0.95%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 0.95%   |
| Validity Sensors VFS Fingerprint sensor                                    | 2         | 0.63%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 0.63%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 2         | 0.63%   |
| LighTuning Fingerprint Reader                                              | 2         | 0.63%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 0.63%   |
| Elan ELAN:ARM-M4                                                           | 2         | 0.63%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 2         | 0.63%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.32%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.32%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 49        | 34.51%  |
| Broadcom              | 45        | 31.69%  |
| O2 Micro              | 23        | 16.2%   |
| Lenovo                | 7         | 4.93%   |
| Upek                  | 4         | 2.82%   |
| C3PO                  | 4         | 2.82%   |
| Cherry                | 3         | 2.11%   |
| Realtek Semiconductor | 2         | 1.41%   |
| Gemalto (was Gemplus) | 2         | 1.41%   |
| In Focus Systems      | 1         | 0.7%    |
| Chicony Electronics   | 1         | 0.7%    |
| Advanced Card Systems | 1         | 0.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 49        | 34.51%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 22        | 15.49%  |
| Broadcom BCM5880 Secure Applications Processor                               | 16        | 11.27%  |
| Broadcom 5880                                                                | 12        | 8.45%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 9         | 6.34%   |
| Broadcom 58200                                                               | 8         | 5.63%   |
| Lenovo Integrated Smart Card Reader                                          | 7         | 4.93%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.82%   |
| Cherry SmartTerminal XX1X                                                    | 3         | 2.11%   |
| C3PO LTC31v2                                                                 | 3         | 2.11%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.41%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 1.41%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.7%    |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.7%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 1         | 0.7%    |
| C3PO USB SMART CARD READER                                                   | 1         | 0.7%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1545      | 65.13%  |
| 1     | 647       | 27.28%  |
| 2     | 149       | 6.28%   |
| 3     | 21        | 0.89%   |
| 4     | 7         | 0.3%    |
| 5     | 2         | 0.08%   |
| 8     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 310       | 30.69%  |
| Graphics card            | 230       | 22.77%  |
| Net/wireless             | 135       | 13.37%  |
| Chipcard                 | 124       | 12.28%  |
| Multimedia controller    | 62        | 6.14%   |
| Camera                   | 27        | 2.67%   |
| Bluetooth                | 25        | 2.48%   |
| Storage                  | 20        | 1.98%   |
| Communication controller | 20        | 1.98%   |
| Card reader              | 14        | 1.39%   |
| Sound                    | 10        | 0.99%   |
| Net/ethernet             | 10        | 0.99%   |
| Flash memory             | 10        | 0.99%   |
| Modem                    | 8         | 0.79%   |
| Dvb card                 | 3         | 0.3%    |
| Network                  | 2         | 0.2%    |


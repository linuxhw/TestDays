BlackPanther - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------------

A project to collect tested hardware configurations for BlackPanther.

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

Total: 4888

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | ThinkPad L470 20J5S2RA00    | [9ce0d2cad0](https://linux-hardware.org/?probe=9ce0d2cad0) | May 09, 2024 |
| Lenovo        | ThinkPad X230 2333A91       | [3ad48e3ebe](https://linux-hardware.org/?probe=3ad48e3ebe) | May 08, 2024 |
| ASUSTek       | K54HR                       | [67ddde3a75](https://linux-hardware.org/?probe=67ddde3a75) | May 08, 2024 |
| Dell          | Latitude E5520              | [1dc92b60a8](https://linux-hardware.org/?probe=1dc92b60a8) | May 08, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [20ab787216](https://linux-hardware.org/?probe=20ab787216) | May 08, 2024 |
| MSI           | GT60 2OC/2OD                | [aa9d5951b9](https://linux-hardware.org/?probe=aa9d5951b9) | May 08, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [b1a0c45242](https://linux-hardware.org/?probe=b1a0c45242) | May 07, 2024 |
| Dell          | Latitude 5501               | [35d264df4c](https://linux-hardware.org/?probe=35d264df4c) | May 07, 2024 |
| HP            | Laptop 15-dw1xxx            | [7d4c93ea72](https://linux-hardware.org/?probe=7d4c93ea72) | May 07, 2024 |
| AWOW          | AK41                        | [21d739c59c](https://linux-hardware.org/?probe=21d739c59c) | May 07, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [e27e19897e](https://linux-hardware.org/?probe=e27e19897e) | May 07, 2024 |
| Lenovo        | V15-ADA 82C7                | [db9ea4ffaf](https://linux-hardware.org/?probe=db9ea4ffaf) | May 07, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [b8e70b0693](https://linux-hardware.org/?probe=b8e70b0693) | May 07, 2024 |
| Fujitsu       | LIFEBOOK AH530              | [55fdc987e5](https://linux-hardware.org/?probe=55fdc987e5) | May 07, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [3236268f3d](https://linux-hardware.org/?probe=3236268f3d) | May 06, 2024 |
| Dell          | Inspiron 7737               | [73f61be8b5](https://linux-hardware.org/?probe=73f61be8b5) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | [d71303b21c](https://linux-hardware.org/?probe=d71303b21c) | May 06, 2024 |
| MSI           | GT60 2OC/2OD                | [3330ada128](https://linux-hardware.org/?probe=3330ada128) | May 06, 2024 |
| Acer          | Aspire 5750                 | [c414f0202a](https://linux-hardware.org/?probe=c414f0202a) | May 06, 2024 |
| HP            | 650                         | [6e66ce7389](https://linux-hardware.org/?probe=6e66ce7389) | May 05, 2024 |
| HP            | 650                         | [aa4f605e5e](https://linux-hardware.org/?probe=aa4f605e5e) | May 05, 2024 |
| HP            | EliteBook 8570w             | [d18669833b](https://linux-hardware.org/?probe=d18669833b) | May 04, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | [1342233681](https://linux-hardware.org/?probe=1342233681) | May 03, 2024 |
| Dell          | Inspiron 5558               | [f3e4760d0f](https://linux-hardware.org/?probe=f3e4760d0f) | May 03, 2024 |
| Dell          | Inspiron 5558               | [ded6bb6fdc](https://linux-hardware.org/?probe=ded6bb6fdc) | May 02, 2024 |
| Dell          | Inspiron 5558               | [6f084542fa](https://linux-hardware.org/?probe=6f084542fa) | May 02, 2024 |
| eMachines     | E725                        | [f8c6e397e1](https://linux-hardware.org/?probe=f8c6e397e1) | May 01, 2024 |
| HP            | 255 G5 Notebook PC          | [945efc5a98](https://linux-hardware.org/?probe=945efc5a98) | May 01, 2024 |
| Packard Be... | EasyNote TE11BZ             | [fe163fcb48](https://linux-hardware.org/?probe=fe163fcb48) | May 01, 2024 |
| Packard Be... | EasyNote TE11BZ             | [db92c4f28a](https://linux-hardware.org/?probe=db92c4f28a) | May 01, 2024 |
| eMachines     | E725                        | [f48c8f52da](https://linux-hardware.org/?probe=f48c8f52da) | Apr 30, 2024 |
| Lenovo        | ThinkPad T420 423662G       | [e67bde685e](https://linux-hardware.org/?probe=e67bde685e) | Apr 29, 2024 |
| Lenovo        | ThinkPad T420 423662G       | [c21e1e6ad3](https://linux-hardware.org/?probe=c21e1e6ad3) | Apr 29, 2024 |
| HP            | Laptop 15-dw1xxx            | [7332d6602f](https://linux-hardware.org/?probe=7332d6602f) | Apr 28, 2024 |
| HP            | Notebook                    | [43a6b1537a](https://linux-hardware.org/?probe=43a6b1537a) | Apr 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [3f7c1cff47](https://linux-hardware.org/?probe=3f7c1cff47) | Apr 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [4ea4b9b731](https://linux-hardware.org/?probe=4ea4b9b731) | Apr 28, 2024 |
| Dell          | Inspiron 3542               | [947b81aba4](https://linux-hardware.org/?probe=947b81aba4) | Apr 27, 2024 |
| HP            | ProBook 455 G1              | [b67b7fc16d](https://linux-hardware.org/?probe=b67b7fc16d) | Apr 26, 2024 |
| HP            | ProBook 455 G1              | [59808a41b2](https://linux-hardware.org/?probe=59808a41b2) | Apr 26, 2024 |
| HP            | 255 G5 Notebook PC          | [b3b73c7c85](https://linux-hardware.org/?probe=b3b73c7c85) | Apr 24, 2024 |
| ASUSTek       | K53BY                       | [b00f35b89c](https://linux-hardware.org/?probe=b00f35b89c) | Apr 23, 2024 |
| ASUSTek       | K54C                        | [9204edfa98](https://linux-hardware.org/?probe=9204edfa98) | Apr 21, 2024 |
| ASUSTek       | K54C                        | [0853f021e9](https://linux-hardware.org/?probe=0853f021e9) | Apr 21, 2024 |
| Packard Be... | EasyNote TK36               | [f44f785257](https://linux-hardware.org/?probe=f44f785257) | Apr 21, 2024 |
| ASUSTek       | K53TA                       | [128c0946a5](https://linux-hardware.org/?probe=128c0946a5) | Apr 21, 2024 |
| ASUSTek       | K53TA                       | [411dc2f51d](https://linux-hardware.org/?probe=411dc2f51d) | Apr 21, 2024 |
| HP            | Presario CQ57               | [366b704066](https://linux-hardware.org/?probe=366b704066) | Apr 21, 2024 |
| HP            | Laptop 15-dw1xxx            | [4a2376cdfa](https://linux-hardware.org/?probe=4a2376cdfa) | Apr 21, 2024 |
| HP            | Presario CQ57               | [956b5fe458](https://linux-hardware.org/?probe=956b5fe458) | Apr 20, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [473affb537](https://linux-hardware.org/?probe=473affb537) | Apr 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [6f826f9c64](https://linux-hardware.org/?probe=6f826f9c64) | Apr 18, 2024 |
| Dell          | Latitude D520               | [d0f7ecac0a](https://linux-hardware.org/?probe=d0f7ecac0a) | Apr 17, 2024 |
| Dell          | Latitude D520               | [faf18ae19f](https://linux-hardware.org/?probe=faf18ae19f) | Apr 17, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [59cf1e0ea1](https://linux-hardware.org/?probe=59cf1e0ea1) | Apr 17, 2024 |
| Acer          | Aspire E1-571               | [3a38e7fc4f](https://linux-hardware.org/?probe=3a38e7fc4f) | Apr 16, 2024 |
| Toshiba       | Satellite L650              | [b05f51b2c8](https://linux-hardware.org/?probe=b05f51b2c8) | Apr 15, 2024 |
| Toshiba       | Satellite L650              | [0a98edcca4](https://linux-hardware.org/?probe=0a98edcca4) | Apr 15, 2024 |
| Toshiba       | Satellite L650              | [e706aef914](https://linux-hardware.org/?probe=e706aef914) | Apr 15, 2024 |
| Toshiba       | Satellite L650              | [1ffbc9aa24](https://linux-hardware.org/?probe=1ffbc9aa24) | Apr 15, 2024 |
| ASUSTek       | X551CA                      | [5bf06a6ae1](https://linux-hardware.org/?probe=5bf06a6ae1) | Apr 14, 2024 |
| Lenovo        | ThinkPad T470 20HES58A1L    | [fd97b7444d](https://linux-hardware.org/?probe=fd97b7444d) | Apr 14, 2024 |
| Lenovo        | ThinkPad X200 74595FG       | [708440ed39](https://linux-hardware.org/?probe=708440ed39) | Apr 14, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [8dd990563f](https://linux-hardware.org/?probe=8dd990563f) | Apr 11, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [a4cda4b4f0](https://linux-hardware.org/?probe=a4cda4b4f0) | Apr 10, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [2359c23a41](https://linux-hardware.org/?probe=2359c23a41) | Apr 10, 2024 |
| Packard Be... | EasyNote TV43HC             | [07aac9c6e6](https://linux-hardware.org/?probe=07aac9c6e6) | Apr 10, 2024 |
| Packard Be... | EasyNote TV43HC             | [036bbb75eb](https://linux-hardware.org/?probe=036bbb75eb) | Apr 10, 2024 |
| HP            | ProBook 455 G1              | [d332e44b92](https://linux-hardware.org/?probe=d332e44b92) | Apr 10, 2024 |
| Lenovo        | ThinkPad T530 2429NL6       | [d16f3981f4](https://linux-hardware.org/?probe=d16f3981f4) | Apr 10, 2024 |
| Dell          | Inspiron 5558               | [a583587fa0](https://linux-hardware.org/?probe=a583587fa0) | Apr 09, 2024 |
| ASUSTek       | X541NA                      | [4118d01689](https://linux-hardware.org/?probe=4118d01689) | Apr 09, 2024 |
| HP            | ProBook 455 G1              | [9a0d60a4e6](https://linux-hardware.org/?probe=9a0d60a4e6) | Apr 09, 2024 |
| HP            | Notebook                    | [1ef4d18969](https://linux-hardware.org/?probe=1ef4d18969) | Apr 09, 2024 |
| Lenovo        | ThinkPad T530 2429NL6       | [ee82d8efd8](https://linux-hardware.org/?probe=ee82d8efd8) | Apr 08, 2024 |
| Packard Be... | EasyNote TK36               | [7b4011aa67](https://linux-hardware.org/?probe=7b4011aa67) | Apr 08, 2024 |
| HP            | ProBook 455 G1              | [cf0a1167a4](https://linux-hardware.org/?probe=cf0a1167a4) | Apr 08, 2024 |
| HP            | ProBook 455 G1              | [aca7655496](https://linux-hardware.org/?probe=aca7655496) | Apr 08, 2024 |
| ASUSTek       | K53BY                       | [fe40c5b1ae](https://linux-hardware.org/?probe=fe40c5b1ae) | Apr 07, 2024 |
| Dell          | Latitude E6330              | [c32426747e](https://linux-hardware.org/?probe=c32426747e) | Apr 07, 2024 |
| HP            | ProBook 650 G2              | [005b1cfa0d](https://linux-hardware.org/?probe=005b1cfa0d) | Apr 07, 2024 |
| HP            | ProBook 650 G2              | [fa83ab6042](https://linux-hardware.org/?probe=fa83ab6042) | Apr 07, 2024 |
| HP            | Presario CQ57               | [2506e7958a](https://linux-hardware.org/?probe=2506e7958a) | Apr 06, 2024 |
| Packard Be... | EasyNote TK36               | [a0d6051c56](https://linux-hardware.org/?probe=a0d6051c56) | Apr 06, 2024 |
| HP            | Presario CQ57               | [781ff00313](https://linux-hardware.org/?probe=781ff00313) | Apr 06, 2024 |
| ASUSTek       | K53BY                       | [c202d85a6a](https://linux-hardware.org/?probe=c202d85a6a) | Apr 06, 2024 |
| HP            | Pavilion dv7                | [a84ff5282d](https://linux-hardware.org/?probe=a84ff5282d) | Apr 05, 2024 |
| HP            | 250 G3                      | [94b04f5a94](https://linux-hardware.org/?probe=94b04f5a94) | Apr 04, 2024 |
| HP            | 630                         | [35dd7e2dc4](https://linux-hardware.org/?probe=35dd7e2dc4) | Apr 04, 2024 |
| Acer          | TravelMate 8571             | [057645b066](https://linux-hardware.org/?probe=057645b066) | Apr 04, 2024 |
| Dell          | Inspiron 3521               | [ee70d25db0](https://linux-hardware.org/?probe=ee70d25db0) | Apr 04, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [b165b6fe04](https://linux-hardware.org/?probe=b165b6fe04) | Apr 03, 2024 |
| Dell          | Latitude E6520              | [f27403f5b8](https://linux-hardware.org/?probe=f27403f5b8) | Apr 02, 2024 |
| Dell          | Vostro 1015                 | [807e851743](https://linux-hardware.org/?probe=807e851743) | Apr 02, 2024 |
| Dell          | Latitude 5480               | [3cfb6f8944](https://linux-hardware.org/?probe=3cfb6f8944) | Apr 01, 2024 |
| Dell          | Latitude E6220              | [56d82e4651](https://linux-hardware.org/?probe=56d82e4651) | Mar 30, 2024 |
| HP            | Presario CQ57               | [f731d051bc](https://linux-hardware.org/?probe=f731d051bc) | Mar 28, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [3c061242d5](https://linux-hardware.org/?probe=3c061242d5) | Mar 27, 2024 |
| Insyde        | Braswell                    | [36cefae839](https://linux-hardware.org/?probe=36cefae839) | Mar 26, 2024 |
| ASUSTek       | X55U                        | [39ac7513a1](https://linux-hardware.org/?probe=39ac7513a1) | Mar 25, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [4f6aeb519e](https://linux-hardware.org/?probe=4f6aeb519e) | Mar 25, 2024 |
| Apple         | MacBookAir5,2               | [26a63eb1aa](https://linux-hardware.org/?probe=26a63eb1aa) | Mar 25, 2024 |
| Medion        | E7218                       | [276473d8eb](https://linux-hardware.org/?probe=276473d8eb) | Mar 25, 2024 |
| Lenovo        | ThinkPad L470 20J5S2RA00    | [1f780ec544](https://linux-hardware.org/?probe=1f780ec544) | Mar 25, 2024 |
| Lenovo        | ThinkPad T430 234452G       | [fe81289ee2](https://linux-hardware.org/?probe=fe81289ee2) | Mar 24, 2024 |
| Lenovo        | ThinkPad T430 234452G       | [cc4e22e5bb](https://linux-hardware.org/?probe=cc4e22e5bb) | Mar 24, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [152813c2d7](https://linux-hardware.org/?probe=152813c2d7) | Mar 24, 2024 |
| Sony          | VPCEB4M1E                   | [770546fc7a](https://linux-hardware.org/?probe=770546fc7a) | Mar 24, 2024 |
| HP            | Pavilion dv6                | [9070fdfab3](https://linux-hardware.org/?probe=9070fdfab3) | Mar 23, 2024 |
| Fujitsu       | LIFEBOOK A555               | [5238348a6f](https://linux-hardware.org/?probe=5238348a6f) | Mar 23, 2024 |
| HP            | 250 G1                      | [55e152c109](https://linux-hardware.org/?probe=55e152c109) | Mar 23, 2024 |
| Dell          | Latitude 5480               | [11476d6105](https://linux-hardware.org/?probe=11476d6105) | Mar 23, 2024 |
| Sony          | SVS13118GBB                 | [b21f07100b](https://linux-hardware.org/?probe=b21f07100b) | Mar 23, 2024 |
| Acer          | Aspire E1-571               | [fa4ac16f77](https://linux-hardware.org/?probe=fa4ac16f77) | Mar 23, 2024 |
| HP            | 650                         | [fcdc2e81ff](https://linux-hardware.org/?probe=fcdc2e81ff) | Mar 23, 2024 |
| Lenovo        | ThinkPad T400 2768WGB       | [903d677c51](https://linux-hardware.org/?probe=903d677c51) | Mar 23, 2024 |
| HP            | 250 G1                      | [37f1c0eef8](https://linux-hardware.org/?probe=37f1c0eef8) | Mar 23, 2024 |
| Lenovo        | Flex 2-15D 20377            | [e285a594eb](https://linux-hardware.org/?probe=e285a594eb) | Mar 23, 2024 |
| Toshiba       | Satellite M50D-A            | [1551082716](https://linux-hardware.org/?probe=1551082716) | Mar 23, 2024 |
| Acer          | Aspire V5-121               | [3b266ed105](https://linux-hardware.org/?probe=3b266ed105) | Mar 22, 2024 |
| Dell          | Inspiron 17 7000 Series ... | [ba43b4e2f3](https://linux-hardware.org/?probe=ba43b4e2f3) | Mar 22, 2024 |
| HP            | ProBook 650 G2              | [f37b764c1f](https://linux-hardware.org/?probe=f37b764c1f) | Mar 22, 2024 |
| ASUSTek       | X200MA                      | [e6502ec467](https://linux-hardware.org/?probe=e6502ec467) | Mar 22, 2024 |
| Dell          | Latitude E7240              | [fba5ef74a3](https://linux-hardware.org/?probe=fba5ef74a3) | Mar 22, 2024 |
| eMachines     | E725                        | [ed7591a944](https://linux-hardware.org/?probe=ed7591a944) | Mar 22, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [20860dcb34](https://linux-hardware.org/?probe=20860dcb34) | Mar 22, 2024 |
| Dell          | Latitude 7390               | [ded1cffb21](https://linux-hardware.org/?probe=ded1cffb21) | Mar 22, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [4922ac4c1e](https://linux-hardware.org/?probe=4922ac4c1e) | Mar 21, 2024 |
| ASUSTek       | K52N                        | [7f4a855bc0](https://linux-hardware.org/?probe=7f4a855bc0) | Mar 21, 2024 |
| ASUSTek       | K52N                        | [31c9cc7e95](https://linux-hardware.org/?probe=31c9cc7e95) | Mar 21, 2024 |
| ASUSTek       | X55U                        | [99ed199098](https://linux-hardware.org/?probe=99ed199098) | Mar 21, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [2bcb8453c8](https://linux-hardware.org/?probe=2bcb8453c8) | Mar 21, 2024 |
| MSI           | GT60 2OC/2OD                | [11156842cb](https://linux-hardware.org/?probe=11156842cb) | Mar 21, 2024 |
| Lenovo        | ThinkPad T410 2537VFQ       | [6e650c99d9](https://linux-hardware.org/?probe=6e650c99d9) | Mar 21, 2024 |
| Acer          | Aspire 5750ZG               | [cd447c8d09](https://linux-hardware.org/?probe=cd447c8d09) | Mar 21, 2024 |
| Dell          | Latitude E5250              | [7afd8ad90c](https://linux-hardware.org/?probe=7afd8ad90c) | Mar 21, 2024 |
| Acer          | TravelMate P215-52          | [ea1412ec3b](https://linux-hardware.org/?probe=ea1412ec3b) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [deaf0f8deb](https://linux-hardware.org/?probe=deaf0f8deb) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [d6511f30e4](https://linux-hardware.org/?probe=d6511f30e4) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [81377c9f3c](https://linux-hardware.org/?probe=81377c9f3c) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [e56b916758](https://linux-hardware.org/?probe=e56b916758) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [ae202e3d04](https://linux-hardware.org/?probe=ae202e3d04) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [8a5c25a49d](https://linux-hardware.org/?probe=8a5c25a49d) | Mar 21, 2024 |
| HP            | ProBook 455 G1              | [9d4a29e34c](https://linux-hardware.org/?probe=9d4a29e34c) | Mar 21, 2024 |
| Toshiba       | Satellite M50D-A            | [28efb8633c](https://linux-hardware.org/?probe=28efb8633c) | Mar 20, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [89bd2eb279](https://linux-hardware.org/?probe=89bd2eb279) | Mar 20, 2024 |
| Lenovo        | V15-ADA 82C7                | [ad20e511df](https://linux-hardware.org/?probe=ad20e511df) | Mar 20, 2024 |
| Dell          | Inspiron 7737               | [d94c08d5bb](https://linux-hardware.org/?probe=d94c08d5bb) | Mar 20, 2024 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [dccc8e498c](https://linux-hardware.org/?probe=dccc8e498c) | Mar 20, 2024 |
| Lenovo        | ThinkPad X395 20NMS0YG00    | [54b4d8c3f7](https://linux-hardware.org/?probe=54b4d8c3f7) | Mar 20, 2024 |
| Insyde        | Braswell                    | [52052f3a4c](https://linux-hardware.org/?probe=52052f3a4c) | Mar 20, 2024 |
| Valve         | Jupiter                     | [ea06aa4de3](https://linux-hardware.org/?probe=ea06aa4de3) | Mar 19, 2024 |
| Valve         | Jupiter                     | [49641a93e9](https://linux-hardware.org/?probe=49641a93e9) | Mar 19, 2024 |
| Sony          | SVS13118GBB                 | [e9ffb83f97](https://linux-hardware.org/?probe=e9ffb83f97) | Mar 19, 2024 |
| HP            | ProBook 455 G1              | [d49e68b665](https://linux-hardware.org/?probe=d49e68b665) | Mar 19, 2024 |
| HP            | ProBook 455 G1              | [ca61401c93](https://linux-hardware.org/?probe=ca61401c93) | Mar 19, 2024 |
| HP            | ProBook 455 G1              | [9af57393f1](https://linux-hardware.org/?probe=9af57393f1) | Mar 19, 2024 |
| HP            | 250 G3                      | [df2aa0348f](https://linux-hardware.org/?probe=df2aa0348f) | Mar 18, 2024 |
| Dell          | Inspiron 1545               | [b71fbb3c42](https://linux-hardware.org/?probe=b71fbb3c42) | Mar 18, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [f18e6f9a20](https://linux-hardware.org/?probe=f18e6f9a20) | Mar 17, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [cbf9e80869](https://linux-hardware.org/?probe=cbf9e80869) | Mar 17, 2024 |
| HP            | 250 G1                      | [3562985bc8](https://linux-hardware.org/?probe=3562985bc8) | Mar 17, 2024 |
| Lenovo        | G550 20023                  | [cfc63cec90](https://linux-hardware.org/?probe=cfc63cec90) | Mar 17, 2024 |
| Dell          | Inspiron 1545               | [c941a3660f](https://linux-hardware.org/?probe=c941a3660f) | Mar 17, 2024 |
| HP            | 650                         | [2504aba44f](https://linux-hardware.org/?probe=2504aba44f) | Mar 15, 2024 |
| HP            | ProBook 455 G1              | [6e6de8b85d](https://linux-hardware.org/?probe=6e6de8b85d) | Mar 14, 2024 |
| HP            | ProBook 455 G1              | [8d9d1c239d](https://linux-hardware.org/?probe=8d9d1c239d) | Mar 14, 2024 |
| HP            | Notebook                    | [86866cc6d3](https://linux-hardware.org/?probe=86866cc6d3) | Mar 14, 2024 |
| HP            | Notebook                    | [a14e0f5083](https://linux-hardware.org/?probe=a14e0f5083) | Mar 14, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [044b9f1cf9](https://linux-hardware.org/?probe=044b9f1cf9) | Mar 13, 2024 |
| Fujitsu Si... | AMILO Li 2727               | [4e7fe59e31](https://linux-hardware.org/?probe=4e7fe59e31) | Mar 13, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [89f277edc6](https://linux-hardware.org/?probe=89f277edc6) | Mar 13, 2024 |
| Dell          | Inspiron 3542               | [b1d7825b45](https://linux-hardware.org/?probe=b1d7825b45) | Mar 13, 2024 |
| Dell          | Inspiron 3542               | [8146ec44da](https://linux-hardware.org/?probe=8146ec44da) | Mar 13, 2024 |
| Dell          | Inspiron 3542               | [004f9952b4](https://linux-hardware.org/?probe=004f9952b4) | Mar 13, 2024 |
| Dell          | Latitude E6440              | [4f51ad06c1](https://linux-hardware.org/?probe=4f51ad06c1) | Mar 12, 2024 |
| Dell          | Latitude E6440              | [48d271828f](https://linux-hardware.org/?probe=48d271828f) | Mar 12, 2024 |
| HP            | ProBook 455 G1              | [a61c8a52d5](https://linux-hardware.org/?probe=a61c8a52d5) | Mar 12, 2024 |
| HP            | ProBook 455 G1              | [b61326e2fe](https://linux-hardware.org/?probe=b61326e2fe) | Mar 12, 2024 |
| HP            | ProBook 455 G1              | [31ba38a204](https://linux-hardware.org/?probe=31ba38a204) | Mar 12, 2024 |
| HP            | ProBook 455 G1              | [b3fb9458f2](https://linux-hardware.org/?probe=b3fb9458f2) | Mar 12, 2024 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | [268fefa14b](https://linux-hardware.org/?probe=268fefa14b) | Mar 12, 2024 |
| HP            | ProBook 455 G1              | [33d6628f25](https://linux-hardware.org/?probe=33d6628f25) | Mar 12, 2024 |
| Dell          | Latitude E6230              | [9f3d83bb2e](https://linux-hardware.org/?probe=9f3d83bb2e) | Mar 11, 2024 |
| Dell          | Latitude E6230              | [9d6a4dad8d](https://linux-hardware.org/?probe=9d6a4dad8d) | Mar 11, 2024 |
| HP            | ProBook 455 G1              | [8cf6a45c74](https://linux-hardware.org/?probe=8cf6a45c74) | Mar 11, 2024 |
| HP            | ProBook 455 G1              | [6db391732c](https://linux-hardware.org/?probe=6db391732c) | Mar 11, 2024 |
| HP            | ProBook 455 G1              | [f553df5906](https://linux-hardware.org/?probe=f553df5906) | Mar 11, 2024 |
| HP            | ProBook 455 G1              | [3e07d3db1c](https://linux-hardware.org/?probe=3e07d3db1c) | Mar 11, 2024 |
| Dell          | Latitude 5501               | [38df224a3f](https://linux-hardware.org/?probe=38df224a3f) | Mar 10, 2024 |
| Dell          | Latitude 5501               | [9bf3b70fdc](https://linux-hardware.org/?probe=9bf3b70fdc) | Mar 10, 2024 |
| HP            | Compaq 15                   | [933a624e6f](https://linux-hardware.org/?probe=933a624e6f) | Mar 10, 2024 |
| eMachines     | E525                        | [025c5c7d72](https://linux-hardware.org/?probe=025c5c7d72) | Mar 10, 2024 |
| ASUSTek       | K53BY                       | [16d91e8a4e](https://linux-hardware.org/?probe=16d91e8a4e) | Mar 10, 2024 |
| HP            | 530                         | [4027275e1e](https://linux-hardware.org/?probe=4027275e1e) | Mar 10, 2024 |
| HP            | ProBook 430 G3              | [f631777def](https://linux-hardware.org/?probe=f631777def) | Mar 09, 2024 |
| HP            | ProBook 430 G3              | [9f3f002632](https://linux-hardware.org/?probe=9f3f002632) | Mar 09, 2024 |
| Dell          | Latitude E4300              | [b5b51d6e8d](https://linux-hardware.org/?probe=b5b51d6e8d) | Mar 08, 2024 |
| Dell          | Latitude E4300              | [cdb623a5cf](https://linux-hardware.org/?probe=cdb623a5cf) | Mar 08, 2024 |
| Acer          | Aspire 5750                 | [5160c66ffb](https://linux-hardware.org/?probe=5160c66ffb) | Mar 08, 2024 |
| Acer          | Aspire 5750                 | [505c8aa361](https://linux-hardware.org/?probe=505c8aa361) | Mar 08, 2024 |
| HP            | ProBook 650 G2              | [93b1986cc2](https://linux-hardware.org/?probe=93b1986cc2) | Mar 07, 2024 |
| eMachines     | E725                        | [c9020b1bd8](https://linux-hardware.org/?probe=c9020b1bd8) | Mar 06, 2024 |
| ASUSTek       | UX32A                       | [2c11401160](https://linux-hardware.org/?probe=2c11401160) | Mar 06, 2024 |
| HP            | Pavilion dv7                | [f9ceb7f595](https://linux-hardware.org/?probe=f9ceb7f595) | Mar 06, 2024 |
| Acer          | Aspire 7738                 | [881cdc21ae](https://linux-hardware.org/?probe=881cdc21ae) | Mar 04, 2024 |
| Acer          | Aspire 7738                 | [799b49346a](https://linux-hardware.org/?probe=799b49346a) | Mar 04, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [7527854f8a](https://linux-hardware.org/?probe=7527854f8a) | Mar 04, 2024 |
| ASUSTek       | X550CL                      | [5805ba00d1](https://linux-hardware.org/?probe=5805ba00d1) | Mar 03, 2024 |
| HP            | ProBook 455 G1              | [38bfa9d3ce](https://linux-hardware.org/?probe=38bfa9d3ce) | Mar 01, 2024 |
| Lenovo        | G550 20023                  | [8ba9bb5abb](https://linux-hardware.org/?probe=8ba9bb5abb) | Mar 01, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [f308193329](https://linux-hardware.org/?probe=f308193329) | Mar 01, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [5d4ce61a86](https://linux-hardware.org/?probe=5d4ce61a86) | Mar 01, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [0196251cd6](https://linux-hardware.org/?probe=0196251cd6) | Mar 01, 2024 |
| Acer          | Aspire V5-121               | [9e2634a2f7](https://linux-hardware.org/?probe=9e2634a2f7) | Mar 01, 2024 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | [0eb65d42bc](https://linux-hardware.org/?probe=0eb65d42bc) | Feb 29, 2024 |
| HP            | ProBook 455 G1              | [fbe7d6e064](https://linux-hardware.org/?probe=fbe7d6e064) | Feb 29, 2024 |
| HP            | Compaq 6710b (KE121EA#AK... | [7d8b42acf1](https://linux-hardware.org/?probe=7d8b42acf1) | Feb 29, 2024 |
| ASUSTek       | X541NA                      | [8e85741592](https://linux-hardware.org/?probe=8e85741592) | Feb 29, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [722c76a7ca](https://linux-hardware.org/?probe=722c76a7ca) | Feb 28, 2024 |
| Lenovo        | ThinkPad T440s 20ARA0Y50... | [fcca63a62e](https://linux-hardware.org/?probe=fcca63a62e) | Feb 28, 2024 |
| Acer          | EX5235                      | [98b84f5c24](https://linux-hardware.org/?probe=98b84f5c24) | Feb 27, 2024 |
| Dell          | Latitude 7390               | [0fe5214832](https://linux-hardware.org/?probe=0fe5214832) | Feb 26, 2024 |
| Dell          | Latitude E7250              | [1e052f4295](https://linux-hardware.org/?probe=1e052f4295) | Feb 26, 2024 |
| HP            | Compaq 15                   | [d72d6ed080](https://linux-hardware.org/?probe=d72d6ed080) | Feb 26, 2024 |
| Samsung       | R530/R730/P530              | [a178c4f940](https://linux-hardware.org/?probe=a178c4f940) | Feb 26, 2024 |
| Dell          | Latitude E6520              | [572f49f06c](https://linux-hardware.org/?probe=572f49f06c) | Feb 25, 2024 |
| Samsung       | R530/R730/P530              | [4a557d45bc](https://linux-hardware.org/?probe=4a557d45bc) | Feb 25, 2024 |
| Lenovo        | G505s 20255                 | [40385fdfe2](https://linux-hardware.org/?probe=40385fdfe2) | Feb 25, 2024 |
| Toshiba       | Satellite L450              | [d5042332dd](https://linux-hardware.org/?probe=d5042332dd) | Feb 24, 2024 |
| Acer          | EX5235                      | [898256f492](https://linux-hardware.org/?probe=898256f492) | Feb 24, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [76aab23263](https://linux-hardware.org/?probe=76aab23263) | Feb 23, 2024 |
| eMachines     | E725                        | [2f82c253cf](https://linux-hardware.org/?probe=2f82c253cf) | Feb 23, 2024 |
| Acer          | Aspire E5-575G              | [4c03371299](https://linux-hardware.org/?probe=4c03371299) | Feb 22, 2024 |
| Acer          | Aspire E5-575G              | [f26ddca849](https://linux-hardware.org/?probe=f26ddca849) | Feb 22, 2024 |
| ASUSTek       | X541SA                      | [5da541263b](https://linux-hardware.org/?probe=5da541263b) | Feb 21, 2024 |
| Lenovo        | ThinkPad L470 20J5S2RA00    | [cafc678da6](https://linux-hardware.org/?probe=cafc678da6) | Feb 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [d6abb294f4](https://linux-hardware.org/?probe=d6abb294f4) | Feb 20, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [0d2fe29e16](https://linux-hardware.org/?probe=0d2fe29e16) | Feb 20, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [7cccaa021a](https://linux-hardware.org/?probe=7cccaa021a) | Feb 20, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [13aee4c968](https://linux-hardware.org/?probe=13aee4c968) | Feb 19, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [e7f7c0235e](https://linux-hardware.org/?probe=e7f7c0235e) | Feb 19, 2024 |
| Lenovo        | ThinkPad X200 74595FG       | [164d346b67](https://linux-hardware.org/?probe=164d346b67) | Feb 18, 2024 |
| Dell          | Inspiron 5558               | [8e1a67c565](https://linux-hardware.org/?probe=8e1a67c565) | Feb 18, 2024 |
| HP            | Pavilion dv6                | [30a1d043d5](https://linux-hardware.org/?probe=30a1d043d5) | Feb 18, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [d1ae872fcd](https://linux-hardware.org/?probe=d1ae872fcd) | Feb 18, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [1ec748cdd4](https://linux-hardware.org/?probe=1ec748cdd4) | Feb 18, 2024 |
| HP            | EliteBook 8570w             | [93fa82661b](https://linux-hardware.org/?probe=93fa82661b) | Feb 18, 2024 |
| Dell          | Inspiron 5567               | [77042df39a](https://linux-hardware.org/?probe=77042df39a) | Feb 18, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [980a3f6e0e](https://linux-hardware.org/?probe=980a3f6e0e) | Feb 17, 2024 |
| Dell          | Latitude E6540              | [ac5c8c3a96](https://linux-hardware.org/?probe=ac5c8c3a96) | Feb 17, 2024 |
| Dell          | Latitude E5250              | [1079517ab7](https://linux-hardware.org/?probe=1079517ab7) | Feb 17, 2024 |
| Dell          | Latitude E6220              | [41583d4638](https://linux-hardware.org/?probe=41583d4638) | Feb 16, 2024 |
| ASUSTek       | K54HR                       | [b573486a80](https://linux-hardware.org/?probe=b573486a80) | Feb 16, 2024 |
| Dell          | Latitude E5250              | [9fc8178d12](https://linux-hardware.org/?probe=9fc8178d12) | Feb 15, 2024 |
| Medion        | E7220                       | [7ab5fb1ba6](https://linux-hardware.org/?probe=7ab5fb1ba6) | Feb 15, 2024 |
| Acer          | Aspire 5750ZG               | [2a57a4a8c6](https://linux-hardware.org/?probe=2a57a4a8c6) | Feb 15, 2024 |
| Lenovo        | ThinkPad T500 2056CL8       | [a50088ad4a](https://linux-hardware.org/?probe=a50088ad4a) | Feb 15, 2024 |
| Acer          | TravelMate P215-52          | [83bbc1c6c9](https://linux-hardware.org/?probe=83bbc1c6c9) | Feb 15, 2024 |
| Dell          | Latitude E5410              | [530aadfacc](https://linux-hardware.org/?probe=530aadfacc) | Feb 15, 2024 |
| HP            | ProBook 650 G2              | [f304239696](https://linux-hardware.org/?probe=f304239696) | Feb 14, 2024 |
| ASUSTek       | K54HR                       | [c55115ae2a](https://linux-hardware.org/?probe=c55115ae2a) | Feb 13, 2024 |
| HP            | Laptop 15-dw1xxx            | [257ef56895](https://linux-hardware.org/?probe=257ef56895) | Feb 13, 2024 |
| Apple         | MacBookPro5,1               | [d75cce37b1](https://linux-hardware.org/?probe=d75cce37b1) | Feb 13, 2024 |
| Dell          | Latitude E5520              | [a9081eadde](https://linux-hardware.org/?probe=a9081eadde) | Feb 13, 2024 |
| HP            | 250 G1                      | [763a7bd9b9](https://linux-hardware.org/?probe=763a7bd9b9) | Feb 13, 2024 |
| Fujitsu       | LIFEBOOK U745               | [1688a50d1e](https://linux-hardware.org/?probe=1688a50d1e) | Feb 12, 2024 |
| Lenovo        | G550 20023                  | [aecea25db9](https://linux-hardware.org/?probe=aecea25db9) | Feb 12, 2024 |
| Fujitsu       | LIFEBOOK U745               | [e4aae3223d](https://linux-hardware.org/?probe=e4aae3223d) | Feb 12, 2024 |
| Dell          | Latitude 5480               | [94fe2aa10d](https://linux-hardware.org/?probe=94fe2aa10d) | Feb 12, 2024 |
| Dell          | Latitude E7240              | [53c500181c](https://linux-hardware.org/?probe=53c500181c) | Feb 11, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [8e1a4bf348](https://linux-hardware.org/?probe=8e1a4bf348) | Feb 11, 2024 |
| HP            | 650                         | [ff19b46e6b](https://linux-hardware.org/?probe=ff19b46e6b) | Feb 11, 2024 |
| HP            | 250 G1                      | [c4666d7fd3](https://linux-hardware.org/?probe=c4666d7fd3) | Feb 11, 2024 |
| Lenovo        | Flex 2-15D 20377            | [d35bcfd4ab](https://linux-hardware.org/?probe=d35bcfd4ab) | Feb 11, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [4c6b2bc534](https://linux-hardware.org/?probe=4c6b2bc534) | Feb 11, 2024 |
| Dell          | Inspiron 5558               | [aad0bc9f91](https://linux-hardware.org/?probe=aad0bc9f91) | Feb 11, 2024 |
| Fujitsu       | LIFEBOOK A555               | [6680a7379f](https://linux-hardware.org/?probe=6680a7379f) | Feb 10, 2024 |
| Fujitsu       | LIFEBOOK A512               | [7ec4aa564c](https://linux-hardware.org/?probe=7ec4aa564c) | Feb 10, 2024 |
| Toshiba       | Satellite L500              | [cf27175afe](https://linux-hardware.org/?probe=cf27175afe) | Feb 10, 2024 |
| Fujitsu       | LIFEBOOK A530               | [0c29733abb](https://linux-hardware.org/?probe=0c29733abb) | Feb 09, 2024 |
| Dell          | Vostro 3500                 | [add4d7702b](https://linux-hardware.org/?probe=add4d7702b) | Feb 09, 2024 |
| HP            | ProBook 450 G1              | [a7c4eba2e5](https://linux-hardware.org/?probe=a7c4eba2e5) | Feb 09, 2024 |
| Apple         | MacBookAir5,2               | [003eb18536](https://linux-hardware.org/?probe=003eb18536) | Feb 09, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [69ed9fbfdd](https://linux-hardware.org/?probe=69ed9fbfdd) | Feb 09, 2024 |
| Dell          | Inspiron 17 7000 Series ... | [22b25994b5](https://linux-hardware.org/?probe=22b25994b5) | Feb 09, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [dd560cf505](https://linux-hardware.org/?probe=dd560cf505) | Feb 09, 2024 |
| Fujitsu       | LIFEBOOK A512               | [ecbc2a4791](https://linux-hardware.org/?probe=ecbc2a4791) | Feb 08, 2024 |
| Lenovo        | ThinkPad T400 2768WGB       | [b03d2cbb00](https://linux-hardware.org/?probe=b03d2cbb00) | Feb 08, 2024 |
| HP            | Notebook                    | [325c3db46c](https://linux-hardware.org/?probe=325c3db46c) | Feb 08, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [64d88e023c](https://linux-hardware.org/?probe=64d88e023c) | Feb 08, 2024 |
| Dell          | Latitude E6230              | [be690710c1](https://linux-hardware.org/?probe=be690710c1) | Feb 08, 2024 |
| Lenovo        | ThinkPad T410 2537VFQ       | [c1ed2f5d1d](https://linux-hardware.org/?probe=c1ed2f5d1d) | Feb 08, 2024 |
| Acer          | Aspire E1-571               | [8dfa1ec3ed](https://linux-hardware.org/?probe=8dfa1ec3ed) | Feb 08, 2024 |
| eMachines     | E725                        | [f476a7c5da](https://linux-hardware.org/?probe=f476a7c5da) | Feb 08, 2024 |
| HP            | ProBook 650 G2              | [f24353913b](https://linux-hardware.org/?probe=f24353913b) | Feb 08, 2024 |
| ASUSTek       | X541SA                      | [e763494c80](https://linux-hardware.org/?probe=e763494c80) | Feb 07, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | [b416d53662](https://linux-hardware.org/?probe=b416d53662) | Feb 07, 2024 |
| Acer          | TravelMate P215-52          | [ba98fb542b](https://linux-hardware.org/?probe=ba98fb542b) | Feb 06, 2024 |
| HP            | 250 G1                      | [ae71670f43](https://linux-hardware.org/?probe=ae71670f43) | Feb 06, 2024 |
| Acer          | Aspire A114-31              | [067304d657](https://linux-hardware.org/?probe=067304d657) | Feb 06, 2024 |
| ASUSTek       | X55U                        | [e11bc4cf1c](https://linux-hardware.org/?probe=e11bc4cf1c) | Feb 06, 2024 |
| Apple         | MacBookAir5,2               | [4936c65b66](https://linux-hardware.org/?probe=4936c65b66) | Feb 06, 2024 |
| HP            | 250 G1                      | [2183b2a7c8](https://linux-hardware.org/?probe=2183b2a7c8) | Feb 06, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [63bb44eed5](https://linux-hardware.org/?probe=63bb44eed5) | Feb 06, 2024 |
| Toshiba       | Satellite L450              | [b2e699c155](https://linux-hardware.org/?probe=b2e699c155) | Feb 06, 2024 |
| Toshiba       | Satellite L450              | [49a92fe54f](https://linux-hardware.org/?probe=49a92fe54f) | Feb 06, 2024 |
| AWOW          | AK41                        | [622838c8ff](https://linux-hardware.org/?probe=622838c8ff) | Feb 06, 2024 |
| MSI           | GT60 2OC/2OD                | [77186f987a](https://linux-hardware.org/?probe=77186f987a) | Feb 05, 2024 |
| Lenovo        | ThinkPad T410 2537VFQ       | [677162fdcb](https://linux-hardware.org/?probe=677162fdcb) | Feb 05, 2024 |
| Lenovo        | ThinkPad T480s 20L70059M... | [19b52f3744](https://linux-hardware.org/?probe=19b52f3744) | Feb 05, 2024 |
| Dell          | Inspiron 17 7000 Series ... | [ac5865b6df](https://linux-hardware.org/?probe=ac5865b6df) | Feb 04, 2024 |
| ASUSTek       | X200MA                      | [0ad5383685](https://linux-hardware.org/?probe=0ad5383685) | Feb 04, 2024 |
| Google        | Kefka                       | [fe649957f9](https://linux-hardware.org/?probe=fe649957f9) | Feb 04, 2024 |
| Google        | Kefka                       | [133aedd402](https://linux-hardware.org/?probe=133aedd402) | Feb 04, 2024 |
| MSI           | CR620                       | [738e384612](https://linux-hardware.org/?probe=738e384612) | Feb 04, 2024 |
| Lenovo        | Flex 2-15D 20377            | [c1e928308b](https://linux-hardware.org/?probe=c1e928308b) | Feb 04, 2024 |
| HP            | Laptop 15-dw1xxx            | [bb65d3b37c](https://linux-hardware.org/?probe=bb65d3b37c) | Feb 04, 2024 |
| Toshiba       | Satellite L500              | [1bf3363342](https://linux-hardware.org/?probe=1bf3363342) | Feb 03, 2024 |
| ASUSTek       | K54HR                       | [d19f02e6c7](https://linux-hardware.org/?probe=d19f02e6c7) | Feb 03, 2024 |
| Lenovo        | ThinkPad X230 2333A91       | [6b6678eed7](https://linux-hardware.org/?probe=6b6678eed7) | Feb 03, 2024 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [92429be3e2](https://linux-hardware.org/?probe=92429be3e2) | Feb 03, 2024 |
| HP            | 650                         | [02e7184f0a](https://linux-hardware.org/?probe=02e7184f0a) | Feb 03, 2024 |
| Dell          | Latitude E6220              | [b8c542661d](https://linux-hardware.org/?probe=b8c542661d) | Feb 03, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [6300a79454](https://linux-hardware.org/?probe=6300a79454) | Feb 02, 2024 |
| eMachines     | E725                        | [e421aa20d1](https://linux-hardware.org/?probe=e421aa20d1) | Feb 02, 2024 |
| Dell          | Inspiron 5567               | [51c9bc9ff2](https://linux-hardware.org/?probe=51c9bc9ff2) | Feb 02, 2024 |
| Medion        | E7218                       | [d99d2a5d9c](https://linux-hardware.org/?probe=d99d2a5d9c) | Feb 02, 2024 |
| Lenovo        | G505s 20255                 | [f1903f6323](https://linux-hardware.org/?probe=f1903f6323) | Feb 02, 2024 |
| Acer          | TravelMate P215-52          | [917516e40b](https://linux-hardware.org/?probe=917516e40b) | Feb 01, 2024 |
| HP            | 250 G1                      | [af6c2e58b5](https://linux-hardware.org/?probe=af6c2e58b5) | Feb 01, 2024 |
| HP            | 250 G1                      | [1cc61ac6b5](https://linux-hardware.org/?probe=1cc61ac6b5) | Feb 01, 2024 |
| HP            | 250 G1                      | [b99ad906cf](https://linux-hardware.org/?probe=b99ad906cf) | Feb 01, 2024 |
| ASUSTek       | X541SA                      | [6bd34cb6e0](https://linux-hardware.org/?probe=6bd34cb6e0) | Jan 31, 2024 |
| ASUSTek       | X541SA                      | [8477157f76](https://linux-hardware.org/?probe=8477157f76) | Jan 31, 2024 |
| Apple         | MacBookPro5,1               | [85b45c9a2f](https://linux-hardware.org/?probe=85b45c9a2f) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | [e12d7e5691](https://linux-hardware.org/?probe=e12d7e5691) | Jan 31, 2024 |
| Apple         | MacBook5,1                  | [68076b1cbd](https://linux-hardware.org/?probe=68076b1cbd) | Jan 31, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [809fd2e9fa](https://linux-hardware.org/?probe=809fd2e9fa) | Jan 30, 2024 |
| HP            | ProBook 650 G2              | [cd22b7035d](https://linux-hardware.org/?probe=cd22b7035d) | Jan 30, 2024 |
| HP            | EliteBook 8570w             | [90936fe065](https://linux-hardware.org/?probe=90936fe065) | Jan 30, 2024 |
| Dell          | Latitude E7240              | [3093481906](https://linux-hardware.org/?probe=3093481906) | Jan 30, 2024 |
| ASUSTek       | ZenBook UX425UA_UM425UA     | [2585f65922](https://linux-hardware.org/?probe=2585f65922) | Jan 30, 2024 |
| Acer          | Aspire E1-571               | [261ad8d1d0](https://linux-hardware.org/?probe=261ad8d1d0) | Jan 30, 2024 |
| AWOW          | AK41                        | [4e8816ed0c](https://linux-hardware.org/?probe=4e8816ed0c) | Jan 30, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [e94c77f59d](https://linux-hardware.org/?probe=e94c77f59d) | Jan 30, 2024 |
| HP            | 250 G1                      | [2e10da4cf7](https://linux-hardware.org/?probe=2e10da4cf7) | Jan 30, 2024 |
| Dell          | Latitude 7390               | [defc75091c](https://linux-hardware.org/?probe=defc75091c) | Jan 30, 2024 |
| Toshiba       | Satellite M50D-A            | [4d7778b932](https://linux-hardware.org/?probe=4d7778b932) | Jan 30, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [8ee7ee6174](https://linux-hardware.org/?probe=8ee7ee6174) | Jan 30, 2024 |
| HP            | Notebook                    | [9203e745cd](https://linux-hardware.org/?probe=9203e745cd) | Jan 29, 2024 |
| Acer          | Aspire E5-575G              | [d4fdcb8580](https://linux-hardware.org/?probe=d4fdcb8580) | Jan 29, 2024 |
| ASUSTek       | K54HR                       | [171ab4ceee](https://linux-hardware.org/?probe=171ab4ceee) | Jan 29, 2024 |
| ASUSTek       | X55U                        | [d62fec19c9](https://linux-hardware.org/?probe=d62fec19c9) | Jan 29, 2024 |
| Acer          | Aspire A114-31              | [9c767147fc](https://linux-hardware.org/?probe=9c767147fc) | Jan 29, 2024 |
| Dell          | Latitude E5520              | [904d3d23cb](https://linux-hardware.org/?probe=904d3d23cb) | Jan 29, 2024 |
| MSI           | GT60 2OC/2OD                | [182643a957](https://linux-hardware.org/?probe=182643a957) | Jan 29, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [169bc52190](https://linux-hardware.org/?probe=169bc52190) | Jan 29, 2024 |
| Lenovo        | ThinkPad T410 2537VFQ       | [e007b6155a](https://linux-hardware.org/?probe=e007b6155a) | Jan 29, 2024 |
| Apple         | MacBookAir5,2               | [7d2b32915e](https://linux-hardware.org/?probe=7d2b32915e) | Jan 29, 2024 |
| Dell          | Latitude E6540              | [1d94b95f41](https://linux-hardware.org/?probe=1d94b95f41) | Jan 28, 2024 |
| HP            | Pavilion dv6                | [68d4e31014](https://linux-hardware.org/?probe=68d4e31014) | Jan 28, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [2b39dd89e1](https://linux-hardware.org/?probe=2b39dd89e1) | Jan 28, 2024 |
| Dell          | Inspiron 5567               | [6dcfbe7bb7](https://linux-hardware.org/?probe=6dcfbe7bb7) | Jan 28, 2024 |
| Dell          | Inspiron 5558               | [d4df85a4b6](https://linux-hardware.org/?probe=d4df85a4b6) | Jan 28, 2024 |
| Dell          | Latitude E6230              | [9225ea832f](https://linux-hardware.org/?probe=9225ea832f) | Jan 28, 2024 |
| Dell          | Inspiron 3521               | [c1602b9504](https://linux-hardware.org/?probe=c1602b9504) | Jan 28, 2024 |
| Dell          | Inspiron 17 7000 Series ... | [f9adbc6592](https://linux-hardware.org/?probe=f9adbc6592) | Jan 28, 2024 |
| Lenovo        | ThinkPad T400 2768WGB       | [dd4a6395ad](https://linux-hardware.org/?probe=dd4a6395ad) | Jan 28, 2024 |
| Lenovo        | Flex 2-15D 20377            | [4f358fd188](https://linux-hardware.org/?probe=4f358fd188) | Jan 28, 2024 |
| Lenovo        | ThinkPad T440s 20ARA0Y50... | [4010d9f5db](https://linux-hardware.org/?probe=4010d9f5db) | Jan 27, 2024 |
| Dell          | Latitude 5480               | [1af6d00744](https://linux-hardware.org/?probe=1af6d00744) | Jan 27, 2024 |
| eMachines     | E725                        | [84147d8349](https://linux-hardware.org/?probe=84147d8349) | Jan 27, 2024 |
| ASUSTek       | X551CA                      | [2147b3f8f3](https://linux-hardware.org/?probe=2147b3f8f3) | Jan 27, 2024 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [4d86c780d1](https://linux-hardware.org/?probe=4d86c780d1) | Jan 27, 2024 |
| HP            | Laptop 15-dw1xxx            | [a7ed96434c](https://linux-hardware.org/?probe=a7ed96434c) | Jan 27, 2024 |
| Dell          | Latitude E6230              | [37f5e13538](https://linux-hardware.org/?probe=37f5e13538) | Jan 26, 2024 |
| Acer          | Aspire E1-571               | [312d47e134](https://linux-hardware.org/?probe=312d47e134) | Jan 26, 2024 |
| HP            | 250 G1                      | [521decddfe](https://linux-hardware.org/?probe=521decddfe) | Jan 26, 2024 |
| eMachines     | E725                        | [112f370e34](https://linux-hardware.org/?probe=112f370e34) | Jan 26, 2024 |
| Lenovo        | G505s 20255                 | [b3fb33d826](https://linux-hardware.org/?probe=b3fb33d826) | Jan 25, 2024 |
| HP            | ProBook 650 G2              | [169fd21256](https://linux-hardware.org/?probe=169fd21256) | Jan 25, 2024 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [7e4faa6c08](https://linux-hardware.org/?probe=7e4faa6c08) | Jan 25, 2024 |
| Dell          | Latitude 7390               | [ba979ded0e](https://linux-hardware.org/?probe=ba979ded0e) | Jan 24, 2024 |
| Acer          | TravelMate P215-52          | [6796026981](https://linux-hardware.org/?probe=6796026981) | Jan 24, 2024 |
| Lenovo        | ThinkPad T410 2537VFQ       | [50080cf267](https://linux-hardware.org/?probe=50080cf267) | Jan 24, 2024 |
| Acer          | TravelMate 8371             | [e8e5b4c378](https://linux-hardware.org/?probe=e8e5b4c378) | Jan 24, 2024 |
| Acer          | TravelMate 8371             | [fb2f053fd4](https://linux-hardware.org/?probe=fb2f053fd4) | Jan 24, 2024 |
| HP            | 650                         | [dd3291b0b8](https://linux-hardware.org/?probe=dd3291b0b8) | Jan 24, 2024 |
| Acer          | Aspire A114-31              | [f08742602c](https://linux-hardware.org/?probe=f08742602c) | Jan 23, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [c4dcf1f288](https://linux-hardware.org/?probe=c4dcf1f288) | Jan 23, 2024 |
| Dell          | Latitude 5480               | [c833a05833](https://linux-hardware.org/?probe=c833a05833) | Jan 23, 2024 |
| MSI           | GT60 2OC/2OD                | [2a30b19d47](https://linux-hardware.org/?probe=2a30b19d47) | Jan 23, 2024 |
| Dell          | Inspiron 7737               | [6b9c1b8d86](https://linux-hardware.org/?probe=6b9c1b8d86) | Jan 23, 2024 |
| Fujitsu       | LIFEBOOK A555               | [136059d131](https://linux-hardware.org/?probe=136059d131) | Jan 23, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [09cb74358d](https://linux-hardware.org/?probe=09cb74358d) | Jan 23, 2024 |
| HP            | 250 G1                      | [1fe3185392](https://linux-hardware.org/?probe=1fe3185392) | Jan 23, 2024 |
| Dell          | Latitude E6220              | [4a2011df5b](https://linux-hardware.org/?probe=4a2011df5b) | Jan 23, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [4ae03ead13](https://linux-hardware.org/?probe=4ae03ead13) | Jan 22, 2024 |
| Lenovo        | V15-ADA 82C7                | [84e28771e9](https://linux-hardware.org/?probe=84e28771e9) | Jan 22, 2024 |
| Toshiba       | Satellite L500              | [3a68e22a09](https://linux-hardware.org/?probe=3a68e22a09) | Jan 22, 2024 |
| ASUSTek       | X55U                        | [2f57cfccb4](https://linux-hardware.org/?probe=2f57cfccb4) | Jan 22, 2024 |
| Samsung       | NC10                        | [75275f27da](https://linux-hardware.org/?probe=75275f27da) | Jan 22, 2024 |
| Fujitsu       | LIFEBOOK A512               | [be9e04db5f](https://linux-hardware.org/?probe=be9e04db5f) | Jan 21, 2024 |
| Fujitsu       | LIFEBOOK A512               | [2b0f56de19](https://linux-hardware.org/?probe=2b0f56de19) | Jan 21, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [2a24247ca2](https://linux-hardware.org/?probe=2a24247ca2) | Jan 20, 2024 |
| Lenovo        | ThinkPad T440s 20ARA0Y50... | [04f5d15e0c](https://linux-hardware.org/?probe=04f5d15e0c) | Jan 20, 2024 |
| Fujitsu Si... | LIFEBOOK S7110              | [c5b364eec0](https://linux-hardware.org/?probe=c5b364eec0) | Jan 19, 2024 |
| ASUSTek       | G551JW                      | [60145f8dc4](https://linux-hardware.org/?probe=60145f8dc4) | Jan 19, 2024 |
| ASUSTek       | G551JW                      | [de74c01024](https://linux-hardware.org/?probe=de74c01024) | Jan 19, 2024 |
| Medion        | E7218                       | [4d82edaf22](https://linux-hardware.org/?probe=4d82edaf22) | Jan 18, 2024 |
| Fujitsu Si... | LIFEBOOK S7110              | [59e61beacb](https://linux-hardware.org/?probe=59e61beacb) | Jan 17, 2024 |
| Lenovo        | ThinkPad T420 4236B87       | [e7afcc3ce9](https://linux-hardware.org/?probe=e7afcc3ce9) | Jan 14, 2024 |
| Lenovo        | B50-30 20382                | [e98a3e78f4](https://linux-hardware.org/?probe=e98a3e78f4) | Jan 14, 2024 |
| Lenovo        | ThinkPad T420 4236B87       | [e6f7ad5a81](https://linux-hardware.org/?probe=e6f7ad5a81) | Jan 14, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [60d61005cb](https://linux-hardware.org/?probe=60d61005cb) | Jan 14, 2024 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [a4ccd82a41](https://linux-hardware.org/?probe=a4ccd82a41) | Jan 14, 2024 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [0a6e40447c](https://linux-hardware.org/?probe=0a6e40447c) | Jan 14, 2024 |
| Acer          | Aspire V5-121               | [95cd91d3ff](https://linux-hardware.org/?probe=95cd91d3ff) | Jan 13, 2024 |
| Acer          | Aspire V5-121               | [278f45c6db](https://linux-hardware.org/?probe=278f45c6db) | Jan 13, 2024 |
| Dell          | Inspiron 3521               | [5569799f07](https://linux-hardware.org/?probe=5569799f07) | Jan 13, 2024 |
| ASUSTek       | X541NA                      | [f909e0ce7b](https://linux-hardware.org/?probe=f909e0ce7b) | Jan 13, 2024 |
| Dell          | Latitude 3350               | [cadeab67e5](https://linux-hardware.org/?probe=cadeab67e5) | Jan 12, 2024 |
| Dell          | Inspiron 5559               | [cab13bdc85](https://linux-hardware.org/?probe=cab13bdc85) | Jan 11, 2024 |
| Lenovo        | G505s 20255                 | [2d6c3b77e9](https://linux-hardware.org/?probe=2d6c3b77e9) | Jan 10, 2024 |
| Dell          | Vostro 1015                 | [4a3e247dd8](https://linux-hardware.org/?probe=4a3e247dd8) | Jan 09, 2024 |
| Samsung       | 300E4C/300E5C/300E7C        | [070c844364](https://linux-hardware.org/?probe=070c844364) | Jan 09, 2024 |
| HP            | Notebook                    | [45febe4c2e](https://linux-hardware.org/?probe=45febe4c2e) | Jan 08, 2024 |
| Dell          | Latitude 5480               | [1ac1a307dc](https://linux-hardware.org/?probe=1ac1a307dc) | Jan 08, 2024 |
| Dell          | Inspiron 3521               | [2b8bf09bd1](https://linux-hardware.org/?probe=2b8bf09bd1) | Jan 08, 2024 |
| Dell          | Inspiron 3521               | [2a29a6c24b](https://linux-hardware.org/?probe=2a29a6c24b) | Jan 08, 2024 |
| Lenovo        | IdeaPad 3-15ITL6 82H8       | [a50c2be0bd](https://linux-hardware.org/?probe=a50c2be0bd) | Jan 08, 2024 |
| HP            | EliteBook 8570w             | [2c4d04c553](https://linux-hardware.org/?probe=2c4d04c553) | Jan 08, 2024 |
| AWOW          | AK41                        | [62d6e6b631](https://linux-hardware.org/?probe=62d6e6b631) | Jan 08, 2024 |
| HP            | 250 G1                      | [74853cc60e](https://linux-hardware.org/?probe=74853cc60e) | Jan 08, 2024 |
| Dell          | Inspiron 15-3567            | [fe8b450484](https://linux-hardware.org/?probe=fe8b450484) | Jan 07, 2024 |
| Acer          | Aspire E5-575G              | [54ae8808da](https://linux-hardware.org/?probe=54ae8808da) | Jan 07, 2024 |
| ASUSTek       | 1001PX                      | [c1b065d9d5](https://linux-hardware.org/?probe=c1b065d9d5) | Jan 07, 2024 |
| Dell          | Inspiron 5558               | [ee83fbddaf](https://linux-hardware.org/?probe=ee83fbddaf) | Jan 07, 2024 |
| ASUSTek       | X551CA                      | [78faa77bac](https://linux-hardware.org/?probe=78faa77bac) | Jan 06, 2024 |
| Lenovo        | B50-30 20382                | [d4e763662a](https://linux-hardware.org/?probe=d4e763662a) | Jan 06, 2024 |
| Acer          | Aspire 5750ZG               | [8325c5264f](https://linux-hardware.org/?probe=8325c5264f) | Jan 06, 2024 |
| eMachines     | E725                        | [2f966d5eeb](https://linux-hardware.org/?probe=2f966d5eeb) | Jan 06, 2024 |
| Fujitsu       | LIFEBOOK A530               | [6b26d6ac5e](https://linux-hardware.org/?probe=6b26d6ac5e) | Jan 06, 2024 |
| Fujitsu       | LIFEBOOK A530               | [d01bdc4286](https://linux-hardware.org/?probe=d01bdc4286) | Jan 06, 2024 |
| Dell          | Inspiron MXC061             | [bbc09ef129](https://linux-hardware.org/?probe=bbc09ef129) | Jan 05, 2024 |
| ASUSTek       | K54HR                       | [8e42bbee46](https://linux-hardware.org/?probe=8e42bbee46) | Jan 05, 2024 |
| HP            | Pavilion dv6                | [d0a6270f74](https://linux-hardware.org/?probe=d0a6270f74) | Jan 04, 2024 |
| Lenovo        | Flex 2-15D 20377            | [69b6518a5c](https://linux-hardware.org/?probe=69b6518a5c) | Jan 04, 2024 |
| Sony          | VPCS13V9E                   | [5dbb868168](https://linux-hardware.org/?probe=5dbb868168) | Jan 03, 2024 |
| ASUSTek       | X200MA                      | [8898e6d6d3](https://linux-hardware.org/?probe=8898e6d6d3) | Jan 03, 2024 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [934cb11b0b](https://linux-hardware.org/?probe=934cb11b0b) | Jan 03, 2024 |
| HP            | 650                         | [11be3085af](https://linux-hardware.org/?probe=11be3085af) | Jan 03, 2024 |
| eMachines     | E725                        | [e3c0315f84](https://linux-hardware.org/?probe=e3c0315f84) | Jan 03, 2024 |
| Dell          | Latitude E7240              | [1ddcf15c95](https://linux-hardware.org/?probe=1ddcf15c95) | Jan 02, 2024 |
| eMachines     | E725                        | [1c62e8a613](https://linux-hardware.org/?probe=1c62e8a613) | Jan 02, 2024 |
| eMachines     | E725                        | [6485437ffb](https://linux-hardware.org/?probe=6485437ffb) | Jan 01, 2024 |
| ASUSTek       | K54HR                       | [c84a5fe9d7](https://linux-hardware.org/?probe=c84a5fe9d7) | Jan 01, 2024 |
| ASUSTek       | K54HR                       | [03ce083285](https://linux-hardware.org/?probe=03ce083285) | Jan 01, 2024 |
| eMachines     | E525                        | [a99f0e3394](https://linux-hardware.org/?probe=a99f0e3394) | Jan 01, 2024 |
| Dell          | Inspiron 15-3567            | [54e9b80fb3](https://linux-hardware.org/?probe=54e9b80fb3) | Jan 01, 2024 |
| Dell          | Inspiron 15-3567            | [c67f642893](https://linux-hardware.org/?probe=c67f642893) | Jan 01, 2024 |
| Fujitsu       | LIFEBOOK A530               | [044d66edb4](https://linux-hardware.org/?probe=044d66edb4) | Jan 01, 2024 |
| Lenovo        | ThinkPad T410 2537BF9       | [5d62cfc80b](https://linux-hardware.org/?probe=5d62cfc80b) | Jan 01, 2024 |
| Apple         | MacBookPro8,1               | [85665aae4c](https://linux-hardware.org/?probe=85665aae4c) | Dec 31, 2023 |
| ASUSTek       | K54HR                       | [0e5edd355d](https://linux-hardware.org/?probe=0e5edd355d) | Dec 31, 2023 |
| ASUSTek       | 1001PX                      | [e0e36774e8](https://linux-hardware.org/?probe=e0e36774e8) | Dec 31, 2023 |
| Dell          | Inspiron 5567               | [c271898460](https://linux-hardware.org/?probe=c271898460) | Dec 31, 2023 |
| Acer          | EX5235                      | [c92709aa57](https://linux-hardware.org/?probe=c92709aa57) | Dec 31, 2023 |
| Acer          | EX5235                      | [4a0cb756ff](https://linux-hardware.org/?probe=4a0cb756ff) | Dec 31, 2023 |
| Dell          | Latitude E6540              | [aa122de07a](https://linux-hardware.org/?probe=aa122de07a) | Dec 31, 2023 |
| HP            | ProBook 450 G1              | [a83eb9d306](https://linux-hardware.org/?probe=a83eb9d306) | Dec 31, 2023 |
| HP            | 250 G1                      | [da6bcc5b27](https://linux-hardware.org/?probe=da6bcc5b27) | Dec 31, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [1258df680a](https://linux-hardware.org/?probe=1258df680a) | Dec 31, 2023 |
| Dell          | Latitude 5480               | [3d096bf8e4](https://linux-hardware.org/?probe=3d096bf8e4) | Dec 31, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [9894c7bf9f](https://linux-hardware.org/?probe=9894c7bf9f) | Dec 31, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [4582e28453](https://linux-hardware.org/?probe=4582e28453) | Dec 31, 2023 |
| Dell          | Latitude E5520              | [bdc879aa29](https://linux-hardware.org/?probe=bdc879aa29) | Dec 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [63794eecd3](https://linux-hardware.org/?probe=63794eecd3) | Dec 29, 2023 |
| HP            | Pavilion dv5                | [f347184b5c](https://linux-hardware.org/?probe=f347184b5c) | Dec 29, 2023 |
| Dell          | Latitude 5480               | [ddcc69c02c](https://linux-hardware.org/?probe=ddcc69c02c) | Dec 29, 2023 |
| Dell          | Latitude E6220              | [c106ee001b](https://linux-hardware.org/?probe=c106ee001b) | Dec 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [55a9c00e34](https://linux-hardware.org/?probe=55a9c00e34) | Dec 29, 2023 |
| ASUSTek       | K54HR                       | [ce4e5d4a5b](https://linux-hardware.org/?probe=ce4e5d4a5b) | Dec 29, 2023 |
| HP            | 250 G1                      | [c0c195904c](https://linux-hardware.org/?probe=c0c195904c) | Dec 29, 2023 |
| MSI           | GP75 Leopard 9SE            | [29e0740b9d](https://linux-hardware.org/?probe=29e0740b9d) | Dec 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [bb3e77da36](https://linux-hardware.org/?probe=bb3e77da36) | Dec 29, 2023 |
| HP            | ProBook 650 G2              | [1dd3970627](https://linux-hardware.org/?probe=1dd3970627) | Dec 29, 2023 |
| Dell          | Inspiron 5558               | [be6a80140f](https://linux-hardware.org/?probe=be6a80140f) | Dec 29, 2023 |
| eMachines     | E725                        | [b3be8d374c](https://linux-hardware.org/?probe=b3be8d374c) | Dec 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [fd565ed585](https://linux-hardware.org/?probe=fd565ed585) | Dec 28, 2023 |
| ASUSTek       | K54HR                       | [dca5908bc4](https://linux-hardware.org/?probe=dca5908bc4) | Dec 28, 2023 |
| HP            | EliteBook Folio 9480m       | [45adbe7c2a](https://linux-hardware.org/?probe=45adbe7c2a) | Dec 28, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [324bfb9f22](https://linux-hardware.org/?probe=324bfb9f22) | Dec 28, 2023 |
| HP            | Laptop 15-dw1xxx            | [86c11fc47f](https://linux-hardware.org/?probe=86c11fc47f) | Dec 28, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | [ecd05eabd6](https://linux-hardware.org/?probe=ecd05eabd6) | Dec 28, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [88fe73b44c](https://linux-hardware.org/?probe=88fe73b44c) | Dec 28, 2023 |
| MSI           | GT60 2OC/2OD                | [d0a3fb037a](https://linux-hardware.org/?probe=d0a3fb037a) | Dec 28, 2023 |
| Apple         | MacBookAir5,2               | [14b41c4c72](https://linux-hardware.org/?probe=14b41c4c72) | Dec 28, 2023 |
| Lenovo        | G70-70 80HW                 | [3b6b661f7d](https://linux-hardware.org/?probe=3b6b661f7d) | Dec 28, 2023 |
| AWOW          | AK41                        | [d081509ed9](https://linux-hardware.org/?probe=d081509ed9) | Dec 28, 2023 |
| Acer          | TravelMate P215-52          | [4191cc3d32](https://linux-hardware.org/?probe=4191cc3d32) | Dec 28, 2023 |
| eMachines     | E725                        | [1b90f2bf06](https://linux-hardware.org/?probe=1b90f2bf06) | Dec 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [594935ef8c](https://linux-hardware.org/?probe=594935ef8c) | Dec 27, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [6ce71dea49](https://linux-hardware.org/?probe=6ce71dea49) | Dec 27, 2023 |
| Acer          | Aspire A114-31              | [dfa2a6458d](https://linux-hardware.org/?probe=dfa2a6458d) | Dec 27, 2023 |
| HP            | EliteBook 8570w             | [4cd7501dc7](https://linux-hardware.org/?probe=4cd7501dc7) | Dec 27, 2023 |
| ASUSTek       | X55U                        | [a29a0b8a23](https://linux-hardware.org/?probe=a29a0b8a23) | Dec 27, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [9d710b8199](https://linux-hardware.org/?probe=9d710b8199) | Dec 27, 2023 |
| Dell          | Latitude 7390               | [32c3fcc941](https://linux-hardware.org/?probe=32c3fcc941) | Dec 27, 2023 |
| Dell          | Inspiron 7737               | [b0bde36cc7](https://linux-hardware.org/?probe=b0bde36cc7) | Dec 27, 2023 |
| HP            | EliteBook 2540p             | [a23b223ac4](https://linux-hardware.org/?probe=a23b223ac4) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3-15ITL6 82H8       | [b465280108](https://linux-hardware.org/?probe=b465280108) | Dec 27, 2023 |
| Lenovo        | IdeaPad 3-15ITL6 82H8       | [67849c584b](https://linux-hardware.org/?probe=67849c584b) | Dec 26, 2023 |
| Acer          | Aspire E1-532               | [c7d5bac798](https://linux-hardware.org/?probe=c7d5bac798) | Dec 26, 2023 |
| ASUSTek       | X55U                        | [a467fa6d5e](https://linux-hardware.org/?probe=a467fa6d5e) | Dec 25, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [4b67581412](https://linux-hardware.org/?probe=4b67581412) | Dec 25, 2023 |
| Sony          | VPCS13V9E                   | [61230cc69b](https://linux-hardware.org/?probe=61230cc69b) | Dec 24, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [fd501fc946](https://linux-hardware.org/?probe=fd501fc946) | Dec 23, 2023 |
| Sony          | VPCS13V9E                   | [05f387de9b](https://linux-hardware.org/?probe=05f387de9b) | Dec 23, 2023 |
| Lenovo        | IdeaPad 320-17ABR 80YN      | [7d9fabde46](https://linux-hardware.org/?probe=7d9fabde46) | Dec 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [bf31061d97](https://linux-hardware.org/?probe=bf31061d97) | Dec 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [a4ecaaf236](https://linux-hardware.org/?probe=a4ecaaf236) | Dec 23, 2023 |
| Dell          | Latitude E6410              | [7e14c30601](https://linux-hardware.org/?probe=7e14c30601) | Dec 23, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [2cc486fed2](https://linux-hardware.org/?probe=2cc486fed2) | Dec 23, 2023 |
| HP            | Notebook                    | [bb4cdbdf05](https://linux-hardware.org/?probe=bb4cdbdf05) | Dec 22, 2023 |
| HP            | Notebook                    | [1b95abcc1b](https://linux-hardware.org/?probe=1b95abcc1b) | Dec 22, 2023 |
| Dell          | Inspiron 3537               | [e4c0a2d0d7](https://linux-hardware.org/?probe=e4c0a2d0d7) | Dec 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [b8f11e5aeb](https://linux-hardware.org/?probe=b8f11e5aeb) | Dec 22, 2023 |
| Dell          | Inspiron 3537               | [41b209e906](https://linux-hardware.org/?probe=41b209e906) | Dec 22, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [7d521242f4](https://linux-hardware.org/?probe=7d521242f4) | Dec 22, 2023 |
| Lenovo        | Flex 2-15D 20377            | [a22602448b](https://linux-hardware.org/?probe=a22602448b) | Dec 22, 2023 |
| Lenovo        | G70-70 80HW                 | [b5d6e26b97](https://linux-hardware.org/?probe=b5d6e26b97) | Dec 21, 2023 |
| Dell          | Inspiron 5559               | [7666e1047d](https://linux-hardware.org/?probe=7666e1047d) | Dec 21, 2023 |
| eMachines     | E725                        | [7b9f0ee917](https://linux-hardware.org/?probe=7b9f0ee917) | Dec 20, 2023 |
| eMachines     | E725                        | [950542e12b](https://linux-hardware.org/?probe=950542e12b) | Dec 20, 2023 |
| Apple         | MacBookPro5,4               | [da996ce093](https://linux-hardware.org/?probe=da996ce093) | Dec 18, 2023 |
| Apple         | MacBookPro5,4               | [ee0f91ec22](https://linux-hardware.org/?probe=ee0f91ec22) | Dec 18, 2023 |
| HP            | Compaq 6710b                | [8a4026815f](https://linux-hardware.org/?probe=8a4026815f) | Dec 18, 2023 |
| HP            | Compaq 6710b                | [01324b2772](https://linux-hardware.org/?probe=01324b2772) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | [a7d805aa7c](https://linux-hardware.org/?probe=a7d805aa7c) | Dec 18, 2023 |
| Fujitsu       | LIFEBOOK A512               | [72663c66da](https://linux-hardware.org/?probe=72663c66da) | Dec 18, 2023 |
| Lenovo        | G70-70 80HW                 | [dc86fb0437](https://linux-hardware.org/?probe=dc86fb0437) | Dec 18, 2023 |
| Acer          | Aspire 7738                 | [1333627761](https://linux-hardware.org/?probe=1333627761) | Dec 17, 2023 |
| Acer          | Aspire 7738                 | [96b31f90ac](https://linux-hardware.org/?probe=96b31f90ac) | Dec 17, 2023 |
| ASUSTek       | K53BY                       | [db6b177a99](https://linux-hardware.org/?probe=db6b177a99) | Dec 17, 2023 |
| Lenovo        | ThinkPad T410 2537AL8       | [8749a1d67d](https://linux-hardware.org/?probe=8749a1d67d) | Dec 16, 2023 |
| Lenovo        | ThinkPad T410 2537AL8       | [9e40928011](https://linux-hardware.org/?probe=9e40928011) | Dec 15, 2023 |
| Apple         | MacBookPro5,4               | [89a318eaa6](https://linux-hardware.org/?probe=89a318eaa6) | Dec 14, 2023 |
| Apple         | MacBookPro5,4               | [1160e51426](https://linux-hardware.org/?probe=1160e51426) | Dec 14, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [a3ef12171e](https://linux-hardware.org/?probe=a3ef12171e) | Dec 13, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | [3cfb1663a2](https://linux-hardware.org/?probe=3cfb1663a2) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | [00de2ee3d8](https://linux-hardware.org/?probe=00de2ee3d8) | Dec 12, 2023 |
| ASUSTek       | K51AE                       | [382bc13632](https://linux-hardware.org/?probe=382bc13632) | Dec 12, 2023 |
| Acer          | Aspire A515-51G             | [13c7114723](https://linux-hardware.org/?probe=13c7114723) | Dec 12, 2023 |
| Lenovo        | G505s 20255                 | [446bcccc18](https://linux-hardware.org/?probe=446bcccc18) | Dec 11, 2023 |
| Dell          | Latitude 5480               | [cdc50c85ce](https://linux-hardware.org/?probe=cdc50c85ce) | Dec 10, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [f604df3e48](https://linux-hardware.org/?probe=f604df3e48) | Dec 10, 2023 |
| HP            | Pavilion dv7                | [853bcfa739](https://linux-hardware.org/?probe=853bcfa739) | Dec 10, 2023 |
| HP            | Pavilion dv7                | [354a9cc9b6](https://linux-hardware.org/?probe=354a9cc9b6) | Dec 10, 2023 |
| Acer          | Nitro AN515-51              | [5c9d12b2c0](https://linux-hardware.org/?probe=5c9d12b2c0) | Dec 10, 2023 |
| Acer          | Aspire E5-575G              | [2c8df80a5f](https://linux-hardware.org/?probe=2c8df80a5f) | Dec 09, 2023 |
| eMachines     | E525                        | [0b83a89d59](https://linux-hardware.org/?probe=0b83a89d59) | Dec 09, 2023 |
| Dell          | Latitude 5480               | [0dd9110b39](https://linux-hardware.org/?probe=0dd9110b39) | Dec 09, 2023 |
| eMachines     | E725                        | [7c8234f296](https://linux-hardware.org/?probe=7c8234f296) | Dec 08, 2023 |
| HP            | Notebook                    | [4d688ddd0c](https://linux-hardware.org/?probe=4d688ddd0c) | Dec 08, 2023 |
| ASUSTek       | X541NA                      | [82c95b312a](https://linux-hardware.org/?probe=82c95b312a) | Dec 07, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [ba710398bd](https://linux-hardware.org/?probe=ba710398bd) | Dec 06, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [4389884ac0](https://linux-hardware.org/?probe=4389884ac0) | Dec 05, 2023 |
| Fujitsu Si... | ESPRIMO Mobile U9210        | [84cbb3e6b5](https://linux-hardware.org/?probe=84cbb3e6b5) | Dec 05, 2023 |
| HP            | ProBook 650 G2              | [16cd39b5e2](https://linux-hardware.org/?probe=16cd39b5e2) | Dec 04, 2023 |
| Dell          | Latitude E6230              | [4c2a286dd8](https://linux-hardware.org/?probe=4c2a286dd8) | Dec 03, 2023 |
| Dell          | Latitude E6230              | [6ac9013399](https://linux-hardware.org/?probe=6ac9013399) | Dec 03, 2023 |
| ASUSTek       | X551CA                      | [08ce611291](https://linux-hardware.org/?probe=08ce611291) | Dec 02, 2023 |
| Acer          | Aspire 7738                 | [f41b4f3bd4](https://linux-hardware.org/?probe=f41b4f3bd4) | Dec 02, 2023 |
| Acer          | Aspire 7738                 | [fc1e5f26f3](https://linux-hardware.org/?probe=fc1e5f26f3) | Dec 02, 2023 |
| HP            | Pavilion dv6                | [6c2a58400d](https://linux-hardware.org/?probe=6c2a58400d) | Dec 01, 2023 |
| HP            | Pavilion dv6                | [6ee138ba11](https://linux-hardware.org/?probe=6ee138ba11) | Dec 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [71ecd72ded](https://linux-hardware.org/?probe=71ecd72ded) | Dec 01, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [dd5b07ee50](https://linux-hardware.org/?probe=dd5b07ee50) | Dec 01, 2023 |
| Acer          | Aspire 5750ZG               | [6578e9c195](https://linux-hardware.org/?probe=6578e9c195) | Dec 01, 2023 |
| Acer          | Nitro AN515-51              | [116d65dc76](https://linux-hardware.org/?probe=116d65dc76) | Dec 01, 2023 |
| HP            | ProBook 650 G2              | [ce6f82a6b0](https://linux-hardware.org/?probe=ce6f82a6b0) | Nov 30, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [ff4348f86f](https://linux-hardware.org/?probe=ff4348f86f) | Nov 30, 2023 |
| HP            | 620                         | [3b69da88c5](https://linux-hardware.org/?probe=3b69da88c5) | Nov 30, 2023 |
| Lenovo        | G550 20023                  | [dab859b1f5](https://linux-hardware.org/?probe=dab859b1f5) | Nov 30, 2023 |
| Lenovo        | G550 20023                  | [6115cb75f9](https://linux-hardware.org/?probe=6115cb75f9) | Nov 30, 2023 |
| ASUSTek       | K54HR                       | [ca91d466bf](https://linux-hardware.org/?probe=ca91d466bf) | Nov 29, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [f2b1e6e4a9](https://linux-hardware.org/?probe=f2b1e6e4a9) | Nov 28, 2023 |
| Dell          | Latitude 7390               | [4cacd41fee](https://linux-hardware.org/?probe=4cacd41fee) | Nov 28, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | [ce03712596](https://linux-hardware.org/?probe=ce03712596) | Nov 28, 2023 |
| AWOW          | AK41                        | [34d9bc9a34](https://linux-hardware.org/?probe=34d9bc9a34) | Nov 28, 2023 |
| AWOW          | AK41                        | [17f3a70619](https://linux-hardware.org/?probe=17f3a70619) | Nov 28, 2023 |
| HP            | Presario CQ57               | [d8178138ad](https://linux-hardware.org/?probe=d8178138ad) | Nov 28, 2023 |
| ASUSTek       | K54HR                       | [d75b3fd958](https://linux-hardware.org/?probe=d75b3fd958) | Nov 28, 2023 |
| HP            | 250 G1                      | [01e4d8a87b](https://linux-hardware.org/?probe=01e4d8a87b) | Nov 28, 2023 |
| Fujitsu       | LIFEBOOK A555               | [988c87ee59](https://linux-hardware.org/?probe=988c87ee59) | Nov 28, 2023 |
| eMachines     | E725                        | [5035b9380f](https://linux-hardware.org/?probe=5035b9380f) | Nov 28, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [ee62c7d97a](https://linux-hardware.org/?probe=ee62c7d97a) | Nov 28, 2023 |
| Dell          | Inspiron 5567               | [b67bf4064d](https://linux-hardware.org/?probe=b67bf4064d) | Nov 28, 2023 |
| HP            | 620                         | [80b7a22522](https://linux-hardware.org/?probe=80b7a22522) | Nov 28, 2023 |
| MSI           | GP75 Leopard 9SE            | [60c7835d8c](https://linux-hardware.org/?probe=60c7835d8c) | Nov 27, 2023 |
| Acer          | TravelMate P215-52          | [ada0d60fb5](https://linux-hardware.org/?probe=ada0d60fb5) | Nov 27, 2023 |
| Acer          | Aspire A114-31              | [43921895ea](https://linux-hardware.org/?probe=43921895ea) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [f6574b2aaa](https://linux-hardware.org/?probe=f6574b2aaa) | Nov 27, 2023 |
| HP            | 250 G1                      | [16a3ccd98e](https://linux-hardware.org/?probe=16a3ccd98e) | Nov 27, 2023 |
| Apple         | MacBookAir5,2               | [d828fc6b62](https://linux-hardware.org/?probe=d828fc6b62) | Nov 27, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [a83678b03b](https://linux-hardware.org/?probe=a83678b03b) | Nov 27, 2023 |
| eMachines     | E725                        | [fd646483cd](https://linux-hardware.org/?probe=fd646483cd) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [bb7da237ac](https://linux-hardware.org/?probe=bb7da237ac) | Nov 26, 2023 |
| Dell          | Latitude E7240              | [0da1cb9f68](https://linux-hardware.org/?probe=0da1cb9f68) | Nov 26, 2023 |
| HP            | 250 G1                      | [1d14f29955](https://linux-hardware.org/?probe=1d14f29955) | Nov 26, 2023 |
| Dell          | Latitude 5480               | [748c349ec3](https://linux-hardware.org/?probe=748c349ec3) | Nov 26, 2023 |
| HP            | EliteBook 8570w             | [4ded3f7409](https://linux-hardware.org/?probe=4ded3f7409) | Nov 26, 2023 |
| Dell          | Latitude 7390               | [b68d99c176](https://linux-hardware.org/?probe=b68d99c176) | Nov 26, 2023 |
| ASUSTek       | X55U                        | [ba9269363a](https://linux-hardware.org/?probe=ba9269363a) | Nov 26, 2023 |
| MSI           | GT60 2OC/2OD                | [11086675c9](https://linux-hardware.org/?probe=11086675c9) | Nov 26, 2023 |
| HP            | 650                         | [00a115705f](https://linux-hardware.org/?probe=00a115705f) | Nov 26, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [efa6660bf5](https://linux-hardware.org/?probe=efa6660bf5) | Nov 25, 2023 |
| ASUSTek       | X55U                        | [02daf65c45](https://linux-hardware.org/?probe=02daf65c45) | Nov 24, 2023 |
| Dell          | Latitude E6220              | [c252669c37](https://linux-hardware.org/?probe=c252669c37) | Nov 24, 2023 |
| Lenovo        | Flex 2-15D 20377            | [668dae74ed](https://linux-hardware.org/?probe=668dae74ed) | Nov 24, 2023 |
| Samsung       | RV415/RV515/E3415           | [c66c77566e](https://linux-hardware.org/?probe=c66c77566e) | Nov 24, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [73f8815e36](https://linux-hardware.org/?probe=73f8815e36) | Nov 24, 2023 |
| Sony          | SVS13118GBB                 | [2eb3722ea1](https://linux-hardware.org/?probe=2eb3722ea1) | Nov 24, 2023 |
| Sony          | SVS13118GBB                 | [65ac45c622](https://linux-hardware.org/?probe=65ac45c622) | Nov 24, 2023 |
| HP            | Notebook                    | [a4488a0c34](https://linux-hardware.org/?probe=a4488a0c34) | Nov 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [fd89a2eed5](https://linux-hardware.org/?probe=fd89a2eed5) | Nov 23, 2023 |
| Dell          | Latitude E5520              | [603704ca41](https://linux-hardware.org/?probe=603704ca41) | Nov 23, 2023 |
| HP            | Presario CQ57               | [1aaa046b20](https://linux-hardware.org/?probe=1aaa046b20) | Nov 22, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [ce2d61136c](https://linux-hardware.org/?probe=ce2d61136c) | Nov 22, 2023 |
| Dell          | Inspiron 7737               | [c5551bb38d](https://linux-hardware.org/?probe=c5551bb38d) | Nov 22, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [feccf655c5](https://linux-hardware.org/?probe=feccf655c5) | Nov 21, 2023 |
| Lenovo        | G50-45 80E3                 | [7f6fbb3c44](https://linux-hardware.org/?probe=7f6fbb3c44) | Nov 21, 2023 |
| Lenovo        | G50-45 80E3                 | [497645938f](https://linux-hardware.org/?probe=497645938f) | Nov 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [91a346655b](https://linux-hardware.org/?probe=91a346655b) | Nov 21, 2023 |
| Samsung       | RV415/RV515/E3415           | [7920ff517f](https://linux-hardware.org/?probe=7920ff517f) | Nov 20, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [6269fd26e0](https://linux-hardware.org/?probe=6269fd26e0) | Nov 20, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [6a2ddf8e53](https://linux-hardware.org/?probe=6a2ddf8e53) | Nov 19, 2023 |
| Dell          | Inspiron 3542               | [488ac4cac6](https://linux-hardware.org/?probe=488ac4cac6) | Nov 18, 2023 |
| Dell          | Inspiron 3542               | [cbdd99c4fc](https://linux-hardware.org/?probe=cbdd99c4fc) | Nov 18, 2023 |
| Dell          | Latitude E6230              | [230d462f11](https://linux-hardware.org/?probe=230d462f11) | Nov 17, 2023 |
| Dell          | Latitude E6230              | [0e87890c4c](https://linux-hardware.org/?probe=0e87890c4c) | Nov 17, 2023 |
| HP            | EliteBook 8570w             | [2c22b9f725](https://linux-hardware.org/?probe=2c22b9f725) | Nov 16, 2023 |
| MSI           | GT60 2OC/2OD                | [a29bea944f](https://linux-hardware.org/?probe=a29bea944f) | Nov 16, 2023 |
| MSI           | GT60 2OC/2OD                | [3648bc5b55](https://linux-hardware.org/?probe=3648bc5b55) | Nov 16, 2023 |
| HP            | EliteBook 8570w             | [4b06d87b96](https://linux-hardware.org/?probe=4b06d87b96) | Nov 15, 2023 |
| AWOW          | AK41                        | [5d9f671218](https://linux-hardware.org/?probe=5d9f671218) | Nov 14, 2023 |
| AWOW          | AK41                        | [89e2926ff6](https://linux-hardware.org/?probe=89e2926ff6) | Nov 14, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [55665c76e2](https://linux-hardware.org/?probe=55665c76e2) | Nov 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [39186e5754](https://linux-hardware.org/?probe=39186e5754) | Nov 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [22c504ad97](https://linux-hardware.org/?probe=22c504ad97) | Nov 13, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [aa66857d17](https://linux-hardware.org/?probe=aa66857d17) | Nov 13, 2023 |
| Fujitsu       | LIFEBOOK E744               | [2f9f860b8f](https://linux-hardware.org/?probe=2f9f860b8f) | Nov 12, 2023 |
| Dell          | Inspiron 5558               | [84d60633b1](https://linux-hardware.org/?probe=84d60633b1) | Nov 12, 2023 |
| Dell          | Inspiron 5558               | [bf78e4de12](https://linux-hardware.org/?probe=bf78e4de12) | Nov 12, 2023 |
| Dell          | Latitude E6520              | [4d1bb1f947](https://linux-hardware.org/?probe=4d1bb1f947) | Nov 11, 2023 |
| Dell          | Latitude E6520              | [ecbec01a36](https://linux-hardware.org/?probe=ecbec01a36) | Nov 11, 2023 |
| Fujitsu       | LIFEBOOK E744               | [85c42caa7f](https://linux-hardware.org/?probe=85c42caa7f) | Nov 11, 2023 |
| Dell          | Vostro 3500                 | [6de94ed555](https://linux-hardware.org/?probe=6de94ed555) | Nov 11, 2023 |
| HP            | ProBook 650 G2              | [c4fc402545](https://linux-hardware.org/?probe=c4fc402545) | Nov 11, 2023 |
| HP            | ProBook 650 G2              | [0523c4d3fd](https://linux-hardware.org/?probe=0523c4d3fd) | Nov 11, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [a1ba3b47c2](https://linux-hardware.org/?probe=a1ba3b47c2) | Nov 10, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [b6ce2c01d3](https://linux-hardware.org/?probe=b6ce2c01d3) | Nov 10, 2023 |
| Acer          | Nitro AN515-51              | [8dda111b6a](https://linux-hardware.org/?probe=8dda111b6a) | Nov 09, 2023 |
| Medion        | E7220                       | [2a13846d8f](https://linux-hardware.org/?probe=2a13846d8f) | Nov 09, 2023 |
| Medion        | E7220                       | [f0e0b97ea6](https://linux-hardware.org/?probe=f0e0b97ea6) | Nov 08, 2023 |
| Dell          | Latitude D520               | [de71d8ccf8](https://linux-hardware.org/?probe=de71d8ccf8) | Nov 08, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [4eb5901f8c](https://linux-hardware.org/?probe=4eb5901f8c) | Nov 08, 2023 |
| Dell          | Latitude D520               | [5beff5a82d](https://linux-hardware.org/?probe=5beff5a82d) | Nov 08, 2023 |
| Lenovo        | V15-ADA 82C7                | [eecf9896e7](https://linux-hardware.org/?probe=eecf9896e7) | Nov 07, 2023 |
| Acer          | Aspire 7738                 | [06df3c94e1](https://linux-hardware.org/?probe=06df3c94e1) | Nov 07, 2023 |
| HP            | HDX 16                      | [faeb7886e4](https://linux-hardware.org/?probe=faeb7886e4) | Nov 07, 2023 |
| HP            | HDX 16                      | [321b191f5f](https://linux-hardware.org/?probe=321b191f5f) | Nov 07, 2023 |
| Lenovo        | G50-45 80E3                 | [518823b9dc](https://linux-hardware.org/?probe=518823b9dc) | Nov 07, 2023 |
| Lenovo        | G50-45 80E3                 | [a9978280c9](https://linux-hardware.org/?probe=a9978280c9) | Nov 07, 2023 |
| Dell          | Vostro 1015                 | [c4d9d2cd13](https://linux-hardware.org/?probe=c4d9d2cd13) | Nov 06, 2023 |
| Dell          | Latitude E6410              | [ebdd852a85](https://linux-hardware.org/?probe=ebdd852a85) | Nov 05, 2023 |
| Dell          | Latitude D520               | [99c85f2153](https://linux-hardware.org/?probe=99c85f2153) | Nov 05, 2023 |
| Dell          | Latitude D520               | [d56819f452](https://linux-hardware.org/?probe=d56819f452) | Nov 05, 2023 |
| HP            | 650                         | [5b72d0e471](https://linux-hardware.org/?probe=5b72d0e471) | Nov 05, 2023 |
| Medion        | E7220                       | [a8643a8082](https://linux-hardware.org/?probe=a8643a8082) | Nov 05, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [b1c2db4297](https://linux-hardware.org/?probe=b1c2db4297) | Nov 05, 2023 |
| Medion        | E7220                       | [f093abab73](https://linux-hardware.org/?probe=f093abab73) | Nov 05, 2023 |
| HP            | Pavilion dv5                | [6a122b29a9](https://linux-hardware.org/?probe=6a122b29a9) | Nov 05, 2023 |
| Dell          | Vostro 3500                 | [08d79042a7](https://linux-hardware.org/?probe=08d79042a7) | Nov 04, 2023 |
| HP            | 650                         | [c472e54502](https://linux-hardware.org/?probe=c472e54502) | Nov 04, 2023 |
| ASUSTek       | K53U                        | [eb44961984](https://linux-hardware.org/?probe=eb44961984) | Nov 04, 2023 |
| Dell          | Inspiron 3542               | [f36f4e888c](https://linux-hardware.org/?probe=f36f4e888c) | Nov 04, 2023 |
| HP            | Pavilion dv6                | [bf6361ff84](https://linux-hardware.org/?probe=bf6361ff84) | Nov 03, 2023 |
| HP            | EliteBook Folio 9480m       | [3d5b8068af](https://linux-hardware.org/?probe=3d5b8068af) | Nov 01, 2023 |
| HP            | EliteBook Folio 9480m       | [135443bd2d](https://linux-hardware.org/?probe=135443bd2d) | Nov 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [f8a1a5a5fa](https://linux-hardware.org/?probe=f8a1a5a5fa) | Nov 01, 2023 |
| Dell          | Inspiron 5558               | [a6c79e3211](https://linux-hardware.org/?probe=a6c79e3211) | Oct 31, 2023 |
| Dell          | Inspiron 5558               | [2327e785db](https://linux-hardware.org/?probe=2327e785db) | Oct 31, 2023 |
| Fujitsu Si... | AMILO Si 2636               | [bc3acc8006](https://linux-hardware.org/?probe=bc3acc8006) | Oct 30, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [abd35a7e37](https://linux-hardware.org/?probe=abd35a7e37) | Oct 30, 2023 |
| AWOW          | AK41                        | [bed4203da6](https://linux-hardware.org/?probe=bed4203da6) | Oct 30, 2023 |
| HP            | Notebook                    | [dae22f458b](https://linux-hardware.org/?probe=dae22f458b) | Oct 30, 2023 |
| HP            | Notebook                    | [373777c65a](https://linux-hardware.org/?probe=373777c65a) | Oct 30, 2023 |
| Dell          | Inspiron 1545               | [9902963d1d](https://linux-hardware.org/?probe=9902963d1d) | Oct 29, 2023 |
| Dell          | Inspiron 1545               | [39c5db1614](https://linux-hardware.org/?probe=39c5db1614) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | [1a14a8f0c4](https://linux-hardware.org/?probe=1a14a8f0c4) | Oct 29, 2023 |
| ASUSTek       | X551CA                      | [a43802c314](https://linux-hardware.org/?probe=a43802c314) | Oct 29, 2023 |
| Dell          | Inspiron 15-3573            | [de8470b056](https://linux-hardware.org/?probe=de8470b056) | Oct 29, 2023 |
| ASUSTek       | K54C                        | [d36a0a583b](https://linux-hardware.org/?probe=d36a0a583b) | Oct 29, 2023 |
| Dell          | Inspiron 15-3573            | [db205eed37](https://linux-hardware.org/?probe=db205eed37) | Oct 29, 2023 |
| Dell          | Inspiron 3521               | [67aa25e9ff](https://linux-hardware.org/?probe=67aa25e9ff) | Oct 28, 2023 |
| Dell          | Inspiron N5010              | [5d60a750af](https://linux-hardware.org/?probe=5d60a750af) | Oct 27, 2023 |
| Dell          | Inspiron N5010              | [6ca7ed2683](https://linux-hardware.org/?probe=6ca7ed2683) | Oct 27, 2023 |
| HP            | HDX 16                      | [e2c3147b80](https://linux-hardware.org/?probe=e2c3147b80) | Oct 27, 2023 |
| HP            | HDX 16                      | [9ec532aa3c](https://linux-hardware.org/?probe=9ec532aa3c) | Oct 27, 2023 |
| Lenovo        | G505 20240                  | [efe15b2600](https://linux-hardware.org/?probe=efe15b2600) | Oct 26, 2023 |
| Lenovo        | G505 20240                  | [9d4b52edfe](https://linux-hardware.org/?probe=9d4b52edfe) | Oct 26, 2023 |
| AWOW          | AK41                        | [e40c573853](https://linux-hardware.org/?probe=e40c573853) | Oct 26, 2023 |
| Lenovo        | G50-30 80G0                 | [5e16db7192](https://linux-hardware.org/?probe=5e16db7192) | Oct 26, 2023 |
| Lenovo        | G50-30 80G0                 | [a2731cd16e](https://linux-hardware.org/?probe=a2731cd16e) | Oct 26, 2023 |
| Fujitsu       | LIFEBOOK A512               | [f6b735de42](https://linux-hardware.org/?probe=f6b735de42) | Oct 25, 2023 |
| ASUSTek       | 1015BX                      | [676f3b81ce](https://linux-hardware.org/?probe=676f3b81ce) | Oct 25, 2023 |
| Lenovo        | G505s 20255                 | [4bc0dc73b1](https://linux-hardware.org/?probe=4bc0dc73b1) | Oct 25, 2023 |
| Fujitsu       | LIFEBOOK A512               | [3deed5f633](https://linux-hardware.org/?probe=3deed5f633) | Oct 24, 2023 |
| Acer          | TravelMate P215-52          | [b834df3a83](https://linux-hardware.org/?probe=b834df3a83) | Oct 23, 2023 |
| Acer          | TravelMate P215-52          | [a62011100d](https://linux-hardware.org/?probe=a62011100d) | Oct 23, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [86dc35496a](https://linux-hardware.org/?probe=86dc35496a) | Oct 23, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [2ae3b33ae8](https://linux-hardware.org/?probe=2ae3b33ae8) | Oct 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [5f54128707](https://linux-hardware.org/?probe=5f54128707) | Oct 22, 2023 |
| Dell          | Latitude E6540              | [5249645843](https://linux-hardware.org/?probe=5249645843) | Oct 22, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [e681e567ad](https://linux-hardware.org/?probe=e681e567ad) | Oct 22, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | [6e43e8e97a](https://linux-hardware.org/?probe=6e43e8e97a) | Oct 20, 2023 |
| Lenovo        | ThinkPad X230 2333A91       | [1ba3f61a85](https://linux-hardware.org/?probe=1ba3f61a85) | Oct 20, 2023 |
| Lenovo        | E50-80 80J2                 | [539584b79f](https://linux-hardware.org/?probe=539584b79f) | Oct 20, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [ba440cffa8](https://linux-hardware.org/?probe=ba440cffa8) | Oct 20, 2023 |
| Fujitsu       | LIFEBOOK A512               | [91503bb9a7](https://linux-hardware.org/?probe=91503bb9a7) | Oct 19, 2023 |
| Fujitsu       | LIFEBOOK A512               | [74d8675dfc](https://linux-hardware.org/?probe=74d8675dfc) | Oct 19, 2023 |
| Sony          | VPCS13V9E                   | [af74c8aeff](https://linux-hardware.org/?probe=af74c8aeff) | Oct 19, 2023 |
| Dell          | Latitude E6230              | [6b95eceb6d](https://linux-hardware.org/?probe=6b95eceb6d) | Oct 18, 2023 |
| Dell          | Latitude E6230              | [80ef815864](https://linux-hardware.org/?probe=80ef815864) | Oct 18, 2023 |
| Fujitsu       | LIFEBOOK A555               | [6495c7be9b](https://linux-hardware.org/?probe=6495c7be9b) | Oct 18, 2023 |
| Lenovo        | V15-ADA 82C7                | [9cf2098fd0](https://linux-hardware.org/?probe=9cf2098fd0) | Oct 17, 2023 |
| HP            | Notebook                    | [62bc59c216](https://linux-hardware.org/?probe=62bc59c216) | Oct 17, 2023 |
| HP            | Notebook                    | [4ee408f659](https://linux-hardware.org/?probe=4ee408f659) | Oct 17, 2023 |
| Lenovo        | ThinkPad T61 889855G        | [d2cf744079](https://linux-hardware.org/?probe=d2cf744079) | Oct 17, 2023 |
| Dell          | Inspiron 7737               | [4f8ecd431c](https://linux-hardware.org/?probe=4f8ecd431c) | Oct 17, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [67ad226870](https://linux-hardware.org/?probe=67ad226870) | Oct 17, 2023 |
| Acer          | Aspire ES1-571              | [031455773c](https://linux-hardware.org/?probe=031455773c) | Oct 14, 2023 |
| Acer          | Aspire 5750ZG               | [23a48d0873](https://linux-hardware.org/?probe=23a48d0873) | Oct 13, 2023 |
| Acer          | Aspire 5750ZG               | [da6b006c58](https://linux-hardware.org/?probe=da6b006c58) | Oct 13, 2023 |
| Dell          | Vostro 3500                 | [7af22eb528](https://linux-hardware.org/?probe=7af22eb528) | Oct 12, 2023 |
| ASUSTek       | X55U                        | [82866b3b8b](https://linux-hardware.org/?probe=82866b3b8b) | Oct 11, 2023 |
| Lenovo        | ThinkPad T420 4236B87       | [55e5cd7abc](https://linux-hardware.org/?probe=55e5cd7abc) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | [1d1d1e17eb](https://linux-hardware.org/?probe=1d1d1e17eb) | Oct 11, 2023 |
| MSI           | GT60 2OC/2OD                | [12d88836d5](https://linux-hardware.org/?probe=12d88836d5) | Oct 11, 2023 |
| eMachines     | E725                        | [1efc1e7a3a](https://linux-hardware.org/?probe=1efc1e7a3a) | Oct 10, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [602dbf9ee0](https://linux-hardware.org/?probe=602dbf9ee0) | Oct 10, 2023 |
| ASUSTek       | X200MA                      | [731177232b](https://linux-hardware.org/?probe=731177232b) | Oct 09, 2023 |
| ASUSTek       | K51AE                       | [9c3d05354e](https://linux-hardware.org/?probe=9c3d05354e) | Oct 09, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [d3bd6d1c84](https://linux-hardware.org/?probe=d3bd6d1c84) | Oct 08, 2023 |
| Lenovo        | IdeaPad 110-15ISK 80UD      | [af810081c9](https://linux-hardware.org/?probe=af810081c9) | Oct 08, 2023 |
| eMachines     | E525                        | [4eb2312418](https://linux-hardware.org/?probe=4eb2312418) | Oct 08, 2023 |
| Dell          | Latitude 7390               | [6204f328e3](https://linux-hardware.org/?probe=6204f328e3) | Oct 05, 2023 |
| Sony          | VPCEH2N1E                   | [b983141e0f](https://linux-hardware.org/?probe=b983141e0f) | Oct 03, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [aefdc00927](https://linux-hardware.org/?probe=aefdc00927) | Oct 03, 2023 |
| HP            | ProBook 6570b               | [77a44e0363](https://linux-hardware.org/?probe=77a44e0363) | Oct 03, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [8cc4ccdbec](https://linux-hardware.org/?probe=8cc4ccdbec) | Oct 01, 2023 |
| ASUSTek       | X55U                        | [029b7ab708](https://linux-hardware.org/?probe=029b7ab708) | Oct 01, 2023 |
| Lenovo        | Flex 2-15D 20377            | [8f9e71f454](https://linux-hardware.org/?probe=8f9e71f454) | Oct 01, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [4567599161](https://linux-hardware.org/?probe=4567599161) | Sep 29, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [526458167b](https://linux-hardware.org/?probe=526458167b) | Sep 29, 2023 |
| Dell          | Inspiron 5559               | [ea6622fcde](https://linux-hardware.org/?probe=ea6622fcde) | Sep 28, 2023 |
| Dell          | Inspiron 5559               | [a7e3c38a52](https://linux-hardware.org/?probe=a7e3c38a52) | Sep 28, 2023 |
| eMachines     | E725                        | [2c76723d59](https://linux-hardware.org/?probe=2c76723d59) | Sep 28, 2023 |
| HP            | 250 G1                      | [0ec87fea6c](https://linux-hardware.org/?probe=0ec87fea6c) | Sep 27, 2023 |
| Dell          | Inspiron 5558               | [e8577ce363](https://linux-hardware.org/?probe=e8577ce363) | Sep 27, 2023 |
| ASUSTek       | X551CA                      | [1fdceb9309](https://linux-hardware.org/?probe=1fdceb9309) | Sep 26, 2023 |
| HP            | 250 G1                      | [1aa0ca441a](https://linux-hardware.org/?probe=1aa0ca441a) | Sep 25, 2023 |
| ASUSTek       | X550CL                      | [9a2c66690c](https://linux-hardware.org/?probe=9a2c66690c) | Sep 25, 2023 |
| Apple         | MacBookAir5,2               | [137fbb8afb](https://linux-hardware.org/?probe=137fbb8afb) | Sep 25, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [fcdc931f2b](https://linux-hardware.org/?probe=fcdc931f2b) | Sep 24, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [2d441ed803](https://linux-hardware.org/?probe=2d441ed803) | Sep 24, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [0c9651a144](https://linux-hardware.org/?probe=0c9651a144) | Sep 24, 2023 |
| HP            | Notebook                    | [b222ca41de](https://linux-hardware.org/?probe=b222ca41de) | Sep 24, 2023 |
| Lenovo        | ThinkPad T400 2768WGB       | [b4a2e6cb0a](https://linux-hardware.org/?probe=b4a2e6cb0a) | Sep 24, 2023 |
| Dell          | Inspiron 5558               | [22a7b0cc9c](https://linux-hardware.org/?probe=22a7b0cc9c) | Sep 24, 2023 |
| Sony          | VPCEH2J1E                   | [2a09805fe9](https://linux-hardware.org/?probe=2a09805fe9) | Sep 24, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [8d4bdbafa8](https://linux-hardware.org/?probe=8d4bdbafa8) | Sep 23, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [083c0510ac](https://linux-hardware.org/?probe=083c0510ac) | Sep 23, 2023 |
| HP            | Compaq 6710b (KE121EA#AK... | [a5b9ab6a07](https://linux-hardware.org/?probe=a5b9ab6a07) | Sep 23, 2023 |
| HP            | 650                         | [3c45902b7c](https://linux-hardware.org/?probe=3c45902b7c) | Sep 23, 2023 |
| Dell          | Latitude 7390               | [1aab1b313f](https://linux-hardware.org/?probe=1aab1b313f) | Sep 22, 2023 |
| HP            | 250 G1                      | [44dde35a76](https://linux-hardware.org/?probe=44dde35a76) | Sep 22, 2023 |
| Dell          | Latitude E5520              | [ae034f7a6b](https://linux-hardware.org/?probe=ae034f7a6b) | Sep 22, 2023 |
| HP            | Laptop 15-dw1xxx            | [18581b1af5](https://linux-hardware.org/?probe=18581b1af5) | Sep 22, 2023 |
| Acer          | Aspire A114-31              | [968cd24afa](https://linux-hardware.org/?probe=968cd24afa) | Sep 22, 2023 |
| Acer          | Aspire E5-575G              | [bb5eff384a](https://linux-hardware.org/?probe=bb5eff384a) | Sep 22, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [942f5325d2](https://linux-hardware.org/?probe=942f5325d2) | Sep 22, 2023 |
| MSI           | GT60 2OC/2OD                | [0b5a8a95dc](https://linux-hardware.org/?probe=0b5a8a95dc) | Sep 22, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [c71bb49dcd](https://linux-hardware.org/?probe=c71bb49dcd) | Sep 21, 2023 |
| Dell          | Inspiron 5567               | [25e14aaf2b](https://linux-hardware.org/?probe=25e14aaf2b) | Sep 21, 2023 |
| Dell          | Latitude E7240              | [3e8e36e3ea](https://linux-hardware.org/?probe=3e8e36e3ea) | Sep 21, 2023 |
| ASUSTek       | K54HR                       | [8552d31b3c](https://linux-hardware.org/?probe=8552d31b3c) | Sep 21, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [32e2046699](https://linux-hardware.org/?probe=32e2046699) | Sep 21, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [22733fb7ba](https://linux-hardware.org/?probe=22733fb7ba) | Sep 21, 2023 |
| MSI           | GP75 Leopard 9SE            | [07431109a7](https://linux-hardware.org/?probe=07431109a7) | Sep 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [ed4753b8e2](https://linux-hardware.org/?probe=ed4753b8e2) | Sep 21, 2023 |
| Dell          | Latitude E6220              | [dd26ec3c45](https://linux-hardware.org/?probe=dd26ec3c45) | Sep 21, 2023 |
| Dell          | Inspiron 15-3567            | [cff5fbdefd](https://linux-hardware.org/?probe=cff5fbdefd) | Sep 21, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [9f1f1562ed](https://linux-hardware.org/?probe=9f1f1562ed) | Sep 21, 2023 |
| HP            | ProBook 650 G2              | [215bdc7f1c](https://linux-hardware.org/?probe=215bdc7f1c) | Sep 20, 2023 |
| Fujitsu Si... | AMILO Li3910                | [14714d058e](https://linux-hardware.org/?probe=14714d058e) | Sep 19, 2023 |
| HP            | 650                         | [f648ca59f3](https://linux-hardware.org/?probe=f648ca59f3) | Sep 16, 2023 |
| Dell          | Latitude 7390               | [c2529c08a4](https://linux-hardware.org/?probe=c2529c08a4) | Sep 14, 2023 |
| HP            | 250 G1                      | [05483d5695](https://linux-hardware.org/?probe=05483d5695) | Sep 14, 2023 |
| Insyde        | Braswell                    | [1fb0864056](https://linux-hardware.org/?probe=1fb0864056) | Sep 14, 2023 |
| HP            | ProBook 650 G2              | [654bee8844](https://linux-hardware.org/?probe=654bee8844) | Sep 14, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [8dba4d978a](https://linux-hardware.org/?probe=8dba4d978a) | Sep 13, 2023 |
| Dell          | Latitude E6220              | [f34fd65819](https://linux-hardware.org/?probe=f34fd65819) | Sep 12, 2023 |
| Dell          | Inspiron 5558               | [ec4efd4d4d](https://linux-hardware.org/?probe=ec4efd4d4d) | Sep 11, 2023 |
| Dell          | Inspiron 15-3567            | [933a72acff](https://linux-hardware.org/?probe=933a72acff) | Sep 10, 2023 |
| HP            | Notebook                    | [231eb17318](https://linux-hardware.org/?probe=231eb17318) | Sep 10, 2023 |
| Dell          | Vostro 1015                 | [06e4b83617](https://linux-hardware.org/?probe=06e4b83617) | Sep 09, 2023 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [a03aa3f52d](https://linux-hardware.org/?probe=a03aa3f52d) | Sep 09, 2023 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [7f678086c3](https://linux-hardware.org/?probe=7f678086c3) | Sep 08, 2023 |
| ASUSTek       | X200MA                      | [77bd4e57e6](https://linux-hardware.org/?probe=77bd4e57e6) | Sep 08, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [d0f37c70e7](https://linux-hardware.org/?probe=d0f37c70e7) | Sep 08, 2023 |
| Gateway       | NE56R                       | [ec2415b16d](https://linux-hardware.org/?probe=ec2415b16d) | Sep 08, 2023 |
| Gateway       | NE56R                       | [4871fca687](https://linux-hardware.org/?probe=4871fca687) | Sep 08, 2023 |
| Lenovo        | ThinkPad T540p 20BE003YU... | [2614f063f8](https://linux-hardware.org/?probe=2614f063f8) | Sep 07, 2023 |
| Dell          | Vostro 1015                 | [9c672d2801](https://linux-hardware.org/?probe=9c672d2801) | Sep 07, 2023 |
| Dell          | Latitude E6540              | [2832b1dd0d](https://linux-hardware.org/?probe=2832b1dd0d) | Sep 06, 2023 |
| ASUSTek       | X200MA                      | [e5a99beac7](https://linux-hardware.org/?probe=e5a99beac7) | Sep 06, 2023 |
| Gateway       | NE56R                       | [ade8432ca6](https://linux-hardware.org/?probe=ade8432ca6) | Sep 06, 2023 |
| Dell          | Latitude 7390               | [4d913a8444](https://linux-hardware.org/?probe=4d913a8444) | Sep 05, 2023 |
| Dell          | Inspiron 15-3567            | [2fe06014b3](https://linux-hardware.org/?probe=2fe06014b3) | Sep 05, 2023 |
| Dell          | Latitude 7390               | [2c6e7f955b](https://linux-hardware.org/?probe=2c6e7f955b) | Sep 05, 2023 |
| HP            | Notebook                    | [76a4d54b3b](https://linux-hardware.org/?probe=76a4d54b3b) | Sep 04, 2023 |
| Gateway       | NE56R                       | [99b1c83e93](https://linux-hardware.org/?probe=99b1c83e93) | Sep 04, 2023 |
| Dell          | Latitude 7390               | [cdee70b142](https://linux-hardware.org/?probe=cdee70b142) | Sep 04, 2023 |
| HP            | Laptop 15-dw1xxx            | [435d20add8](https://linux-hardware.org/?probe=435d20add8) | Sep 04, 2023 |
| eMachines     | E725                        | [cb1c5bd673](https://linux-hardware.org/?probe=cb1c5bd673) | Sep 03, 2023 |
| HP            | Pavilion dv6                | [cf6a67d073](https://linux-hardware.org/?probe=cf6a67d073) | Sep 03, 2023 |
| Lenovo        | Flex 2-15D 20377            | [88c1e6be3b](https://linux-hardware.org/?probe=88c1e6be3b) | Sep 03, 2023 |
| HP            | Pavilion x2 Detachable      | [c98b2d5aba](https://linux-hardware.org/?probe=c98b2d5aba) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [90fb74ac63](https://linux-hardware.org/?probe=90fb74ac63) | Sep 03, 2023 |
| Lenovo        | Flex 2-15D 20377            | [7b0445b6d8](https://linux-hardware.org/?probe=7b0445b6d8) | Sep 03, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [3e196c9509](https://linux-hardware.org/?probe=3e196c9509) | Sep 03, 2023 |
| Dell          | Inspiron 5558               | [87cb36af8d](https://linux-hardware.org/?probe=87cb36af8d) | Sep 03, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [4764776393](https://linux-hardware.org/?probe=4764776393) | Sep 02, 2023 |
| Dell          | Inspiron 7737               | [c1ad093dbb](https://linux-hardware.org/?probe=c1ad093dbb) | Sep 02, 2023 |
| HP            | ProBook 650 G2              | [a00c4f0a62](https://linux-hardware.org/?probe=a00c4f0a62) | Sep 02, 2023 |
| HP            | 250 G5 Notebook PC          | [75ad357b16](https://linux-hardware.org/?probe=75ad357b16) | Sep 01, 2023 |
| ASUSTek       | X550CL                      | [e1eb9c4b56](https://linux-hardware.org/?probe=e1eb9c4b56) | Sep 01, 2023 |
| Sony          | VPCEH2J1E                   | [0d1017e65a](https://linux-hardware.org/?probe=0d1017e65a) | Aug 31, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | [458b3b6310](https://linux-hardware.org/?probe=458b3b6310) | Aug 31, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [4d1e47297b](https://linux-hardware.org/?probe=4d1e47297b) | Aug 30, 2023 |
| Dell          | Inspiron 5567               | [0eddf6dfcd](https://linux-hardware.org/?probe=0eddf6dfcd) | Aug 30, 2023 |
| Dell          | Latitude E7240              | [ba4d78320f](https://linux-hardware.org/?probe=ba4d78320f) | Aug 30, 2023 |
| Apple         | MacBookAir5,2               | [8e595f3214](https://linux-hardware.org/?probe=8e595f3214) | Aug 30, 2023 |
| Acer          | Aspire A114-31              | [6bf92318e7](https://linux-hardware.org/?probe=6bf92318e7) | Aug 30, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [41797b2df4](https://linux-hardware.org/?probe=41797b2df4) | Aug 30, 2023 |
| HP            | 250 G1                      | [6821396f96](https://linux-hardware.org/?probe=6821396f96) | Aug 29, 2023 |
| Lenovo        | G70-35 80Q5                 | [0e3563cf3e](https://linux-hardware.org/?probe=0e3563cf3e) | Aug 29, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [0f7047f2c2](https://linux-hardware.org/?probe=0f7047f2c2) | Aug 29, 2023 |
| Acer          | Aspire E5-575G              | [9c733aac9d](https://linux-hardware.org/?probe=9c733aac9d) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [9f725ce1a7](https://linux-hardware.org/?probe=9f725ce1a7) | Aug 28, 2023 |
| Apple         | MacBookPro5,1               | [62464b6b0d](https://linux-hardware.org/?probe=62464b6b0d) | Aug 28, 2023 |
| Sony          | VPCEH2N1E                   | [a3e59b2f83](https://linux-hardware.org/?probe=a3e59b2f83) | Aug 28, 2023 |
| Toshiba       | Satellite C55D-A-14W        | [c091e0bc8b](https://linux-hardware.org/?probe=c091e0bc8b) | Aug 28, 2023 |
| Apple         | MacBookAir5,2               | [635743c7d4](https://linux-hardware.org/?probe=635743c7d4) | Aug 28, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [cb57dd666e](https://linux-hardware.org/?probe=cb57dd666e) | Aug 28, 2023 |
| MSI           | GP75 Leopard 9SE            | [a8a97f9555](https://linux-hardware.org/?probe=a8a97f9555) | Aug 27, 2023 |
| eMachines     | E725                        | [415b4166b9](https://linux-hardware.org/?probe=415b4166b9) | Aug 27, 2023 |
| eMachines     | E725                        | [edb02e1501](https://linux-hardware.org/?probe=edb02e1501) | Aug 27, 2023 |
| ASUSTek       | K54HR                       | [28217feff7](https://linux-hardware.org/?probe=28217feff7) | Aug 27, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [7f67a243d7](https://linux-hardware.org/?probe=7f67a243d7) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | [3f742c8393](https://linux-hardware.org/?probe=3f742c8393) | Aug 27, 2023 |
| HP            | Compaq 6730b (NB025EA#AB... | [3b462ade1a](https://linux-hardware.org/?probe=3b462ade1a) | Aug 27, 2023 |
| HP            | 250 G1                      | [27baf9b755](https://linux-hardware.org/?probe=27baf9b755) | Aug 27, 2023 |
| Acer          | Aspire One 753              | [6070c05860](https://linux-hardware.org/?probe=6070c05860) | Aug 27, 2023 |
| HP            | EliteBook 2540p             | [6641de7018](https://linux-hardware.org/?probe=6641de7018) | Aug 27, 2023 |
| MSI           | GT60 2OC/2OD                | [998ee50b04](https://linux-hardware.org/?probe=998ee50b04) | Aug 27, 2023 |
| HP            | 650                         | [ed399f8cfb](https://linux-hardware.org/?probe=ed399f8cfb) | Aug 27, 2023 |
| Acer          | Aspire One 753              | [f8ae4bfb92](https://linux-hardware.org/?probe=f8ae4bfb92) | Aug 27, 2023 |
| ASUSTek       | X550CL                      | [679808ec60](https://linux-hardware.org/?probe=679808ec60) | Aug 26, 2023 |
| Lenovo        | ThinkPad X250 20CLS1JN00    | [e8e1a3d429](https://linux-hardware.org/?probe=e8e1a3d429) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | [b1fe190515](https://linux-hardware.org/?probe=b1fe190515) | Aug 26, 2023 |
| Lenovo        | ThinkPad T470 20HES58A1L    | [bc1cdf2ce7](https://linux-hardware.org/?probe=bc1cdf2ce7) | Aug 26, 2023 |
| MSI           | GP75 Leopard 9SE            | [db9336b4db](https://linux-hardware.org/?probe=db9336b4db) | Aug 26, 2023 |
| Lenovo        | ThinkPad T410 2537VFQ       | [d8b8b7565b](https://linux-hardware.org/?probe=d8b8b7565b) | Aug 26, 2023 |
| HP            | 250 G1                      | [d2989d3be0](https://linux-hardware.org/?probe=d2989d3be0) | Aug 26, 2023 |
| Dell          | Inspiron 5558               | [8a59de1138](https://linux-hardware.org/?probe=8a59de1138) | Aug 26, 2023 |
| ASUSTek       | K54HR                       | [55da0d1667](https://linux-hardware.org/?probe=55da0d1667) | Aug 26, 2023 |
| Dell          | Latitude E6410              | [20134aee31](https://linux-hardware.org/?probe=20134aee31) | Aug 25, 2023 |
| Lenovo        | G70-35 80Q5                 | [1025de1dcf](https://linux-hardware.org/?probe=1025de1dcf) | Aug 25, 2023 |
| Dell          | Latitude E5520              | [6e27e77275](https://linux-hardware.org/?probe=6e27e77275) | Aug 25, 2023 |
| Fujitsu       | LIFEBOOK A555               | [1dc34b7cc5](https://linux-hardware.org/?probe=1dc34b7cc5) | Aug 25, 2023 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | [7d90deb5b1](https://linux-hardware.org/?probe=7d90deb5b1) | Aug 25, 2023 |
| Dell          | Latitude E6220              | [6afbb8e146](https://linux-hardware.org/?probe=6afbb8e146) | Aug 24, 2023 |
| Dell          | Precision M6600             | [60acc9bcb0](https://linux-hardware.org/?probe=60acc9bcb0) | Aug 23, 2023 |
| MSI           | GT60 2OC/2OD                | [e610051fdc](https://linux-hardware.org/?probe=e610051fdc) | Aug 20, 2023 |
| Dell          | Latitude E6230              | [7888184dd0](https://linux-hardware.org/?probe=7888184dd0) | Aug 19, 2023 |
| Dell          | Latitude E6230              | [1672d92536](https://linux-hardware.org/?probe=1672d92536) | Aug 19, 2023 |
| HP            | Notebook                    | [661cb258ef](https://linux-hardware.org/?probe=661cb258ef) | Aug 19, 2023 |
| Dell          | Precision M6600             | [15df8fbaaf](https://linux-hardware.org/?probe=15df8fbaaf) | Aug 18, 2023 |
| HP            | Pavilion dv6                | [a6d62bc041](https://linux-hardware.org/?probe=a6d62bc041) | Aug 18, 2023 |
| Dell          | Latitude E6410              | [9cc0b91505](https://linux-hardware.org/?probe=9cc0b91505) | Aug 14, 2023 |
| HP            | 250 G5 Notebook PC          | [d5b2c3b80a](https://linux-hardware.org/?probe=d5b2c3b80a) | Aug 14, 2023 |
| HP            | ProBook 650 G2              | [b310a70636](https://linux-hardware.org/?probe=b310a70636) | Aug 14, 2023 |
| Acer          | Extensa 5220                | [92605dd73d](https://linux-hardware.org/?probe=92605dd73d) | Aug 12, 2023 |
| Acer          | Aspire E1-532               | [84cbdf027b](https://linux-hardware.org/?probe=84cbdf027b) | Aug 12, 2023 |
| HP            | ProBook 650 G2              | [8fbbf1483d](https://linux-hardware.org/?probe=8fbbf1483d) | Aug 09, 2023 |
| HP            | Notebook                    | [59e006f729](https://linux-hardware.org/?probe=59e006f729) | Aug 09, 2023 |
| ASUSTek       | X540LJ                      | [e28870563c](https://linux-hardware.org/?probe=e28870563c) | Aug 09, 2023 |
| HP            | ProBook 650 G2              | [78859b39fb](https://linux-hardware.org/?probe=78859b39fb) | Aug 09, 2023 |
| HP            | Notebook                    | [5cfbf14023](https://linux-hardware.org/?probe=5cfbf14023) | Aug 07, 2023 |
| ASUSTek       | X540SA                      | [db952b584b](https://linux-hardware.org/?probe=db952b584b) | Aug 07, 2023 |
| Dell          | Inspiron 15-3567            | [cf49ab1496](https://linux-hardware.org/?probe=cf49ab1496) | Aug 04, 2023 |
| Dell          | Inspiron 15-3567            | [49e694bb22](https://linux-hardware.org/?probe=49e694bb22) | Aug 04, 2023 |
| Lenovo        | V15-ADA 82C7                | [effe3c3d6d](https://linux-hardware.org/?probe=effe3c3d6d) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [30b14bc4f6](https://linux-hardware.org/?probe=30b14bc4f6) | Aug 04, 2023 |
| HP            | Laptop 17-ak0xx             | [0e36ac41e4](https://linux-hardware.org/?probe=0e36ac41e4) | Aug 04, 2023 |
| HP            | Pavilion 17                 | [e0cf9c4fce](https://linux-hardware.org/?probe=e0cf9c4fce) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [4c45ace98b](https://linux-hardware.org/?probe=4c45ace98b) | Aug 03, 2023 |
| Acer          | Aspire ES1-533              | [b7ffeb681e](https://linux-hardware.org/?probe=b7ffeb681e) | Aug 03, 2023 |
| ASUSTek       | X541NA                      | [b8ece2fce1](https://linux-hardware.org/?probe=b8ece2fce1) | Aug 03, 2023 |
| HP            | Pavilion 17                 | [abad0a7963](https://linux-hardware.org/?probe=abad0a7963) | Aug 02, 2023 |
| HP            | Notebook                    | [b73fa31837](https://linux-hardware.org/?probe=b73fa31837) | Aug 02, 2023 |
| Lenovo        | Z50-75 80EC                 | [0b22fa6444](https://linux-hardware.org/?probe=0b22fa6444) | Aug 02, 2023 |
| HP            | Notebook                    | [329c725795](https://linux-hardware.org/?probe=329c725795) | Jul 31, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [c3b01ce24d](https://linux-hardware.org/?probe=c3b01ce24d) | Jul 30, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [8e26feba38](https://linux-hardware.org/?probe=8e26feba38) | Jul 30, 2023 |
| Fujitsu       | LIFEBOOK A512               | [7bcd0d7683](https://linux-hardware.org/?probe=7bcd0d7683) | Jul 30, 2023 |
| Dell          | Inspiron 7737               | [6fd92e6150](https://linux-hardware.org/?probe=6fd92e6150) | Jul 29, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | [68d5cb02bf](https://linux-hardware.org/?probe=68d5cb02bf) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [3c326304ab](https://linux-hardware.org/?probe=3c326304ab) | Jul 29, 2023 |
| ASUSTek       | X550CL                      | [4e19477a40](https://linux-hardware.org/?probe=4e19477a40) | Jul 29, 2023 |
| Fujitsu       | LIFEBOOK A512               | [404f75d04c](https://linux-hardware.org/?probe=404f75d04c) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [19d341d49d](https://linux-hardware.org/?probe=19d341d49d) | Jul 28, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [a7c322fa40](https://linux-hardware.org/?probe=a7c322fa40) | Jul 28, 2023 |
| Lenovo        | ThinkPad T500 2056CL8       | [180a80b4fe](https://linux-hardware.org/?probe=180a80b4fe) | Jul 26, 2023 |
| Dell          | Latitude E5410              | [e26148754b](https://linux-hardware.org/?probe=e26148754b) | Jul 25, 2023 |
| Toshiba       | Satellite C660              | [11a6a3a607](https://linux-hardware.org/?probe=11a6a3a607) | Jul 23, 2023 |
| Acer          | Aspire ES1-571              | [8f2c838141](https://linux-hardware.org/?probe=8f2c838141) | Jul 22, 2023 |
| ASUSTek       | X550CL                      | [c4da72acde](https://linux-hardware.org/?probe=c4da72acde) | Jul 21, 2023 |
| ASUSTek       | X550CL                      | [2d8ae98d9c](https://linux-hardware.org/?probe=2d8ae98d9c) | Jul 21, 2023 |
| Acer          | Aspire ES1-571              | [e022b7bd64](https://linux-hardware.org/?probe=e022b7bd64) | Jul 21, 2023 |
| Dell          | Inspiron 7737               | [1faafe201d](https://linux-hardware.org/?probe=1faafe201d) | Jul 19, 2023 |
| Acer          | Aspire One 753              | [f2b71747bc](https://linux-hardware.org/?probe=f2b71747bc) | Jul 18, 2023 |
| Acer          | Aspire One 753              | [53d0821b75](https://linux-hardware.org/?probe=53d0821b75) | Jul 18, 2023 |
| Acer          | Aspire 8930                 | [8b9534387b](https://linux-hardware.org/?probe=8b9534387b) | Jul 17, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [b6925518be](https://linux-hardware.org/?probe=b6925518be) | Jul 16, 2023 |
| HP            | EliteBook 8570w             | [05a330fa6c](https://linux-hardware.org/?probe=05a330fa6c) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [60947b35a4](https://linux-hardware.org/?probe=60947b35a4) | Jul 16, 2023 |
| HP            | ProBook 640 G8 Notebook ... | [856a25b9d5](https://linux-hardware.org/?probe=856a25b9d5) | Jul 16, 2023 |
| Dell          | Inspiron 17 7000 Series ... | [1ccdf38dfa](https://linux-hardware.org/?probe=1ccdf38dfa) | Jul 16, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | [71045dea53](https://linux-hardware.org/?probe=71045dea53) | Jul 16, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [8cc38e55a2](https://linux-hardware.org/?probe=8cc38e55a2) | Jul 15, 2023 |
| Lenovo        | ThinkPad R400 7440EL1       | [c0101c7ae1](https://linux-hardware.org/?probe=c0101c7ae1) | Jul 15, 2023 |
| Acer          | Aspire 6930G                | [ba12b5ff3e](https://linux-hardware.org/?probe=ba12b5ff3e) | Jul 14, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [34e242c377](https://linux-hardware.org/?probe=34e242c377) | Jul 13, 2023 |
| RM            | Mobile ONE WIDESCREEN       | [bc67d71f5f](https://linux-hardware.org/?probe=bc67d71f5f) | Jul 13, 2023 |
| HP            | EliteBook 8570w             | [5d1ed4c0a4](https://linux-hardware.org/?probe=5d1ed4c0a4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [c23f2219b4](https://linux-hardware.org/?probe=c23f2219b4) | Jul 12, 2023 |
| Fujitsu       | LIFEBOOK U745               | [e169b67c63](https://linux-hardware.org/?probe=e169b67c63) | Jul 12, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [8528943b9e](https://linux-hardware.org/?probe=8528943b9e) | Jul 11, 2023 |
| Toshiba       | Satellite C55-A-1NV         | [1f9c336539](https://linux-hardware.org/?probe=1f9c336539) | Jul 11, 2023 |
| eMachines     | E725                        | [69e7b54469](https://linux-hardware.org/?probe=69e7b54469) | Jul 10, 2023 |
| eMachines     | E725                        | [307f75ef0a](https://linux-hardware.org/?probe=307f75ef0a) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [fe0bc25044](https://linux-hardware.org/?probe=fe0bc25044) | Jul 09, 2023 |
| Lenovo        | B50-30 20382                | [70e2ac254a](https://linux-hardware.org/?probe=70e2ac254a) | Jul 09, 2023 |
| eMachines     | E725                        | [c70b217933](https://linux-hardware.org/?probe=c70b217933) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [f47888ce55](https://linux-hardware.org/?probe=f47888ce55) | Jul 08, 2023 |
| Acer          | Aspire One 753              | [9f56cc566d](https://linux-hardware.org/?probe=9f56cc566d) | Jul 08, 2023 |
| Sony          | VPCYB3V1E                   | [2dd9b76ce0](https://linux-hardware.org/?probe=2dd9b76ce0) | Jul 06, 2023 |
| Acer          | Aspire E5-575G              | [713b52b0c5](https://linux-hardware.org/?probe=713b52b0c5) | Jul 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | [11537fb0f5](https://linux-hardware.org/?probe=11537fb0f5) | Jul 04, 2023 |
| Acer          | Aspire E5-575G              | [fe616ea0ed](https://linux-hardware.org/?probe=fe616ea0ed) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [22879dbc9e](https://linux-hardware.org/?probe=22879dbc9e) | Jul 03, 2023 |
| Dell          | Inspiron 5558               | [496b83b6b8](https://linux-hardware.org/?probe=496b83b6b8) | Jul 03, 2023 |
| eMachines     | E725                        | [ca2b670023](https://linux-hardware.org/?probe=ca2b670023) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [efa8ecd790](https://linux-hardware.org/?probe=efa8ecd790) | Jul 03, 2023 |
| Dell          | Inspiron 15-3567            | [72af61849b](https://linux-hardware.org/?probe=72af61849b) | Jul 03, 2023 |
| eMachines     | E725                        | [622425a84f](https://linux-hardware.org/?probe=622425a84f) | Jul 02, 2023 |
| Dell          | Inspiron 15-3567            | [ef1c856eb5](https://linux-hardware.org/?probe=ef1c856eb5) | Jul 02, 2023 |
| HP            | 650                         | [279f48a7df](https://linux-hardware.org/?probe=279f48a7df) | Jul 01, 2023 |
| HP            | Notebook                    | [552c6713e1](https://linux-hardware.org/?probe=552c6713e1) | Jun 30, 2023 |
| Dell          | Inspiron 15-3567            | [d3f7bcfb2c](https://linux-hardware.org/?probe=d3f7bcfb2c) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [1efefadbdf](https://linux-hardware.org/?probe=1efefadbdf) | Jun 27, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [e304e9beeb](https://linux-hardware.org/?probe=e304e9beeb) | Jun 27, 2023 |
| Dell          | Inspiron 5558               | [126187748f](https://linux-hardware.org/?probe=126187748f) | Jun 27, 2023 |
| eMachines     | E725                        | [e1ed487442](https://linux-hardware.org/?probe=e1ed487442) | Jun 26, 2023 |
| eMachines     | E725                        | [909f61c87a](https://linux-hardware.org/?probe=909f61c87a) | Jun 26, 2023 |
| HP            | Notebook                    | [ce52423528](https://linux-hardware.org/?probe=ce52423528) | Jun 26, 2023 |
| Lenovo        | IdeaPad 330-15AST 81D6      | [604d6b2b6f](https://linux-hardware.org/?probe=604d6b2b6f) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [d34d125de2](https://linux-hardware.org/?probe=d34d125de2) | Jun 26, 2023 |
| HP            | ProBook 650 G2              | [1858ae62ee](https://linux-hardware.org/?probe=1858ae62ee) | Jun 26, 2023 |
| Dell          | Inspiron 5558               | [43849169cb](https://linux-hardware.org/?probe=43849169cb) | Jun 25, 2023 |
| HP            | EliteBook 2540p             | [2b3a2327fb](https://linux-hardware.org/?probe=2b3a2327fb) | Jun 24, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [186b2c5cb7](https://linux-hardware.org/?probe=186b2c5cb7) | Jun 24, 2023 |
| Acer          | Aspire A114-31              | [3cb015a09d](https://linux-hardware.org/?probe=3cb015a09d) | Jun 23, 2023 |
| HP            | Notebook                    | [6710ed8c9c](https://linux-hardware.org/?probe=6710ed8c9c) | Jun 21, 2023 |
| Dell          | Latitude E6410              | [1d89edd254](https://linux-hardware.org/?probe=1d89edd254) | Jun 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/BlackPanther/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| BlackPanther 18.1 | 1680      | 88.65%  |
| BlackPanther 16.2 | 185       | 9.76%   |
| BlackPanther 22.1 | 28        | 1.48%   |
| BlackPanther 16.1 | 2         | 0.11%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| BlackPanther | 1861      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 4.18.16-desktop-1bP     | 1179      | 54.86%  |
| 5.6.14-desktop-2bP      | 504       | 23.45%  |
| 4.9.20-desktop-pae-1bP  | 175       | 8.14%   |
| 5.15.85-desktop-1bP     | 147       | 6.84%   |
| 5.1.15-desktop-1bP      | 79        | 3.68%   |
| 6.3.8-desktop-1bP       | 21        | 0.98%   |
| 6.5.3-power-1bP         | 5         | 0.23%   |
| 6.3.3-desktop-1bP       | 5         | 0.23%   |
| 4.9.20-desktop-1bP      | 5         | 0.23%   |
| 6.6.11-power-1bP        | 4         | 0.19%   |
| 4.7.0-desktop-1bP       | 4         | 0.19%   |
| 6.4.3-desktop-1bP       | 3         | 0.14%   |
| 6.2.9-desktop-1bP       | 3         | 0.14%   |
| 6.5.7-power-1bP         | 2         | 0.09%   |
| 5.6.14-server-2bP       | 2         | 0.09%   |
| 5.10.1-desktop-1bP      | 2         | 0.09%   |
| 4.14.14-desktop-pae-1bP | 2         | 0.09%   |
| 6.6.4-200.fc39.x86_64   | 1         | 0.05%   |
| 6.1.0-1bP               | 1         | 0.05%   |
| 5.8.11-desktop-2bP      | 1         | 0.05%   |
| 5.15.6-desktop-1bP      | 1         | 0.05%   |
| 5.10.1-desktop-2bP      | 1         | 0.05%   |
| 5.1.15-server-1bP       | 1         | 0.05%   |
| 4.15.0-desktop-pae-1bP  | 1         | 0.05%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18.16 | 1179      | 54.89%  |
| 5.6.14  | 506       | 23.56%  |
| 4.9.20  | 180       | 8.38%   |
| 5.15.85 | 147       | 6.84%   |
| 5.1.15  | 79        | 3.68%   |
| 6.3.8   | 21        | 0.98%   |
| 6.5.3   | 5         | 0.23%   |
| 6.3.3   | 5         | 0.23%   |
| 6.6.11  | 4         | 0.19%   |
| 4.7.0   | 4         | 0.19%   |
| 6.4.3   | 3         | 0.14%   |
| 6.2.9   | 3         | 0.14%   |
| 5.10.1  | 3         | 0.14%   |
| 6.5.7   | 2         | 0.09%   |
| 4.14.14 | 2         | 0.09%   |
| 6.6.4   | 1         | 0.05%   |
| 6.1.0   | 1         | 0.05%   |
| 5.8.11  | 1         | 0.05%   |
| 5.15.6  | 1         | 0.05%   |
| 4.15.0  | 1         | 0.05%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 4.18    | 1179      | 54.94%  |
| 5.6     | 506       | 23.58%  |
| 4.9     | 180       | 8.39%   |
| 5.15    | 148       | 6.9%    |
| 5.1     | 79        | 3.68%   |
| 6.3     | 24        | 1.12%   |
| 6.5     | 7         | 0.33%   |
| 6.6     | 5         | 0.23%   |
| 4.7     | 4         | 0.19%   |
| 6.4     | 3         | 0.14%   |
| 6.2     | 3         | 0.14%   |
| 5.10    | 3         | 0.14%   |
| 4.14    | 2         | 0.09%   |
| 6.1     | 1         | 0.05%   |
| 5.8     | 1         | 0.05%   |
| 4.15    | 1         | 0.05%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 1703      | 90.11%  |
| i686   | 187       | 9.89%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| KDE5     | 1811      | 97%     |
| Unknown  | 51        | 2.73%   |
| KDE      | 3         | 0.16%   |
| Cinnamon | 1         | 0.05%   |
| Budgie   | 1         | 0.05%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 1857      | 99.68%  |
| Wayland | 4         | 0.21%   |
| Unknown | 2         | 0.11%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| SDDM    | 1854      | 99.41%  |
| Unknown | 10        | 0.54%   |
| LightDM | 1         | 0.05%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 1860      | 99.79%  |
| hu_HU   | 4         | 0.21%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| BIOS | 1277      | 65.09%  |
| EFI  | 685       | 34.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Overlay | 1168      | 54.71%  |
| Ext4    | 949       | 44.45%  |
| Unknown | 7         | 0.33%   |
| Btrfs   | 5         | 0.23%   |
| Ext2    | 3         | 0.14%   |
| Xfs     | 1         | 0.05%   |
| Ntfs    | 1         | 0.05%   |
| Ext3    | 1         | 0.05%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| MBR     | 1215      | 61.86%  |
| GPT     | 733       | 37.32%  |
| Unknown | 16        | 0.81%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1360      | 65.48%  |
| Yes       | 717       | 34.52%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 1096      | 53.96%  |
| Yes       | 935       | 46.04%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                   | Notebooks | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 393       | 21.12%  |
| Lenovo                 | 335       | 18%     |
| Dell                   | 288       | 15.48%  |
| ASUSTek Computer       | 247       | 13.27%  |
| Acer                   | 203       | 10.91%  |
| Toshiba                | 81        | 4.35%   |
| Samsung Electronics    | 44        | 2.36%   |
| Fujitsu                | 36        | 1.93%   |
| Packard Bell           | 30        | 1.61%   |
| Fujitsu Siemens        | 29        | 1.56%   |
| MSI                    | 25        | 1.34%   |
| Sony                   | 23        | 1.24%   |
| eMachines              | 20        | 1.07%   |
| Apple                  | 19        | 1.02%   |
| Medion                 | 17        | 0.91%   |
| Alcor                  | 6         | 0.32%   |
| Hungaro Flotta Kft     | 5         | 0.27%   |
| Gateway                | 5         | 0.27%   |
| BANGHO                 | 4         | 0.21%   |
| Unknown                | 4         | 0.21%   |
| Insyde                 | 3         | 0.16%   |
| speedmaster            | 2         | 0.11%   |
| Positivo               | 2         | 0.11%   |
| Panasonic              | 2         | 0.11%   |
| Notebook               | 2         | 0.11%   |
| Jumper                 | 2         | 0.11%   |
| Intel                  | 2         | 0.11%   |
| Google                 | 2         | 0.11%   |
| Gigabyte Technology    | 2         | 0.11%   |
| AWOW                   | 2         | 0.11%   |
| Alienware              | 2         | 0.11%   |
| Valve                  | 1         | 0.05%   |
| TUXEDO                 | 1         | 0.05%   |
| Timi                   | 1         | 0.05%   |
| THD                    | 1         | 0.05%   |
| RM                     | 1         | 0.05%   |
| Philco                 | 1         | 0.05%   |
| Pegatron               | 1         | 0.05%   |
| ONE-NETBOOK TECHNOLOGY | 1         | 0.05%   |
| NOBLEX                 | 1         | 0.05%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| HP 250 G1                            | 40        | 2.15%   |
| Dell Latitude E6410                  | 20        | 1.07%   |
| HP ProBook 455 G1                    | 15        | 0.81%   |
| HP Notebook                          | 15        | 0.81%   |
| Unknown                              | 14        | 0.75%   |
| Lenovo IdeaPad 330-15IKB 81DE        | 12        | 0.64%   |
| Lenovo G50-45 80E3                   | 11        | 0.59%   |
| Dell Inspiron 7737                   | 10        | 0.54%   |
| Toshiba Satellite C660               | 9         | 0.48%   |
| Lenovo IdeaPad 100-15IBD 80QQ        | 9         | 0.48%   |
| HP Pavilion g6                       | 9         | 0.48%   |
| HP 650                               | 9         | 0.48%   |
| HP 620                               | 8         | 0.43%   |
| Dell Latitude 5480                   | 8         | 0.43%   |
| Dell Inspiron 3521                   | 8         | 0.43%   |
| ASUS X550CC                          | 8         | 0.43%   |
| ASUS K50IJ                           | 8         | 0.43%   |
| HP Pavilion Notebook                 | 7         | 0.38%   |
| HP 250 G5 Notebook PC                | 7         | 0.38%   |
| Dell Latitude E6430                  | 7         | 0.38%   |
| Dell Latitude E6400                  | 7         | 0.38%   |
| ASUS VivoBook 15_ASUS Laptop X540UBR | 7         | 0.38%   |
| Lenovo G550 20023                    | 6         | 0.32%   |
| Lenovo G50-30 80G0                   | 6         | 0.32%   |
| HP ProBook 640 G8 Notebook PC        | 6         | 0.32%   |
| HP Pavilion dv6                      | 6         | 0.32%   |
| HP EliteBook 8470p                   | 6         | 0.32%   |
| HP EliteBook 8460p                   | 6         | 0.32%   |
| eMachines E525                       | 6         | 0.32%   |
| Dell Latitude E6420                  | 6         | 0.32%   |
| Dell Latitude E4310                  | 6         | 0.32%   |
| ASUS VivoBook 15_ASUS Laptop X540UAR | 6         | 0.32%   |
| Acer Aspire 5732Z                    | 6         | 0.32%   |
| Toshiba Satellite L300               | 5         | 0.27%   |
| Lenovo Z50-75 80EC                   | 5         | 0.27%   |
| Lenovo G505s 20255                   | 5         | 0.27%   |
| HP ProBook 6450b                     | 5         | 0.27%   |
| HP Presario CQ57                     | 5         | 0.27%   |
| HP EliteBook 8440p                   | 5         | 0.27%   |
| HP EliteBook 6930p                   | 5         | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Acer Aspire              | 156       | 8.38%   |
| Dell Latitude            | 141       | 7.58%   |
| Lenovo ThinkPad          | 125       | 6.72%   |
| Dell Inspiron            | 108       | 5.8%    |
| Lenovo IdeaPad           | 94        | 5.05%   |
| Toshiba Satellite        | 73        | 3.92%   |
| HP ProBook               | 70        | 3.76%   |
| HP EliteBook             | 60        | 3.22%   |
| HP 250                   | 55        | 2.96%   |
| HP Pavilion              | 51        | 2.74%   |
| HP Compaq                | 40        | 2.15%   |
| Packard Bell EasyNote    | 29        | 1.56%   |
| Fujitsu LIFEBOOK         | 29        | 1.56%   |
| ASUS VivoBook            | 29        | 1.56%   |
| Fujitsu Siemens AMILO    | 20        | 1.07%   |
| Acer TravelMate          | 18        | 0.97%   |
| HP Laptop                | 16        | 0.86%   |
| HP Notebook              | 15        | 0.81%   |
| Unknown                  | 14        | 0.75%   |
| Dell Vostro              | 13        | 0.7%    |
| Lenovo G50-45            | 11        | 0.59%   |
| HP Presario              | 10        | 0.54%   |
| Dell Precision           | 10        | 0.54%   |
| Lenovo 3000              | 9         | 0.48%   |
| HP 650                   | 9         | 0.48%   |
| HP 620                   | 8         | 0.43%   |
| ASUS X550CC              | 8         | 0.43%   |
| ASUS K50IJ               | 8         | 0.43%   |
| HP 255                   | 7         | 0.38%   |
| ASUS ASUS                | 7         | 0.38%   |
| Lenovo G550              | 6         | 0.32%   |
| Lenovo G50-30            | 6         | 0.32%   |
| HP 15                    | 6         | 0.32%   |
| eMachines E525           | 6         | 0.32%   |
| Acer Extensa             | 6         | 0.32%   |
| Lenovo Z50-75            | 5         | 0.27%   |
| Lenovo G580              | 5         | 0.27%   |
| Lenovo G505s             | 5         | 0.27%   |
| Hungaro Flotta Kft Navon | 5         | 0.27%   |
| Fujitsu Siemens LIFEBOOK | 5         | 0.27%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2011    | 235       | 12.63%  |
| 2013    | 217       | 11.66%  |
| 2010    | 195       | 10.48%  |
| 2012    | 163       | 8.76%   |
| 2008    | 149       | 8.01%   |
| 2014    | 142       | 7.63%   |
| 2009    | 133       | 7.15%   |
| 2015    | 111       | 5.96%   |
| 2016    | 103       | 5.53%   |
| 2007    | 95        | 5.1%    |
| 2018    | 88        | 4.73%   |
| 2017    | 87        | 4.67%   |
| 2019    | 46        | 2.47%   |
| 2006    | 41        | 2.2%    |
| 2020    | 27        | 1.45%   |
| 2021    | 15        | 0.81%   |
| 2005    | 9         | 0.48%   |
| 2023    | 2         | 0.11%   |
| 2024    | 1         | 0.05%   |
| 2022    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 1861      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 1861      | 99.95%  |
| Enabled  | 1         | 0.05%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1859      | 99.89%  |
| Yes  | 2         | 0.11%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 3.01-4.0   | 775       | 40.26%  |
| 4.01-8.0   | 418       | 21.71%  |
| 8.01-16.0  | 259       | 13.45%  |
| 1.01-2.0   | 248       | 12.88%  |
| 2.01-3.0   | 93        | 4.83%   |
| 16.01-24.0 | 77        | 4%      |
| 0.51-1.0   | 34        | 1.77%   |
| 24.01-32.0 | 11        | 0.57%   |
| 32.01-64.0 | 8         | 0.42%   |
| Unknown    | 2         | 0.1%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 0.51-1.0   | 1143      | 50.44%  |
| 1.01-2.0   | 690       | 30.45%  |
| 0.01-0.5   | 284       | 12.53%  |
| 2.01-3.0   | 82        | 3.62%   |
| 3.01-4.0   | 33        | 1.46%   |
| 4.01-8.0   | 27        | 1.19%   |
| 8.01-16.0  | 3         | 0.13%   |
| 16.01-24.0 | 2         | 0.09%   |
| Unknown    | 2         | 0.09%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1570      | 79.86%  |
| 2      | 329       | 16.73%  |
| 3      | 44        | 2.24%   |
| 0      | 19        | 0.97%   |
| 4      | 3         | 0.15%   |
| 5      | 1         | 0.05%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1227      | 65.02%  |
| No        | 660       | 34.98%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1741      | 93.45%  |
| No        | 122       | 6.55%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1834      | 98.44%  |
| No        | 29        | 1.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 1320      | 69.55%  |
| No        | 578       | 30.45%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country     | Notebooks | Percent |
|-------------|-----------|---------|
| Hungary     | 1349      | 71.95%  |
| Germany     | 95        | 5.07%   |
| USA         | 74        | 3.95%   |
| Slovakia    | 38        | 2.03%   |
| UK          | 33        | 1.76%   |
| Romania     | 31        | 1.65%   |
| Austria     | 27        | 1.44%   |
| Italy       | 21        | 1.12%   |
| France      | 20        | 1.07%   |
| Argentina   | 17        | 0.91%   |
| Spain       | 16        | 0.85%   |
| Canada      | 16        | 0.85%   |
| Japan       | 11        | 0.59%   |
| Brazil      | 11        | 0.59%   |
| Serbia      | 10        | 0.53%   |
| Poland      | 7         | 0.37%   |
| Russia      | 6         | 0.32%   |
| Australia   | 6         | 0.32%   |
| Switzerland | 5         | 0.27%   |
| Ireland     | 5         | 0.27%   |
| Belgium     | 5         | 0.27%   |
| Sweden      | 4         | 0.21%   |
| Netherlands | 4         | 0.21%   |
| Greece      | 4         | 0.21%   |
| India       | 3         | 0.16%   |
| Finland     | 3         | 0.16%   |
| Czechia     | 3         | 0.16%   |
| China       | 3         | 0.16%   |
| UAE         | 2         | 0.11%   |
| Turkey      | 2         | 0.11%   |
| Puerto Rico | 2         | 0.11%   |
| Philippines | 2         | 0.11%   |
| Moldova     | 2         | 0.11%   |
| Mexico      | 2         | 0.11%   |
| Madagascar  | 2         | 0.11%   |
| Israel      | 2         | 0.11%   |
| Indonesia   | 2         | 0.11%   |
| Ghana       | 2         | 0.11%   |
| Ecuador     | 2         | 0.11%   |
| Cyprus      | 2         | 0.11%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Notebooks | Percent |
|-------------------|-----------|---------|
| Budapest          | 538       | 23.05%  |
| Tatabánya        | 32        | 1.37%   |
| Miskolc           | 32        | 1.37%   |
| Debrecen          | 32        | 1.37%   |
| Pécs             | 30        | 1.29%   |
| Győr             | 29        | 1.24%   |
| Zalaegerszeg      | 28        | 1.2%    |
| Veszprém         | 25        | 1.07%   |
| Székesfehérvár | 25        | 1.07%   |
| Szeged            | 24        | 1.03%   |
| Nyiregyhaza       | 23        | 0.99%   |
| Szombathely       | 22        | 0.94%   |
| Szolnok           | 19        | 0.81%   |
| Vienna            | 17        | 0.73%   |
| Szigetszentmiklos | 16        | 0.69%   |
| Salgotarjan       | 16        | 0.69%   |
| Pomaz             | 15        | 0.64%   |
| Kecskemét        | 15        | 0.64%   |
| Cegled            | 14        | 0.6%    |
| Érd              | 13        | 0.56%   |
| Bratislava        | 13        | 0.56%   |
| Toekoel           | 12        | 0.51%   |
| Szorgalmatos      | 12        | 0.51%   |
| Szekszárd        | 12        | 0.51%   |
| Kaposvár         | 12        | 0.51%   |
| Regensburg        | 11        | 0.47%   |
| Kazincbarcika     | 11        | 0.47%   |
| Dunaújváros     | 11        | 0.47%   |
| Berettyóújfalu  | 11        | 0.47%   |
| Tiszaujvaros      | 10        | 0.43%   |
| Târgu Mureş     | 10        | 0.43%   |
| Kiskunfelegyhaza  | 10        | 0.43%   |
| Karcag            | 10        | 0.43%   |
| Banská Bystrica  | 10        | 0.43%   |
| Ajka              | 10        | 0.43%   |
| Sopron            | 9         | 0.39%   |
| Nagykanizsa       | 9         | 0.39%   |
| Gyomro            | 9         | 0.39%   |
| Obertraubling     | 8         | 0.34%   |
| Hatvan            | 8         | 0.34%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 370       | 619    | 15.8%   |
| WDC                 | 321       | 529    | 13.71%  |
| Kingston            | 252       | 448    | 10.76%  |
| Toshiba             | 246       | 387    | 10.5%   |
| Samsung Electronics | 192       | 386    | 8.2%    |
| HGST                | 163       | 258    | 6.96%   |
| Hitachi             | 152       | 227    | 6.49%   |
| SanDisk             | 83        | 159    | 3.54%   |
| Unknown             | 81        | 146    | 3.46%   |
| Fujitsu             | 49        | 61     | 2.09%   |
| Intel               | 41        | 70     | 1.75%   |
| A-DATA Technology   | 39        | 66     | 1.67%   |
| Crucial             | 35        | 48     | 1.49%   |
| SK hynix            | 31        | 53     | 1.32%   |
| Intenso             | 22        | 56     | 0.94%   |
| SPCC                | 19        | 34     | 0.81%   |
| Apacer              | 19        | 31     | 0.81%   |
| Micron Technology   | 17        | 37     | 0.73%   |
| JMicron Technology  | 17        | 18     | 0.73%   |
| PNY                 | 16        | 27     | 0.68%   |
| China               | 16        | 27     | 0.68%   |
| Patriot             | 13        | 19     | 0.56%   |
| LITEON              | 12        | 26     | 0.51%   |
| Transcend           | 8         | 9      | 0.34%   |
| LITEONIT            | 8         | 19     | 0.34%   |
| Kingmax             | 8         | 10     | 0.34%   |
| Team                | 7         | 12     | 0.3%    |
| SSSTC               | 7         | 18     | 0.3%    |
| Gigabyte Technology | 7         | 10     | 0.3%    |
| OCZ                 | 6         | 7      | 0.26%   |
| Unknown             | 5         | 12     | 0.21%   |
| Verbatim            | 4         | 8      | 0.17%   |
| KingSpec            | 4         | 5      | 0.17%   |
| BHT                 | 4         | 4      | 0.17%   |
| Apple               | 4         | 13     | 0.17%   |
| Netac               | 3         | 3      | 0.13%   |
| Hewlett-Packard     | 3         | 3      | 0.13%   |
| GOODRAM             | 3         | 3      | 0.13%   |
| TO Exter            | 2         | 3      | 0.09%   |
| ShanDianZhe         | 2         | 2      | 0.09%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                              | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD    | 62        | 2.54%   |
| Kingston SA400S37120G 120GB SSD    | 59        | 2.42%   |
| Seagate ST1000LM035-1RK172 1TB     | 47        | 1.93%   |
| Toshiba MQ01ABD100 1TB             | 42        | 1.72%   |
| Toshiba MQ01ABF050 500GB           | 38        | 1.56%   |
| Seagate ST500LT012-1DG142 500GB    | 37        | 1.52%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 36        | 1.48%   |
| HGST HTS545050A7E680 500GB         | 35        | 1.44%   |
| HGST HTS545032A7E380 320GB         | 33        | 1.35%   |
| Kingston SA400S37480G 480GB SSD    | 32        | 1.31%   |
| Kingston SV300S37A120G 120GB SSD   | 27        | 1.11%   |
| HGST HTS725050A7E630 500GB         | 25        | 1.03%   |
| Seagate ST9500325AS 500GB          | 22        | 0.9%    |
| Seagate ST9320325AS 320GB          | 22        | 0.9%    |
| WDC WD10JPVX-22JC3T0 1TB           | 18        | 0.74%   |
| Toshiba MQ04ABF100 1TB             | 18        | 0.74%   |
| Seagate ST500LT012-9WS142 500GB    | 15        | 0.62%   |
| Kingston SUV400S37120G 120GB SSD   | 15        | 0.62%   |
| HGST HTS721010A9E630 1TB           | 15        | 0.62%   |
| Seagate ST9250315AS 250GB          | 14        | 0.57%   |
| HGST HTS545050A7E380 500GB         | 14        | 0.57%   |
| HGST HTS541010A9E680 1TB           | 14        | 0.57%   |
| Toshiba MQ01ABD050 500GB           | 13        | 0.53%   |
| Kingston SA400S37960G 960GB SSD    | 12        | 0.49%   |
| Seagate ST500LM000-1EJ162 500GB    | 11        | 0.45%   |
| Seagate M3 Portable 4TB            | 11        | 0.45%   |
| Samsung SSD 860 EVO 500GB          | 11        | 0.45%   |
| Samsung SSD 850 EVO 250GB          | 11        | 0.45%   |
| WDC WD5000LPVX-22V0TT0 500GB       | 10        | 0.41%   |
| WDC WD5000LPCX-24VHAT0 500GB       | 10        | 0.41%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 10        | 0.41%   |
| Samsung HM160HI 160GB              | 10        | 0.41%   |
| JMicron Generic 320GB              | 10        | 0.41%   |
| Hitachi HTS723232A7A364 320GB      | 10        | 0.41%   |
| Hitachi HTS543232A7A384 320GB      | 10        | 0.41%   |
| WDC WD10JPVX-60JC3T0 1TB           | 9         | 0.37%   |
| Toshiba MQ01ABD075 752GB           | 9         | 0.37%   |
| Crucial CT120BX500SSD1 120GB       | 9         | 0.37%   |
| WDC WD5000LPCX-24C6HT0 500GB       | 8         | 0.33%   |
| WDC WD3200BPVT-22JJ5T0 320GB       | 8         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 359       | 603    | 27.64%  |
| WDC                 | 292       | 480    | 22.48%  |
| Toshiba             | 224       | 332    | 17.24%  |
| HGST                | 163       | 258    | 12.55%  |
| Hitachi             | 152       | 227    | 11.7%   |
| Fujitsu             | 49        | 61     | 3.77%   |
| Samsung Electronics | 33        | 46     | 2.54%   |
| JMicron Technology  | 11        | 11     | 0.85%   |
| Unknown             | 5         | 12     | 0.38%   |
| TO Exter            | 2         | 3      | 0.15%   |
| IBM/Hitachi         | 2         | 3      | 0.15%   |
| QC-FT-D             | 1         | 1      | 0.08%   |
| MARSHAL             | 1         | 2      | 0.08%   |
| Initio              | 1         | 2      | 0.08%   |
| ICY BOX             | 1         | 1      | 0.08%   |
| IB-1122             | 1         | 1      | 0.08%   |
| HGST HTS            | 1         | 6      | 0.08%   |
| CSD                 | 1         | 2      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 241       | 422    | 29.18%  |
| Samsung Electronics | 123       | 247    | 14.89%  |
| SanDisk             | 69        | 134    | 8.35%   |
| A-DATA Technology   | 37        | 64     | 4.48%   |
| Crucial             | 35        | 48     | 4.24%   |
| Intel               | 30        | 51     | 3.63%   |
| WDC                 | 28        | 41     | 3.39%   |
| SK hynix            | 24        | 39     | 2.91%   |
| Intenso             | 22        | 56     | 2.66%   |
| SPCC                | 18        | 33     | 2.18%   |
| Apacer              | 17        | 27     | 2.06%   |
| PNY                 | 16        | 27     | 1.94%   |
| China               | 16        | 27     | 1.94%   |
| Micron Technology   | 15        | 30     | 1.82%   |
| Patriot             | 13        | 19     | 1.57%   |
| Toshiba             | 11        | 33     | 1.33%   |
| LITEON              | 11        | 19     | 1.33%   |
| Transcend           | 8         | 9      | 0.97%   |
| LITEONIT            | 8         | 19     | 0.97%   |
| Kingmax             | 8         | 10     | 0.97%   |
| Team                | 7         | 12     | 0.85%   |
| Gigabyte Technology | 7         | 10     | 0.85%   |
| OCZ                 | 6         | 7      | 0.73%   |
| Verbatim            | 4         | 8      | 0.48%   |
| KingSpec            | 4         | 5      | 0.48%   |
| BHT                 | 4         | 4      | 0.48%   |
| Apple               | 4         | 13     | 0.48%   |
| Netac               | 3         | 3      | 0.36%   |
| GOODRAM             | 3         | 3      | 0.36%   |
| ShanDianZhe         | 2         | 2      | 0.24%   |
| HS-SSD-C100         | 2         | 2      | 0.24%   |
| Hewlett-Packard     | 2         | 3      | 0.24%   |
| Corsair             | 2         | 3      | 0.24%   |
| Zheino              | 1         | 1      | 0.12%   |
| XrayDisk            | 1         | 1      | 0.12%   |
| Unknown             | 1         | 3      | 0.12%   |
| Union Memory        | 1         | 5      | 0.12%   |
| Timetec             | 1         | 11     | 0.12%   |
| TCSUNBOW            | 1         | 1      | 0.12%   |
| T-FORCE             | 1         | 1      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 1221      | 2051   | 55.68%  |
| SSD     | 752       | 1486   | 34.29%  |
| NVMe    | 100       | 238    | 4.56%   |
| MMC     | 93        | 166    | 4.24%   |
| Unknown | 27        | 31     | 1.23%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1751      | 3449   | 86.43%  |
| NVMe | 100       | 238    | 4.94%   |
| MMC  | 93        | 166    | 4.59%   |
| SAS  | 82        | 119    | 4.05%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1503      | 2811   | 79.11%  |
| 0.51-1.0   | 368       | 669    | 19.37%  |
| 1.01-2.0   | 26        | 54     | 1.37%   |
| 4.01-10.0  | 2         | 2      | 0.11%   |
| 3.01-4.0   | 1         | 1      | 0.05%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| Unknown        | 1110      | 48.81%  |
| 101-250        | 448       | 19.7%   |
| 251-500        | 281       | 12.36%  |
| 51-100         | 153       | 6.73%   |
| 501-1000       | 104       | 4.57%   |
| 21-50          | 94        | 4.13%   |
| 1001-2000      | 36        | 1.58%   |
| 1-20           | 29        | 1.28%   |
| 2001-3000      | 17        | 0.75%   |
| More than 3000 | 1         | 0.04%   |
| 0              | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| Unknown   | 1110      | 48.07%  |
| 1-20      | 842       | 36.47%  |
| 21-50     | 122       | 5.28%   |
| 51-100    | 89        | 3.85%   |
| 101-250   | 71        | 3.07%   |
| 251-500   | 33        | 1.43%   |
| 1001-2000 | 22        | 0.95%   |
| 501-1000  | 16        | 0.69%   |
| 2001-3000 | 3         | 0.13%   |
| 0         | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| HGST HTS545032A7E380 320GB          | 32        | 59     | 4.73%   |
| HGST HTS545050A7E680 500GB          | 25        | 34     | 3.7%    |
| HGST HTS725050A7E630 500GB          | 18        | 19     | 2.66%   |
| Seagate ST500LT012-1DG142 500GB     | 17        | 32     | 2.51%   |
| Seagate ST500LT012-9WS142 500GB     | 13        | 18     | 1.92%   |
| Seagate ST9500325AS 500GB           | 12        | 22     | 1.78%   |
| Seagate ST9320325AS 320GB           | 12        | 28     | 1.78%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 12        | 16     | 1.78%   |
| Toshiba MQ01ABF050 500GB            | 11        | 35     | 1.63%   |
| Toshiba MQ01ABD100 1TB              | 11        | 12     | 1.63%   |
| HGST HTS545050A7E380 500GB          | 10        | 16     | 1.48%   |
| HGST HTS541010A9E680 1TB            | 10        | 24     | 1.48%   |
| Seagate ST9250315AS 250GB           | 9         | 11     | 1.33%   |
| Samsung Electronics HM160HI 160GB   | 9         | 14     | 1.33%   |
| Hitachi HTS723232A7A364 320GB       | 9         | 9      | 1.33%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 10     | 1.18%   |
| WDC WD10JPVX-22JC3T0 1TB            | 7         | 11     | 1.04%   |
| Kingston SV300S37A120G 120GB SSD    | 7         | 12     | 1.04%   |
| Hitachi HTS543232A7A384 320GB       | 7         | 9      | 1.04%   |
| Seagate ST9320423AS 320GB           | 6         | 6      | 0.89%   |
| Hitachi HTS547550A9E384 500GB       | 6         | 24     | 0.89%   |
| Hitachi HTS545050A7E380 500GB       | 6         | 10     | 0.89%   |
| Toshiba MQ01ABD050 500GB            | 5         | 6      | 0.74%   |
| Seagate ST9500420AS 500GB           | 5         | 14     | 0.74%   |
| Seagate ST500LM000-SSHD-8GB         | 5         | 10     | 0.74%   |
| Samsung Electronics HM321HI 320GB   | 5         | 8      | 0.74%   |
| Hitachi HTS725025A9A364 250GB       | 5         | 6      | 0.74%   |
| Hitachi HTS545050B9A300 500GB       | 5         | 9      | 0.74%   |
| Hitachi HTS545016B9A300 160GB       | 5         | 5      | 0.74%   |
| Hitachi HTS541680J9SA00 80GB        | 5         | 5      | 0.74%   |
| WDC WD2500BEKT-75PVMT0 250GB        | 4         | 6      | 0.59%   |
| Seagate ST980811AS 80GB             | 4         | 5      | 0.59%   |
| Seagate ST9160310AS 160GB           | 4         | 5      | 0.59%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 4         | 5      | 0.59%   |
| Seagate ST500LM000-1EJ162 500GB     | 4         | 6      | 0.59%   |
| Seagate ST320LT007-9ZV142 320GB     | 4         | 4      | 0.59%   |
| Hitachi HTS545032B9A300 320GB       | 4         | 5      | 0.59%   |
| Hitachi HTS545025B9A300 250GB       | 4         | 9      | 0.59%   |
| Hitachi HTS542516K9SA00 160GB       | 4         | 4      | 0.59%   |
| Toshiba MQ01ABD075 752GB            | 3         | 5      | 0.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 161       | 268    | 24.14%  |
| Hitachi             | 102       | 158    | 15.29%  |
| HGST                | 102       | 164    | 15.29%  |
| Toshiba             | 96        | 145    | 14.39%  |
| WDC                 | 90        | 147    | 13.49%  |
| Samsung Electronics | 26        | 52     | 3.9%    |
| Fujitsu             | 21        | 30     | 3.15%   |
| Kingston            | 20        | 35     | 3%      |
| Intel               | 13        | 28     | 1.95%   |
| SK hynix            | 7         | 8      | 1.05%   |
| SanDisk             | 4         | 5      | 0.6%    |
| A-DATA Technology   | 3         | 3      | 0.45%   |
| Intenso             | 2         | 2      | 0.3%    |
| Crucial             | 2         | 2      | 0.3%    |
| China               | 2         | 2      | 0.3%    |
| Apple               | 2         | 11     | 0.3%    |
| Timetec             | 1         | 9      | 0.15%   |
| SPCC                | 1         | 1      | 0.15%   |
| Netac               | 1         | 1      | 0.15%   |
| Micron Technology   | 1         | 1      | 0.15%   |
| MARSHAL             | 1         | 1      | 0.15%   |
| LITEONIT            | 1         | 2      | 0.15%   |
| Kingmax             | 1         | 1      | 0.15%   |
| KING                | 1         | 1      | 0.15%   |
| JMicron Technology  | 1         | 1      | 0.15%   |
| Initio              | 1         | 2      | 0.15%   |
| ICY BOX             | 1         | 1      | 0.15%   |
| IBM/Hitachi         | 1         | 1      | 0.15%   |
| CSD                 | 1         | 2      | 0.15%   |
| Apacer              | 1         | 2      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 161       | 268    | 27.24%  |
| Hitachi             | 102       | 158    | 17.26%  |
| HGST                | 102       | 164    | 17.26%  |
| Toshiba             | 91        | 132    | 15.4%   |
| WDC                 | 87        | 144    | 14.72%  |
| Samsung Electronics | 22        | 32     | 3.72%   |
| Fujitsu             | 21        | 30     | 3.55%   |
| MARSHAL             | 1         | 1      | 0.17%   |
| Initio              | 1         | 2      | 0.17%   |
| ICY BOX             | 1         | 1      | 0.17%   |
| IBM/Hitachi         | 1         | 1      | 0.17%   |
| CSD                 | 1         | 2      | 0.17%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 570       | 935    | 88.37%  |
| SSD     | 72        | 147    | 11.16%  |
| NVMe    | 2         | 3      | 0.31%   |
| Unknown | 1         | 1      | 0.16%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                              | Notebooks | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-22ZAT0 500GB        | 2         | 2      | 8.7%    |
| Toshiba MQ01ABD100 1TB             | 2         | 2      | 8.7%    |
| Toshiba MK6475GSX 640GB            | 2         | 2      | 8.7%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 2      | 8.7%    |
| WDC WD5000BEVT-22A0RT0 500GB       | 1         | 7      | 4.35%   |
| WDC WD3200BVVT-63A26Y0 320GB       | 1         | 1      | 4.35%   |
| WDC WD3200BPVT-24JJ5T0 320GB       | 1         | 1      | 4.35%   |
| WDC WD3200BEVT-08A23T1 320GB       | 1         | 1      | 4.35%   |
| WDC WD2500LPCX-24C6HT0 250GB       | 1         | 1      | 4.35%   |
| WDC WD1600BEVT-22ZCT0 160GB        | 1         | 1      | 4.35%   |
| Toshiba MQ01ABD050V 500GB          | 1         | 1      | 4.35%   |
| Toshiba MK5055GSX 500GB            | 1         | 1      | 4.35%   |
| Toshiba MK3275GSX 320GB            | 1         | 1      | 4.35%   |
| Toshiba MK1665GSX 160GB            | 1         | 1      | 4.35%   |
| Toshiba MK1646GSX 160GB            | 1         | 1      | 4.35%   |
| Seagate ST9320325AS 320GB          | 1         | 1      | 4.35%   |
| Samsung Electronics SSD 980 500GB  | 1         | 1      | 4.35%   |
| Samsung Electronics HM060HI 64GB   | 1         | 1      | 4.35%   |
| Intel SSDPEKKW256G7 256GB          | 1         | 1      | 4.35%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Toshiba             | 9         | 9      | 39.13%  |
| WDC                 | 8         | 14     | 34.78%  |
| Seagate             | 3         | 3      | 13.04%  |
| Samsung Electronics | 2         | 2      | 8.7%    |
| Intel               | 1         | 1      | 4.35%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 1286      | 2560   | 60.8%   |
| Malfunc  | 636       | 1086   | 30.07%  |
| Detected | 170       | 297    | 8.04%   |
| Failed   | 23        | 29     | 1.09%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1530      | 79.44%  |
| AMD                              | 263       | 13.66%  |
| Samsung Electronics              | 41        | 2.13%   |
| Nvidia                           | 19        | 0.99%   |
| SanDisk                          | 12        | 0.62%   |
| Kingston Technology Company      | 12        | 0.62%   |
| Toshiba America Info Systems     | 10        | 0.52%   |
| Solid State Storage Technology   | 7         | 0.36%   |
| VIA Technologies                 | 6         | 0.31%   |
| JMicron Technology               | 4         | 0.21%   |
| SK hynix                         | 3         | 0.16%   |
| Phison Electronics               | 3         | 0.16%   |
| KIOXIA                           | 3         | 0.16%   |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Silicon Image                    | 2         | 0.1%    |
| Micron Technology                | 2         | 0.1%    |
| Lite-On Technology               | 2         | 0.1%    |
| ADATA Technology                 | 2         | 0.1%    |
| Silicon Motion                   | 1         | 0.05%   |
| Realtek Semiconductor            | 1         | 0.05%   |
| O2 Micro                         | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 212       | 9.6%    |
| AMD FCH SATA Controller [AHCI mode]                                                    | 183       | 8.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                  | 157       | 7.11%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 143       | 6.47%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 118       | 5.34%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                         | 96        | 4.35%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 94        | 4.26%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 87        | 3.94%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                         | 84        | 3.8%    |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 79        | 3.58%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                     | 60        | 2.72%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                         | 53        | 2.4%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 51        | 2.31%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller       | 48        | 2.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]         | 45        | 2.04%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                 | 43        | 1.95%   |
| Intel 82801G (ICH7 Family) IDE Controller                                              | 34        | 1.54%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                     | 33        | 1.49%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 2 port SATA Controller [IDE mode]                   | 32        | 1.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                          | 32        | 1.45%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                         | 31        | 1.4%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 22        | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [IDE mode]                           | 21        | 0.95%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 20        | 0.91%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                          | 19        | 0.86%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                          | 19        | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                      | 18        | 0.81%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                 | 17        | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                          | 16        | 0.72%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 15        | 0.68%   |
| Intel Volume Management Device NVMe RAID Controller                                    | 14        | 0.63%   |
| Intel Mobile 4 Series Chipset PT IDER Controller                                       | 14        | 0.63%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 14        | 0.63%   |
| AMD FCH SATA Controller [IDE mode]                                                     | 14        | 0.63%   |
| Nvidia MCP79 AHCI Controller                                                           | 13        | 0.59%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                      | 13        | 0.59%   |
| Intel 7 Series Chipset Family 4-port SATA Controller [IDE mode]                        | 13        | 0.59%   |
| Intel 7 Series Chipset Family 2-port SATA Controller [IDE mode]                        | 13        | 0.59%   |
| Intel Mobile PM965/GM965 PT IDER Controller                                            | 10        | 0.45%   |
| Intel 6 Series/C200 Series Chipset Family Mobile SATA Controller (IDE mode, ports 0-3) | 10        | 0.45%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 1563      | 74.32%  |
| IDE  | 326       | 15.5%   |
| RAID | 114       | 5.42%   |
| NVMe | 100       | 4.76%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 1587      | 85.28%  |
| AMD          | 273       | 14.67%  |
| CentaurHauls | 1         | 0.05%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Notebooks | Percent |
|---------------------------------------------|-----------|---------|
| Intel Celeron CPU 1000M @ 1.80GHz           | 41        | 2.19%   |
| Intel Core i5-2520M CPU @ 2.50GHz           | 40        | 2.14%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 27        | 1.44%   |
| Intel Core i5 CPU M 520 @ 2.40GHz           | 24        | 1.28%   |
| Intel Core i3-5005U CPU @ 2.00GHz           | 23        | 1.23%   |
| Intel Core i3-6006U CPU @ 2.00GHz           | 22        | 1.18%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz        | 22        | 1.18%   |
| Intel Pentium Dual-Core CPU T4400 @ 2.20GHz | 21        | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz           | 21        | 1.12%   |
| Intel Celeron CPU N3060 @ 1.60GHz           | 21        | 1.12%   |
| Intel Celeron CPU N2840 @ 2.16GHz           | 19        | 1.02%   |
| Intel Core i5-5200U CPU @ 2.20GHz           | 18        | 0.96%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 18        | 0.96%   |
| Intel Core i3-7020U CPU @ 2.30GHz           | 17        | 0.91%   |
| Intel Atom CPU N455 @ 1.66GHz               | 17        | 0.91%   |
| Intel Core i7-4510U CPU @ 2.00GHz           | 16        | 0.86%   |
| Intel Core i5-4210U CPU @ 1.70GHz           | 16        | 0.86%   |
| Intel Core i5-3320M CPU @ 2.60GHz           | 16        | 0.86%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz        | 16        | 0.86%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz        | 16        | 0.86%   |
| Intel Atom CPU N450 @ 1.66GHz               | 16        | 0.86%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz | 15        | 0.8%    |
| Intel Core i3-3217U CPU @ 1.80GHz           | 15        | 0.8%    |
| Intel Core i3-2310M CPU @ 2.10GHz           | 15        | 0.8%    |
| Intel Core i3 CPU M 370 @ 2.40GHz           | 15        | 0.8%    |
| Intel Core i3 CPU M 350 @ 2.27GHz           | 15        | 0.8%    |
| AMD A10-5750M APU with Radeon HD Graphics   | 15        | 0.8%    |
| Intel Core i5-6200U CPU @ 2.30GHz           | 14        | 0.75%   |
| Intel Core i3-2350M CPU @ 2.30GHz           | 14        | 0.75%   |
| Intel Core i3 CPU M 380 @ 2.53GHz           | 14        | 0.75%   |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz        | 14        | 0.75%   |
| Intel Celeron CPU N3350 @ 1.10GHz           | 14        | 0.75%   |
| Intel Core i5-2540M CPU @ 2.60GHz           | 13        | 0.7%    |
| Intel Core i5 CPU M 560 @ 2.67GHz           | 13        | 0.7%    |
| Intel Core i5 CPU M 540 @ 2.53GHz           | 13        | 0.7%    |
| Intel Core 2 CPU T5500 @ 1.66GHz            | 13        | 0.7%    |
| Intel Atom CPU N270 @ 1.60GHz               | 13        | 0.7%    |
| Intel Pentium CPU B960 @ 2.20GHz            | 12        | 0.64%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 12        | 0.64%   |
| Intel Pentium CPU N3710 @ 1.60GHz           | 11        | 0.59%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                                | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Intel Core i5                        | 408       | 21.84%  |
| Intel Core i3                        | 237       | 12.69%  |
| Intel Celeron                        | 206       | 11.03%  |
| Intel Core 2 Duo                     | 196       | 10.49%  |
| Intel Core i7                        | 186       | 9.96%   |
| Intel Pentium                        | 96        | 5.14%   |
| Intel Atom                           | 76        | 4.07%   |
| Intel Pentium Dual-Core              | 55        | 2.94%   |
| AMD A4                               | 34        | 1.82%   |
| Intel Core 2                         | 32        | 1.71%   |
| AMD A8                               | 32        | 1.71%   |
| AMD A6                               | 27        | 1.45%   |
| AMD A10                              | 26        | 1.39%   |
| Other                                | 23        | 1.23%   |
| Intel Pentium Dual                   | 23        | 1.23%   |
| AMD E                                | 22        | 1.18%   |
| AMD E1                               | 21        | 1.12%   |
| AMD Ryzen 5                          | 17        | 0.91%   |
| AMD E2                               | 17        | 0.91%   |
| Intel Genuine                        | 14        | 0.75%   |
| Intel Celeron Dual-Core              | 13        | 0.7%    |
| Intel Celeron M                      | 10        | 0.54%   |
| Intel Pentium Silver                 | 8         | 0.43%   |
| Intel Pentium M                      | 7         | 0.37%   |
| Intel Core Duo                       | 7         | 0.37%   |
| AMD Turion 64 X2 Mobile              | 7         | 0.37%   |
| AMD C-60                             | 7         | 0.37%   |
| AMD Athlon II                        | 7         | 0.37%   |
| AMD C-50                             | 6         | 0.32%   |
| AMD Athlon II Dual-Core              | 6         | 0.32%   |
| AMD FX                               | 5         | 0.27%   |
| AMD Athlon X2                        | 4         | 0.21%   |
| AMD Mobile Sempron                   | 3         | 0.16%   |
| AMD C-70                             | 3         | 0.16%   |
| AMD A12                              | 3         | 0.16%   |
| Intel Core 2 Quad                    | 2         | 0.11%   |
| AMD V140                             | 2         | 0.11%   |
| AMD Turion X2 Ultra Dual-Core Mobile | 2         | 0.11%   |
| AMD Turion 64 Mobile                 | 2         | 0.11%   |
| AMD Ryzen 3                          | 2         | 0.11%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 1415      | 75.67%  |
| 4      | 281       | 15.03%  |
| 1      | 149       | 7.97%   |
| 6      | 22        | 1.18%   |
| 8      | 3         | 0.16%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 1861      | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 940       | 50.11%  |
| 1      | 936       | 49.89%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1812      | 97.26%  |
| 32-bit         | 45        | 2.42%   |
| Unknown        | 6         | 0.32%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x206a7    | 201       | 10.44%  |
| 0x306a9    | 190       | 9.87%   |
| 0x1067a    | 161       | 8.36%   |
| Unknown    | 142       | 7.38%   |
| 0x20655    | 116       | 6.03%   |
| 0x40651    | 80        | 4.16%   |
| 0x6fd      | 69        | 3.58%   |
| 0x306d4    | 61        | 3.17%   |
| 0x306c3    | 50        | 2.6%    |
| 0x406e3    | 49        | 2.55%   |
| 0x10676    | 48        | 2.49%   |
| 0x406c4    | 47        | 2.44%   |
| 0x806e9    | 44        | 2.29%   |
| 0x20652    | 43        | 2.23%   |
| 0x106ca    | 42        | 2.18%   |
| 0x30678    | 38        | 1.97%   |
| 0x05000119 | 36        | 1.87%   |
| 0x806ea    | 33        | 1.71%   |
| 0x07030105 | 32        | 1.66%   |
| 0x06001119 | 28        | 1.45%   |
| 0x0700010f | 21        | 1.09%   |
| 0x6f6      | 20        | 1.04%   |
| 0x406c3    | 19        | 0.99%   |
| 0x6fb      | 18        | 0.94%   |
| 0x506c9    | 18        | 0.94%   |
| 0x106c2    | 17        | 0.88%   |
| 0x906ea    | 16        | 0.83%   |
| 0x06006705 | 16        | 0.83%   |
| 0x706a1    | 15        | 0.78%   |
| 0x6f2      | 14        | 0.73%   |
| 0x506e3    | 13        | 0.68%   |
| 0x806ec    | 12        | 0.62%   |
| 0x10661    | 12        | 0.62%   |
| 0x05000029 | 12        | 0.62%   |
| 0x906e9    | 11        | 0.57%   |
| 0x806c1    | 10        | 0.52%   |
| 0x6ec      | 10        | 0.52%   |
| 0x30673    | 9         | 0.47%   |
| 0x06003106 | 9         | 0.47%   |
| 0x03000027 | 9         | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| Penryn          | 210       | 11.28%  |
| SandyBridge     | 201       | 10.8%   |
| IvyBridge       | 193       | 10.37%  |
| Westmere        | 161       | 8.65%   |
| Haswell         | 143       | 7.68%   |
| Core            | 141       | 7.58%   |
| KabyLake        | 133       | 7.15%   |
| Silvermont      | 115       | 6.18%   |
| Skylake         | 71        | 3.82%   |
| Broadwell       | 68        | 3.65%   |
| Bonnell         | 62        | 3.33%   |
| Bobcat          | 54        | 2.9%    |
| Puma            | 46        | 2.47%   |
| Piledriver      | 32        | 1.72%   |
| Excavator       | 32        | 1.72%   |
| P6              | 27        | 1.45%   |
| Jaguar          | 25        | 1.34%   |
| Goldmont        | 22        | 1.18%   |
| K10             | 18        | 0.97%   |
| Goldmont plus   | 18        | 0.97%   |
| K8 Hammer       | 16        | 0.86%   |
| TigerLake       | 14        | 0.75%   |
| Steamroller     | 11        | 0.59%   |
| K10 Llano       | 9         | 0.48%   |
| Zen+            | 7         | 0.38%   |
| Zen             | 7         | 0.38%   |
| K8 & K10 hybrid | 7         | 0.38%   |
| Zen 2           | 6         | 0.32%   |
| CometLake       | 4         | 0.21%   |
| Unknown         | 4         | 0.21%   |
| Nehalem         | 3         | 0.16%   |
| Zen 3           | 1         | 0.05%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1400      | 63.67%  |
| AMD                              | 413       | 18.78%  |
| Nvidia                           | 379       | 17.24%  |
| VIA Technologies                 | 6         | 0.27%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 3rd Gen Core processor Graphics Controller                                         | 185       | 7.77%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 183       | 7.69%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 156       | 6.55%   |
| Intel Core Processor Integrated Graphics Controller                                      | 112       | 4.7%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 88        | 3.7%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 68        | 2.86%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 67        | 2.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 67        | 2.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 61        | 2.56%   |
| Intel HD Graphics 5500                                                                   | 60        | 2.52%   |
| Intel HD Graphics 620                                                                    | 52        | 2.18%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 51        | 2.14%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 49        | 2.06%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 47        | 1.97%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 43        | 1.81%   |
| Intel Atom Processor D4xx/D5xx/N4xx/N5xx Integrated Graphics Controller                  | 43        | 1.81%   |
| AMD Mullins [Radeon R4/R5 Graphics]                                                      | 33        | 1.39%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 29        | 1.22%   |
| Intel UHD Graphics 620                                                                   | 28        | 1.18%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 25        | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 23        | 0.97%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 22        | 0.92%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 22        | 0.92%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 21        | 0.88%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 18        | 0.76%   |
| Intel HD Graphics 500                                                                    | 18        | 0.76%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 17        | 0.71%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 15        | 0.63%   |
| AMD Richland [Radeon HD 8650G]                                                           | 15        | 0.63%   |
| AMD RV710/M92 [Mobility Radeon HD 4530/4570/5145/530v/540v/545v]                         | 14        | 0.59%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 14        | 0.59%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 12        | 0.5%    |
| Nvidia GK107M [GeForce GT 750M]                                                          | 12        | 0.5%    |
| Intel HD Graphics 530                                                                    | 12        | 0.5%    |
| AMD Wrestler [Radeon HD 6310]                                                            | 11        | 0.46%   |
| Nvidia GM108M [GeForce 920MX]                                                            | 10        | 0.42%   |
| Nvidia G96CM [GeForce 9600M GT]                                                          | 10        | 0.42%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 10        | 0.42%   |
| AMD Wani [Radeon R5/R6/R7 Graphics]                                                      | 10        | 0.42%   |
| AMD Thames [Radeon HD 7500M/7600M Series]                                                | 10        | 0.42%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1070      | 57.4%   |
| 1 x AMD        | 283       | 15.18%  |
| Intel + Nvidia | 259       | 13.89%  |
| 1 x Nvidia     | 114       | 6.12%   |
| Intel + AMD    | 73        | 3.92%   |
| 2 x AMD        | 52        | 2.79%   |
| 1 x VIA        | 6         | 0.32%   |
| AMD + Nvidia   | 5         | 0.27%   |
| 2 x Nvidia     | 1         | 0.05%   |
| 1 x SiS        | 1         | 0.05%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 1841      | 98.71%  |
| Unknown     | 22        | 1.18%   |
| Proprietary | 2         | 0.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 1068      | 55.74%  |
| 0.01-0.5   | 389       | 20.3%   |
| 1.01-2.0   | 234       | 12.21%  |
| 0.51-1.0   | 163       | 8.51%   |
| 3.01-4.0   | 45        | 2.35%   |
| 5.01-6.0   | 10        | 0.52%   |
| 2.01-3.0   | 4         | 0.21%   |
| 7.01-8.0   | 3         | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 397       | 20.46%  |
| AU Optronics            | 368       | 18.97%  |
| Samsung Electronics     | 314       | 16.19%  |
| Chimei Innolux          | 216       | 11.13%  |
| BOE                     | 155       | 7.99%   |
| Chi Mei Optoelectronics | 123       | 6.34%   |
| Lenovo                  | 65        | 3.35%   |
| LG Philips              | 35        | 1.8%    |
| InfoVision              | 24        | 1.24%   |
| Apple                   | 21        | 1.08%   |
| Goldstar                | 20        | 1.03%   |
| Hewlett-Packard         | 17        | 0.88%   |
| CPT                     | 16        | 0.82%   |
| HannStar                | 14        | 0.72%   |
| PANDA                   | 12        | 0.62%   |
| Dell                    | 11        | 0.57%   |
| Philips                 | 10        | 0.52%   |
| Quanta Display          | 9         | 0.46%   |
| Vestel Elektronik       | 8         | 0.41%   |
| Toshiba                 | 8         | 0.41%   |
| InnoLux Display         | 8         | 0.41%   |
| BenQ                    | 8         | 0.41%   |
| Ancor Communications    | 8         | 0.41%   |
| Sony                    | 7         | 0.36%   |
| Sharp                   | 7         | 0.36%   |
| Acer                    | 6         | 0.31%   |
| Fujitsu Siemens         | 4         | 0.21%   |
| ASUSTek Computer        | 4         | 0.21%   |
| AOC                     | 4         | 0.21%   |
| Panasonic               | 3         | 0.15%   |
| IBM                     | 3         | 0.15%   |
| Hitachi                 | 3         | 0.15%   |
| Unknown                 | 2         | 0.1%    |
| SKY                     | 2         | 0.1%    |
| Plain Tree Systems      | 2         | 0.1%    |
| OEM                     | 2         | 0.1%    |
| NEC Computers           | 2         | 0.1%    |
| MiTAC                   | 2         | 0.1%    |
| Eizo                    | 2         | 0.1%    |
| CTV                     | 2         | 0.1%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Notebooks | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 47        | 2.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch     | 32        | 1.63%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 27        | 1.38%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 26        | 1.33%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 25        | 1.27%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 24        | 1.22%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 23        | 1.17%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 19        | 0.97%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 18        | 0.92%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 16        | 0.82%   |
| Chi Mei Optoelectronics LCD Monitor CMO1592 1366x768 344x193mm 15.5-inch | 15        | 0.76%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 13        | 0.66%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 13        | 0.66%   |
| BOE LCD Monitor BOE0675 1366x768 344x194mm 15.5-inch                     | 13        | 0.66%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                     | 12        | 0.61%   |
| AU Optronics LCD Monitor AUO10EC 1366x768 344x193mm 15.5-inch            | 12        | 0.61%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch          | 11        | 0.56%   |
| LG Display LCD Monitor LGD0365 1600x900 382x215mm 17.3-inch              | 10        | 0.51%   |
| Chimei Innolux LCD Monitor CMN1734 1600x900 382x214mm 17.2-inch          | 10        | 0.51%   |
| Chimei Innolux LCD Monitor CMN15BC 1366x768 344x194mm 15.5-inch          | 10        | 0.51%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 10        | 0.51%   |
| AU Optronics LCD Monitor AUO20EC 1366x768 344x193mm 15.5-inch            | 10        | 0.51%   |
| Samsung Electronics LCD Monitor SEC3046 1366x768 344x193mm 15.5-inch     | 9         | 0.46%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 9         | 0.46%   |
| Chimei Innolux LCD Monitor CMN1119 1366x768 256x144mm 11.6-inch          | 9         | 0.46%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 9         | 0.46%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 9         | 0.46%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 8         | 0.41%   |
| Samsung Electronics LCD Monitor SEC325A 1366x768 344x194mm 15.5-inch     | 8         | 0.41%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 8         | 0.41%   |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 8         | 0.41%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch              | 8         | 0.41%   |
| Lenovo LCD Monitor LEN4036 1440x900 303x190mm 14.1-inch                  | 8         | 0.41%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x190mm 14.1-inch                  | 8         | 0.41%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 8         | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch         | 8         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A1 1366x768 344x193mm 15.5-inch | 8         | 0.41%   |
| Chi Mei Optoelectronics LCD Monitor CMO1526 1280x800 331x207mm 15.4-inch | 8         | 0.41%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch     | 7         | 0.36%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 946       | 49.45%  |
| 1920x1080 (FHD)    | 369       | 19.29%  |
| 1280x800 (WXGA)    | 194       | 10.14%  |
| 1600x900 (HD+)     | 152       | 7.95%   |
| 1440x900 (WXGA+)   | 62        | 3.24%   |
| 1024x600           | 46        | 2.4%    |
| 3840x2160 (4K)     | 32        | 1.67%   |
| 1680x1050 (WSXGA+) | 26        | 1.36%   |
| 1920x1200 (WUXGA)  | 20        | 1.05%   |
| 1024x768 (XGA)     | 13        | 0.68%   |
| 1360x768           | 11        | 0.58%   |
| 1280x1024 (SXGA)   | 9         | 0.47%   |
| 2560x1440 (QHD)    | 5         | 0.26%   |
| 1920x540           | 5         | 0.26%   |
| 3840x1080          | 3         | 0.16%   |
| 2560x1080          | 3         | 0.16%   |
| 2288x1287          | 3         | 0.16%   |
| 1280x720 (HD)      | 3         | 0.16%   |
| 1680x945           | 2         | 0.1%    |
| 1280x768           | 2         | 0.1%    |
| 800x1280           | 1         | 0.05%   |
| 3840x2400          | 1         | 0.05%   |
| 3440x1440          | 1         | 0.05%   |
| 2560x1600          | 1         | 0.05%   |
| 2160x1440          | 1         | 0.05%   |
| 1400x1050          | 1         | 0.05%   |
| 1024x576           | 1         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 1108      | 56.7%   |
| 14      | 189       | 9.67%   |
| 17      | 149       | 7.63%   |
| 13      | 122       | 6.24%   |
| 12      | 63        | 3.22%   |
| 10      | 52        | 2.66%   |
| 11      | 50        | 2.56%   |
| 23      | 32        | 1.64%   |
| 21      | 27        | 1.38%   |
| 18      | 21        | 1.07%   |
| 27      | 20        | 1.02%   |
| 24      | 17        | 0.87%   |
| 20      | 13        | 0.67%   |
| 22      | 11        | 0.56%   |
| 84      | 9         | 0.46%   |
| 19      | 9         | 0.46%   |
| 31      | 8         | 0.41%   |
| 32      | 5         | 0.26%   |
| 8       | 5         | 0.26%   |
| Unknown | 5         | 0.26%   |
| 54      | 4         | 0.2%    |
| 16      | 4         | 0.2%    |
| 72      | 3         | 0.15%   |
| 65      | 3         | 0.15%   |
| 52      | 3         | 0.15%   |
| 48      | 3         | 0.15%   |
| 34      | 3         | 0.15%   |
| 142     | 2         | 0.1%    |
| 49      | 2         | 0.1%    |
| 40      | 2         | 0.1%    |
| 29      | 2         | 0.1%    |
| 25      | 2         | 0.1%    |
| 50      | 1         | 0.05%   |
| 39      | 1         | 0.05%   |
| 37      | 1         | 0.05%   |
| 26      | 1         | 0.05%   |
| 9       | 1         | 0.05%   |
| 7       | 1         | 0.05%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Notebooks | Percent |
|----------------|-----------|---------|
| 301-350        | 1310      | 67.46%  |
| 201-300        | 234       | 12.05%  |
| 351-400        | 196       | 10.09%  |
| 501-600        | 71        | 3.66%   |
| 401-500        | 66        | 3.4%    |
| 1001-1500      | 16        | 0.82%   |
| 1501-2000      | 12        | 0.62%   |
| 601-700        | 11        | 0.57%   |
| 701-800        | 8         | 0.41%   |
| 101-200        | 6         | 0.31%   |
| Unknown        | 5         | 0.26%   |
| 801-900        | 4         | 0.21%   |
| More than 2000 | 2         | 0.1%    |
| 1-100          | 1         | 0.05%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 1493      | 81.5%   |
| 16/10   | 295       | 16.1%   |
| 4/3     | 15        | 0.82%   |
| 5/4     | 9         | 0.49%   |
| 3/2     | 8         | 0.44%   |
| 21/9    | 4         | 0.22%   |
| 32/9    | 3         | 0.16%   |
| 1.00    | 2         | 0.11%   |
| 0.67    | 1         | 0.05%   |
| 0.62    | 1         | 0.05%   |
| Unknown | 1         | 0.05%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 1106      | 56.86%  |
| 81-90          | 255       | 13.11%  |
| 121-130        | 107       | 5.5%    |
| 201-250        | 68        | 3.5%    |
| 61-70          | 61        | 3.14%   |
| 71-80          | 53        | 2.72%   |
| 41-50          | 52        | 2.67%   |
| 51-60          | 50        | 2.57%   |
| 131-140        | 40        | 2.06%   |
| 151-200        | 28        | 1.44%   |
| More than 1000 | 25        | 1.29%   |
| 141-150        | 25        | 1.29%   |
| 301-350        | 21        | 1.08%   |
| 351-500        | 16        | 0.82%   |
| 251-300        | 11        | 0.57%   |
| 91-100         | 8         | 0.41%   |
| 1-40           | 7         | 0.36%   |
| 501-1000       | 7         | 0.36%   |
| Unknown        | 5         | 0.26%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 101-120       | 977       | 50.94%  |
| 121-160       | 461       | 24.04%  |
| 51-100        | 420       | 21.9%   |
| 161-240       | 31        | 1.62%   |
| 1-50          | 20        | 1.04%   |
| Unknown       | 5         | 0.26%   |
| More than 240 | 4         | 0.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 1734      | 90.6%   |
| 2     | 153       | 7.99%   |
| 3     | 11        | 0.57%   |
| 0     | 11        | 0.57%   |
| 4     | 5         | 0.26%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Notebooks | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 952       | 30.33%  |
| Intel                             | 766       | 24.4%   |
| Qualcomm Atheros                  | 647       | 20.61%  |
| Broadcom                          | 300       | 9.56%   |
| Ralink                            | 106       | 3.38%   |
| Broadcom Limited                  | 92        | 2.93%   |
| Marvell Technology Group          | 62        | 1.98%   |
| Dell                              | 18        | 0.57%   |
| Ralink Technology                 | 16        | 0.51%   |
| JMicron Technology                | 16        | 0.51%   |
| Huawei Technologies               | 15        | 0.48%   |
| Hewlett-Packard                   | 15        | 0.48%   |
| Ericsson Business Mobile Networks | 14        | 0.45%   |
| Nvidia                            | 13        | 0.41%   |
| Samsung Electronics               | 11        | 0.35%   |
| DisplayLink                       | 11        | 0.35%   |
| Sierra Wireless                   | 10        | 0.32%   |
| Xiaomi                            | 9         | 0.29%   |
| Attansic Technology               | 9         | 0.29%   |
| TP-Link                           | 6         | 0.19%   |
| Qualcomm Atheros Communications   | 6         | 0.19%   |
| VIA Technologies                  | 5         | 0.16%   |
| T & A Mobile Phones               | 4         | 0.13%   |
| MediaTek                          | 4         | 0.13%   |
| ASIX Electronics                  | 4         | 0.13%   |
| D-Link                            | 3         | 0.1%    |
| ASUSTek Computer                  | 3         | 0.1%    |
| Silicon Integrated Systems [SiS]  | 2         | 0.06%   |
| NetGear                           | 2         | 0.06%   |
| LG Electronics                    | 2         | 0.06%   |
| Belkin Components                 | 2         | 0.06%   |
| AMD                               | 2         | 0.06%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.03%   |
| Toshiba                           | 1         | 0.03%   |
| Spreadtrum Communications         | 1         | 0.03%   |
| Shenzhen Goodix Technology        | 1         | 0.03%   |
| OPPO Electronics                  | 1         | 0.03%   |
| Motorola PCS                      | 1         | 0.03%   |
| Micro Star International          | 1         | 0.03%   |
| ICS Advent                        | 1         | 0.03%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 548       | 14.54%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 325       | 8.62%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 150       | 3.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 122       | 3.24%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 99        | 2.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 2.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 78        | 2.07%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 76        | 2.02%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 1.91%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 72        | 1.91%   |
| Intel Wireless 7260                                                     | 70        | 1.86%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 1.86%   |
| Intel 82577LM Gigabit Network Connection                                | 58        | 1.54%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 1.51%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 1.35%   |
| Intel Centrino Advanced-N 6200                                          | 46        | 1.22%   |
| Intel 82567LM Gigabit Network Connection                                | 46        | 1.22%   |
| Intel Wireless 7265                                                     | 39        | 1.03%   |
| Intel Wireless 3165                                                     | 39        | 1.03%   |
| Intel Wireless 8265 / 8275                                              | 38        | 1.01%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 0.96%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 0.93%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 34        | 0.9%    |
| Intel Wireless 3160                                                     | 34        | 0.9%    |
| Intel WiFi Link 5100                                                    | 33        | 0.88%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 33        | 0.88%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 29        | 0.77%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 0.69%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 26        | 0.69%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 0.66%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 0.64%   |
| Intel Ethernet Connection I218-LM                                       | 24        | 0.64%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                    | 23        | 0.61%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 21        | 0.56%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 21        | 0.56%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 20        | 0.53%   |
| Intel 82566MM Gigabit Network Connection                                | 20        | 0.53%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 20        | 0.53%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 711       | 37.03%  |
| Qualcomm Atheros                | 570       | 29.69%  |
| Realtek Semiconductor           | 232       | 12.08%  |
| Broadcom                        | 193       | 10.05%  |
| Ralink                          | 106       | 5.52%   |
| Broadcom Limited                | 43        | 2.24%   |
| Ralink Technology               | 16        | 0.83%   |
| Sierra Wireless                 | 10        | 0.52%   |
| Dell                            | 10        | 0.52%   |
| TP-Link                         | 6         | 0.31%   |
| Qualcomm Atheros Communications | 6         | 0.31%   |
| Hewlett-Packard                 | 3         | 0.16%   |
| D-Link                          | 3         | 0.16%   |
| ASUSTek Computer                | 3         | 0.16%   |
| NetGear                         | 2         | 0.1%    |
| MediaTek                        | 2         | 0.1%    |
| Belkin Components               | 2         | 0.1%    |
| Micro Star International        | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 150       | 7.78%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 122       | 6.32%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 85        | 4.41%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 78        | 4.04%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 76        | 3.94%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 72        | 3.73%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                               | 72        | 3.73%   |
| Intel Wireless 7260                                                     | 70        | 3.63%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 70        | 3.63%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 57        | 2.95%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 51        | 2.64%   |
| Intel Centrino Advanced-N 6200                                          | 46        | 2.38%   |
| Intel Wireless 7265                                                     | 39        | 2.02%   |
| Intel Wireless 3165                                                     | 39        | 2.02%   |
| Intel Wireless 8265 / 8275                                              | 38        | 1.97%   |
| Intel Centrino Ultimate-N 6300                                          | 36        | 1.87%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 35        | 1.81%   |
| Intel Wireless 3160                                                     | 34        | 1.76%   |
| Intel WiFi Link 5100                                                    | 33        | 1.71%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 33        | 1.71%   |
| Broadcom BCM43142 802.11b/g/n                                           | 33        | 1.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 26        | 1.35%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 25        | 1.3%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 24        | 1.24%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 21        | 1.09%   |
| Broadcom Limited BCM4312 802.11b/g LP-PHY                               | 21        | 1.09%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 20        | 1.04%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 20        | 1.04%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 0.88%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 17        | 0.88%   |
| Intel Ultimate N WiFi Link 5300                                         | 17        | 0.88%   |
| Realtek RTL8191SEvB Wireless LAN Controller                             | 15        | 0.78%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 14        | 0.73%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 13        | 0.67%   |
| Intel Wi-Fi 6 AX201                                                     | 13        | 0.67%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 13        | 0.67%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                  | 13        | 0.67%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 12        | 0.62%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 12        | 0.62%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 12        | 0.62%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 903       | 50.53%  |
| Intel                            | 358       | 20.03%  |
| Qualcomm Atheros                 | 175       | 9.79%   |
| Broadcom                         | 135       | 7.55%   |
| Marvell Technology Group         | 62        | 3.47%   |
| Broadcom Limited                 | 50        | 2.8%    |
| JMicron Technology               | 16        | 0.9%    |
| Nvidia                           | 13        | 0.73%   |
| Huawei Technologies              | 11        | 0.62%   |
| DisplayLink                      | 11        | 0.62%   |
| Samsung Electronics              | 10        | 0.56%   |
| Xiaomi                           | 9         | 0.5%    |
| Attansic Technology              | 9         | 0.5%    |
| VIA Technologies                 | 5         | 0.28%   |
| T & A Mobile Phones              | 4         | 0.22%   |
| ASIX Electronics                 | 4         | 0.22%   |
| Silicon Integrated Systems [SiS] | 2         | 0.11%   |
| LG Electronics                   | 2         | 0.11%   |
| ZTE WCDMA Technologies MSM       | 1         | 0.06%   |
| Spreadtrum Communications        | 1         | 0.06%   |
| OPPO Electronics                 | 1         | 0.06%   |
| Motorola PCS                     | 1         | 0.06%   |
| MediaTek                         | 1         | 0.06%   |
| ICS Advent                       | 1         | 0.06%   |
| HMD Global                       | 1         | 0.06%   |
| Davicom Semiconductor            | 1         | 0.06%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 548       | 30.63%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 325       | 18.17%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 99        | 5.53%   |
| Intel 82577LM Gigabit Network Connection                               | 58        | 3.24%   |
| Intel 82567LM Gigabit Network Connection                               | 46        | 2.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 34        | 1.9%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 29        | 1.62%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 26        | 1.45%   |
| Intel Ethernet Connection I218-LM                                      | 24        | 1.34%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 23        | 1.29%   |
| Intel 82566MM Gigabit Network Connection                               | 20        | 1.12%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 17        | 0.95%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 17        | 0.95%   |
| Intel Ethernet Connection I217-LM                                      | 17        | 0.95%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 16        | 0.89%   |
| Broadcom Limited NetLink BCM5787M Gigabit Ethernet PCI Express         | 16        | 0.89%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 15        | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 14        | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 14        | 0.78%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 14        | 0.78%   |
| Broadcom BCM4401-B0 100Base-TX                                         | 14        | 0.78%   |
| Intel 82579V Gigabit Network Connection                                | 13        | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 12        | 0.67%   |
| Intel Ethernet Connection (4) I219-LM                                  | 12        | 0.67%   |
| Broadcom NetLink BCM5906M Fast Ethernet PCI Express                    | 12        | 0.67%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                        | 12        | 0.67%   |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 12        | 0.67%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                | 12        | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 11        | 0.61%   |
| DisplayLink USB3 to HDMI                                               | 11        | 0.61%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 10        | 0.56%   |
| Nvidia MCP79 Ethernet                                                  | 10        | 0.56%   |
| Intel Ethernet Connection (13) I219-V                                  | 10        | 0.56%   |
| Huawei VTR-L09                                                         | 10        | 0.56%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 10        | 0.56%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 9         | 0.5%    |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                             | 9         | 0.5%    |
| Attansic AR8152 v2.0 Fast Ethernet                                     | 9         | 0.5%    |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 8         | 0.45%   |
| Intel 82577LC Gigabit Network Connection                               | 8         | 0.45%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1834      | 50.59%  |
| Ethernet | 1740      | 48%     |
| Modem    | 49        | 1.35%   |
| Unknown  | 2         | 0.06%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 1478      | 72.59%  |
| Ethernet | 558       | 27.41%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 1687      | 90.36%  |
| 1     | 150       | 8.03%   |
| 0     | 26        | 1.39%   |
| 3     | 4         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 1662      | 84.67%  |
| Yes  | 301       | 15.33%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 339       | 25.41%  |
| Qualcomm Atheros Communications | 174       | 13.04%  |
| Broadcom                        | 151       | 11.32%  |
| Realtek Semiconductor           | 122       | 9.15%   |
| Dell                            | 83        | 6.22%   |
| Ralink                          | 72        | 5.4%    |
| Lite-On Technology              | 70        | 5.25%   |
| Foxconn / Hon Hai               | 68        | 5.1%    |
| Hewlett-Packard                 | 66        | 4.95%   |
| IMC Networks                    | 49        | 3.67%   |
| Toshiba                         | 36        | 2.7%    |
| Cambridge Silicon Radio         | 31        | 2.32%   |
| Apple                           | 19        | 1.42%   |
| ASUSTek Computer                | 11        | 0.82%   |
| Foxconn International           | 8         | 0.6%    |
| Askey Computer                  | 8         | 0.6%    |
| Ralink Technology               | 7         | 0.52%   |
| Alps Electric                   | 5         | 0.37%   |
| Chicony Electronics             | 4         | 0.3%    |
| Realtek                         | 3         | 0.22%   |
| Micro Star International        | 3         | 0.22%   |
| Taiyo Yuden                     | 2         | 0.15%   |
| MediaTek                        | 1         | 0.07%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Fujitsu                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 190       | 14.21%  |
| Ralink RT3290 Bluetooth                             | 72        | 5.39%   |
| Realtek Bluetooth Radio                             | 63        | 4.71%   |
| Qualcomm Atheros  Bluetooth Device                  | 59        | 4.41%   |
| Intel Bluetooth Device                              | 46        | 3.44%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 42        | 3.14%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 37        | 2.77%   |
| Dell DW375 Bluetooth Module                         | 37        | 2.77%   |
| HP Broadcom 2070 Bluetooth Combo                    | 33        | 2.47%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 32        | 2.39%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 31        | 2.32%   |
| Broadcom BCM2045B (BDC-2.1)                         | 30        | 2.24%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 2.09%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 25        | 1.87%   |
| Foxconn / Hon Hai Bluetooth Device                  | 24        | 1.8%    |
| Broadcom HP Portable SoftSailing                    | 23        | 1.72%   |
| Lite-On Atheros AR3012 Bluetooth                    | 21        | 1.57%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 21        | 1.57%   |
| Realtek RTL8821A Bluetooth                          | 20        | 1.5%    |
| Realtek RTL8723B Bluetooth                          | 20        | 1.5%    |
| IMC Networks Bluetooth Device                       | 20        | 1.5%    |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 19        | 1.42%   |
| Intel AX201 Bluetooth                               | 19        | 1.42%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]  | 17        | 1.27%   |
| Toshiba Bluetooth Device                            | 15        | 1.12%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 15        | 1.12%   |
| Dell BCM20702A0 Bluetooth Module                    | 14        | 1.05%   |
| Broadcom BCM2070 Bluetooth Device                   | 13        | 0.97%   |
| Lite-On Bluetooth Device                            | 12        | 0.9%    |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 0.9%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 12        | 0.9%    |
| Apple Bluetooth Host Controller                     | 12        | 0.9%    |
| Realtek  Bluetooth 4.2 Adapter                      | 11        | 0.82%   |
| Dell Wireless 365 Bluetooth                         | 11        | 0.82%   |
| IMC Networks Bluetooth Radio                        | 10        | 0.75%   |
| Foxconn / Hon Hai BCM20702A0                        | 10        | 0.75%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 9         | 0.67%   |
| Broadcom BCM43142A0 Bluetooth 4.0                   | 9         | 0.67%   |
| Broadcom BCM2045B (BDC-2) [Bluetooth Controller]    | 9         | 0.67%   |
| Foxconn International BCM43142A0 Bluetooth module   | 8         | 0.6%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1551      | 75.99%  |
| AMD                              | 324       | 15.87%  |
| Nvidia                           | 126       | 6.17%   |
| C-Media Electronics              | 10        | 0.49%   |
| Logitech                         | 7         | 0.34%   |
| VIA Technologies                 | 6         | 0.29%   |
| Creative Technology              | 6         | 0.29%   |
| Texas Instruments                | 2         | 0.1%    |
| Silicon Integrated Systems [SiS] | 2         | 0.1%    |
| Tenx Technology                  | 1         | 0.05%   |
| PreSonus Audio Electronics       | 1         | 0.05%   |
| Numark                           | 1         | 0.05%   |
| M-Audio                          | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Focusrite-Novation               | 1         | 0.05%   |
| ASUSTek Computer                 | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 235       | 9.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 196       | 7.87%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 164       | 6.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 159       | 6.39%   |
| AMD FCH Azalia Controller                                                                         | 145       | 5.83%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 140       | 5.62%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 112       | 4.5%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 101       | 4.06%   |
| Intel 8 Series HD Audio Controller                                                                | 91        | 3.66%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 90        | 3.62%   |
| AMD Kabini HDMI/DP Audio                                                                          | 81        | 3.25%   |
| Intel Broadwell-U Audio Controller                                                                | 68        | 2.73%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 67        | 2.69%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 63        | 2.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 55        | 2.21%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 52        | 2.09%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 46        | 1.85%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 46        | 1.85%   |
| AMD Wrestler HDMI Audio                                                                           | 46        | 1.85%   |
| AMD Trinity HDMI Audio Controller                                                                 | 32        | 1.29%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 32        | 1.29%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 22        | 0.88%   |
| AMD High Definition Audio Controller                                                              | 22        | 0.88%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 0.88%   |
| Intel Cannon Lake PCH cAVS                                                                        | 21        | 0.84%   |
| Nvidia High Definition Audio Controller                                                           | 19        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 18        | 0.72%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 17        | 0.68%   |
| Nvidia MCP79 High Definition Audio                                                                | 15        | 0.6%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 15        | 0.6%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 14        | 0.56%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 14        | 0.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 14        | 0.56%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 14        | 0.56%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 13        | 0.52%   |
| Intel CM238 HD Audio Controller                                                                   | 11        | 0.44%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 11        | 0.44%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 11        | 0.44%   |
| AMD Kaveri HDMI/DP Audio Controller                                                               | 11        | 0.44%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.4%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 603       | 27.08%  |
| SK hynix                     | 563       | 25.28%  |
| Unknown                      | 247       | 11.09%  |
| Kingston                     | 229       | 10.28%  |
| Micron Technology            | 187       | 8.4%    |
| Elpida                       | 84        | 3.77%   |
| Nanya Technology             | 71        | 3.19%   |
| Ramaxel Technology           | 57        | 2.56%   |
| A-DATA Technology            | 36        | 1.62%   |
| Crucial                      | 24        | 1.08%   |
| Corsair                      | 16        | 0.72%   |
| Kingmax                      | 15        | 0.67%   |
| ASint Technology             | 13        | 0.58%   |
| 48spaces                     | 11        | 0.49%   |
| Transcend                    | 10        | 0.45%   |
| Unknown (ABCD)               | 7         | 0.31%   |
| Qimonda                      | 7         | 0.31%   |
| Toshiba                      | 5         | 0.22%   |
| Kingmax Semiconductor        | 5         | 0.22%   |
| Apacer                       | 5         | 0.22%   |
| SHARETRONIC                  | 4         | 0.18%   |
| Patriot                      | 4         | 0.18%   |
| Melco                        | 2         | 0.09%   |
| Infineon                     | 2         | 0.09%   |
| CSX                          | 2         | 0.09%   |
| Axiom                        | 2         | 0.09%   |
| Unifosa                      | 1         | 0.04%   |
| Teikon                       | 1         | 0.04%   |
| Team                         | 1         | 0.04%   |
| Smart Brazil                 | 1         | 0.04%   |
| PUSKILL                      | 1         | 0.04%   |
| PNY                          | 1         | 0.04%   |
| Patriot Memory (PDP Systems) | 1         | 0.04%   |
| Memory Solution              | 1         | 0.04%   |
| Magnum Tech                  | 1         | 0.04%   |
| Hikvision                    | 1         | 0.04%   |
| GOODRAM                      | 1         | 0.04%   |
| Goldkey                      | 1         | 0.04%   |
| G.Skill                      | 1         | 0.04%   |
| Catalyst                     | 1         | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                     | Notebooks | Percent |
|-----------------------------------------------------------|-----------|---------|
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 55        | 2.3%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s     | 54        | 2.25%   |
| Unknown RAM Module 2048MB SODIMM DDR2 667MT/s             | 45        | 1.88%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s     | 41        | 1.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s     | 39        | 1.63%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s     | 37        | 1.54%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s    | 36        | 1.5%    |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s     | 31        | 1.29%   |
| SK hynix RAM HMT325S6CFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 25        | 1.04%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s     | 25        | 1.04%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s     | 25        | 1.04%   |
| Unknown RAM Module 2048MB SODIMM DDR2                     | 24        | 1%      |
| Samsung RAM M471B5673FH0-CF8 2GB SODIMM DDR3 1067MT/s     | 24        | 1%      |
| Samsung RAM M471B5273DH0-CK0 4096MB SODIMM DDR3 1600MT/s  | 24        | 1%      |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s    | 23        | 0.96%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s     | 23        | 0.96%   |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s  | 22        | 0.92%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s    | 21        | 0.88%   |
| Unknown RAM Module 1024MB SODIMM DDR2 667MT/s             | 20        | 0.83%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s     | 20        | 0.83%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 19        | 0.79%   |
| Unknown RAM Module 1024MB SODIMM DDR2                     | 18        | 0.75%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s     | 17        | 0.71%   |
| Unknown RAM Module 2048MB SODIMM 800MT/s                  | 15        | 0.63%   |
| SK hynix RAM HMT325S6EFR8A-PB 2048MB SODIMM DDR3 1600MT/s | 15        | 0.63%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s     | 15        | 0.63%   |
| SK hynix RAM HMT325S6BFR8C-H9 2GB SODIMM DDR3 1600MT/s    | 14        | 0.58%   |
| Samsung RAM M471B5273CH0-CK0 4096MB SODIMM DDR3 1600MT/s  | 14        | 0.58%   |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4GB SODIMM DDR3 1334MT/s     | 13        | 0.54%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s    | 12        | 0.5%    |
| SK hynix RAM HMT125S6BFR8C-G7 2GB SODIMM DDR3 1067MT/s    | 12        | 0.5%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s     | 12        | 0.5%    |
| Nanya RAM NT4GC64B8HB0NS-CG 4GB SODIMM DDR3 1334MT/s      | 12        | 0.5%    |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s      | 12        | 0.5%    |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s     | 12        | 0.5%    |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s            | 11        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s    | 11        | 0.46%   |
| SK hynix RAM HMT451S6AFR8A-PB 4096MB SODIMM DDR3 1600MT/s | 11        | 0.46%   |
| Samsung RAM M471B5673EH1-CF8 2048MB SODIMM DDR3 4199MT/s  | 11        | 0.46%   |
| Ramaxel RAM RMT3170ME68F9F1600 4GB SODIMM DDR3 1600MT/s   | 11        | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR3    | 1130      | 60.04%  |
| DDR2    | 274       | 14.56%  |
| DDR4    | 266       | 14.13%  |
| SDRAM   | 106       | 5.63%   |
| Unknown | 34        | 1.81%   |
| LPDDR4  | 33        | 1.75%   |
| DDR     | 24        | 1.28%   |
| DRAM    | 8         | 0.43%   |
| LPDDR3  | 6         | 0.32%   |
| LPDDR5  | 1         | 0.05%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 1783      | 98.07%  |
| DIMM         | 14        | 0.77%   |
| Row Of Chips | 13        | 0.72%   |
| Chip         | 7         | 0.39%   |
| Unknown      | 1         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size    | Notebooks | Percent |
|---------|-----------|---------|
| 4096    | 879       | 42.02%  |
| 2048    | 602       | 28.78%  |
| 8192    | 354       | 16.92%  |
| 1024    | 183       | 8.75%   |
| 16384   | 39        | 1.86%   |
| 512     | 26        | 1.24%   |
| 32768   | 7         | 0.33%   |
| Unknown | 2         | 0.1%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 1600    | 748       | 36.08%  |
| 1334    | 232       | 11.19%  |
| 667     | 164       | 7.91%   |
| 2667    | 155       | 7.48%   |
| 1333    | 124       | 5.98%   |
| 1067    | 93        | 4.49%   |
| 2400    | 83        | 4%      |
| Unknown | 72        | 3.47%   |
| 800     | 69        | 3.33%   |
| 4199    | 56        | 2.7%    |
| 3200    | 43        | 2.07%   |
| 2048    | 41        | 1.98%   |
| 533     | 34        | 1.64%   |
| 2133    | 31        | 1.5%    |
| 975     | 31        | 1.5%    |
| 3266    | 23        | 1.11%   |
| 1066    | 23        | 1.11%   |
| 333     | 14        | 0.68%   |
| 1867    | 10        | 0.48%   |
| 1639    | 9         | 0.43%   |
| 1776    | 3         | 0.14%   |
| 8400    | 2         | 0.1%    |
| 4266    | 2         | 0.1%    |
| 2267    | 2         | 0.1%    |
| 400     | 2         | 0.1%    |
| 3733    | 1         | 0.05%   |
| 2134    | 1         | 0.05%   |
| 1866    | 1         | 0.05%   |
| 1400    | 1         | 0.05%   |
| 1200    | 1         | 0.05%   |
| 266     | 1         | 0.05%   |
| 200     | 1         | 0.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 11        | 52.38%  |
| Canon                 | 3         | 14.29%  |
| Samsung Electronics   | 2         | 9.52%   |
| Brother Industries    | 2         | 9.52%   |
| Seiko Epson           | 1         | 4.76%   |
| Oki Data              | 1         | 4.76%   |
| Lexmark International | 1         | 4.76%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                   | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Officejet J4500 series               | 2         | 9.52%   |
| HP DeskJet 2130 series                  | 2         | 9.52%   |
| Seiko Epson XP-240 Series               | 1         | 4.76%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 4.76%   |
| Samsung Composite Device                | 1         | 4.76%   |
| Oki Data USB Device                     | 1         | 4.76%   |
| Lexmark International Lexmark X203n     | 1         | 4.76%   |
| HP LaserJet P1102                       | 1         | 4.76%   |
| HP LaserJet 1022                        | 1         | 4.76%   |
| HP LaserJet 1020                        | 1         | 4.76%   |
| HP ENVY 4520 series                     | 1         | 4.76%   |
| HP DeskJet 5550                         | 1         | 4.76%   |
| HP DeskJet 3630 series                  | 1         | 4.76%   |
| HP Deskjet 1510                         | 1         | 4.76%   |
| Canon TS5100 series                     | 1         | 4.76%   |
| Canon PIXMA MG2500 Series               | 1         | 4.76%   |
| Canon CAPT USB Device                   | 1         | 4.76%   |
| Brother HL-1110 series                  | 1         | 4.76%   |
| Brother DCP-1610W                       | 1         | 4.76%   |

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


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Canon CanoScan LiDE 120 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 436       | 28.09%  |
| Realtek Semiconductor                  | 136       | 8.76%   |
| IMC Networks                           | 132       | 8.51%   |
| Microdia                               | 119       | 7.67%   |
| Suyin                                  | 109       | 7.02%   |
| Sunplus Innovation Technology          | 102       | 6.57%   |
| Cheng Uei Precision Industry (Foxlink) | 62        | 3.99%   |
| Syntek                                 | 53        | 3.41%   |
| Acer                                   | 49        | 3.16%   |
| Bison Electronics                      | 44        | 2.84%   |
| Quanta                                 | 36        | 2.32%   |
| Silicon Motion                         | 34        | 2.19%   |
| Lite-On Technology                     | 32        | 2.06%   |
| Alcor Micro                            | 26        | 1.68%   |
| Lenovo                                 | 24        | 1.55%   |
| Ricoh                                  | 23        | 1.48%   |
| Primax Electronics                     | 22        | 1.42%   |
| Apple                                  | 17        | 1.1%    |
| ALi                                    | 16        | 1.03%   |
| Z-Star Microelectronics                | 12        | 0.77%   |
| OmniVision Technologies                | 11        | 0.71%   |
| Importek                               | 10        | 0.64%   |
| Logitech                               | 6         | 0.39%   |
| DigiTech                               | 6         | 0.39%   |
| Samsung Electronics                    | 5         | 0.32%   |
| KYE Systems (Mouse Systems)            | 5         | 0.32%   |
| Genesys Logic                          | 4         | 0.26%   |
| Trust                                  | 2         | 0.13%   |
| SHENZHEN EMEET TECHNOLOGY              | 2         | 0.13%   |
| Nebraska Furniture Mart                | 2         | 0.13%   |
| Luxvisions Innotech Limited            | 2         | 0.13%   |
| Intel                                  | 2         | 0.13%   |
| GEMBIRD                                | 2         | 0.13%   |
| Xiaomi                                 | 1         | 0.06%   |
| Sunplus Technology                     | 1         | 0.06%   |
| Spreadtrum Communications              | 1         | 0.06%   |
| Hewlett-Packard                        | 1         | 0.06%   |
| Google                                 | 1         | 0.06%   |
| Generalplus Technology                 | 1         | 0.06%   |
| Cubeternet                             | 1         | 0.06%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Notebooks | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony HP Truevision HD                                | 39        | 2.51%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 35        | 2.25%   |
| Chicony HD WebCam                                       | 32        | 2.06%   |
| Realtek USB Camera                                      | 28        | 1.8%    |
| Chicony USB2.0 VGA UVC WebCam                           | 25        | 1.61%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 24        | 1.55%   |
| Sunplus HP Truevision HD                                | 24        | 1.55%   |
| Chicony Integrated Camera                               | 24        | 1.55%   |
| Acer Lenovo EasyCamera                                  | 22        | 1.42%   |
| Microdia Integrated Webcam                              | 20        | 1.29%   |
| Chicony USB2.0 HD UVC WebCam                            | 20        | 1.29%   |
| Chicony FJ Camera                                       | 20        | 1.29%   |
| Sunplus Integrated_Webcam_HD                            | 18        | 1.16%   |
| Sunplus HD WebCam                                       | 18        | 1.16%   |
| IMC Networks EasyCamera                                 | 18        | 1.16%   |
| Chicony Lenovo EasyCamera                               | 18        | 1.16%   |
| Syntek EasyCamera                                       | 17        | 1.09%   |
| Realtek Lenovo EasyCamera                               | 17        | 1.09%   |
| IMC Networks USB2.0 HD UVC WebCam                       | 17        | 1.09%   |
| Primax HP HD Webcam [Fixed]                             | 16        | 1.03%   |
| Chicony EasyCamera                                      | 15        | 0.97%   |
| Chicony 2.0M UVC Webcam / CNF7129                       | 15        | 0.97%   |
| Realtek Integrated Webcam HD                            | 14        | 0.9%    |
| Microdia Integrated_Webcam_HD                           | 14        | 0.9%    |
| Lite-On HP HD Webcam                                    | 14        | 0.9%    |
| Cheng Uei Precision Industry (Foxlink) HP Truevision HD | 14        | 0.9%    |
| Realtek Integrated Webcam                               | 13        | 0.84%   |
| Chicony VGA WebCam                                      | 13        | 0.84%   |
| Chicony TOSHIBA Web Camera - HD                         | 13        | 0.84%   |
| Bison Lenovo EasyCamera                                 | 13        | 0.84%   |
| ALi Gateway Webcam                                      | 13        | 0.84%   |
| Syntek Integrated Camera                                | 12        | 0.77%   |
| Realtek USB2.0 VGA UVC WebCam                           | 12        | 0.77%   |
| Quanta VGA Webcam                                       | 12        | 0.77%   |
| Chicony Integrated HP HD Webcam                         | 12        | 0.77%   |
| Suyin HD WebCam                                         | 11        | 0.71%   |
| Silicon Motion WebCam SC-0311139N                       | 11        | 0.71%   |
| OmniVision OV2640 Webcam                                | 11        | 0.71%   |
| Lenovo Integrated Webcam [R5U877]                       | 11        | 0.71%   |
| IMC Networks UVC VGA Webcam                             | 11        | 0.71%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 74        | 41.34%  |
| AuthenTec                  | 57        | 31.84%  |
| Upek                       | 20        | 11.17%  |
| LighTuning Technology      | 12        | 6.7%    |
| STMicroelectronics         | 9         | 5.03%   |
| Synaptics                  | 4         | 2.23%   |
| Elan Microelectronics      | 2         | 1.12%   |
| Shenzhen Goodix Technology | 1         | 0.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AuthenTec AES2810                                                          | 23        | 12.85%  |
| AuthenTec AES2501 Fingerprint Sensor                                       | 20        | 11.17%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 19        | 10.61%  |
| Validity Sensors VFS491                                                    | 13        | 7.26%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 11        | 6.15%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 9         | 5.03%   |
| STMicroelectronics Fingerprint Reader                                      | 9         | 5.03%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 8         | 4.47%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 4.47%   |
| LighTuning Fingerprint Reader                                              | 8         | 4.47%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 4.47%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 3.35%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 5         | 2.79%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.23%   |
| AuthenTec AES1600                                                          | 4         | 2.23%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.68%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 1.12%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 1.12%   |
| Synaptics  WBDI                                                            | 2         | 1.12%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 2         | 1.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 2         | 1.12%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.12%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 0.56%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 0.56%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.56%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 0.56%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 1         | 0.56%   |
| Shenzhen Goodix  FingerPrint Device                                        | 1         | 0.56%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 1         | 0.56%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 81        | 56.25%  |
| O2 Micro              | 27        | 18.75%  |
| Lenovo                | 19        | 13.19%  |
| Alcor Micro           | 11        | 7.64%   |
| Upek                  | 5         | 3.47%   |
| Gemalto (was Gemplus) | 1         | 0.69%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 60        | 41.67%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 16.67%  |
| Lenovo Integrated Smart Card Reader                                          | 19        | 13.19%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 15        | 10.42%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 11        | 7.64%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 5         | 3.47%   |
| Broadcom 5880                                                                | 4         | 2.78%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 2.08%   |
| Broadcom 58200                                                               | 2         | 1.39%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 1         | 0.69%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 1302      | 67.92%  |
| 1     | 513       | 26.76%  |
| 2     | 89        | 4.64%   |
| 3     | 9         | 0.47%   |
| 10    | 1         | 0.05%   |
| 9     | 1         | 0.05%   |
| 5     | 1         | 0.05%   |
| 4     | 1         | 0.05%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 179       | 25.39%  |
| Chipcard                 | 144       | 20.43%  |
| Graphics card            | 138       | 19.57%  |
| Bluetooth                | 75        | 10.64%  |
| Net/wireless             | 59        | 8.37%   |
| Storage                  | 38        | 5.39%   |
| Multimedia controller    | 20        | 2.84%   |
| Flash memory             | 17        | 2.41%   |
| Communication controller | 15        | 2.13%   |
| Camera                   | 8         | 1.13%   |
| Sound                    | 4         | 0.57%   |
| Storage/ata              | 2         | 0.28%   |
| Net/ethernet             | 2         | 0.28%   |
| Card reader              | 2         | 0.28%   |
| Storage/raid             | 1         | 0.14%   |
| Network                  | 1         | 0.14%   |


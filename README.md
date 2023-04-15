# Overdyuu
-----
Repo for PC configs

## ToDo list
- [] Install & configure rEFInd
- [x] Create a GIT repo for configs
- [x] Upload configs and documentation to repo
- [] Search for 'Linux configuration best practices'
- [] Implement chosen practices if there're any

## Specs:
1. **`CPU`**: Intel Core i7-13700K
2. **`GPU`**: Inno3D GeForce RTX 3080X4
3. **`RAM`**: G.Skill Trident Z5 6000MHz CL32 2x32GB
4. **`MOBO`**: Asus Prime Z790-A WiFi
5. **`CASE`**: Fractal Torrent White
6. **`STORAGE`**:
   1.**`SSD #1`**: WD SN770 1TB
   2.**`SSD #2`**: WD SN770 2TB
7. **`PSU`**: Corsair HX1200
8. **`CPU COOLER`**: Noctua NH-U12A



## Partitioning:
`/dev/nvme0n1p1 EFI 3GiB`
`/dev/nvme0n1p2 XFS 928GiB`

## Ricing:
https://github.com/ibrahimbutt/direwolf-arch-rice

## List of packages:
### Core:
* base
* linux
* linux-firmware
* sof-firmware
* archlinux-keyring
* intel-ucode
* refind
* sudo

### Tools:
* vim
* gptfdisk
* util-linux-libs
* git
* openssh
* htop
* btop

### Networking:
* tcpdump
* networkmanager
* iw
* iwd
* ethtool

### Documentation:
* man-db
* man-pages
* texinfo

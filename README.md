# minecraft-installer
Unofficial minecraft java edition installer made for all Linux distributions

## How to run installer?
### Prerequisites
It requires ```wget``` and ```tar``` to be already installed on your system.

MINECRAFT BINARY HAS ITS OWN DEPENDENCIES AND THIS INSTALLER DOESN'T INSTALL THEM!!!

### Instalation
1. Open your terminal and type:
```
git clone https://github.com/captainjo99/minecraft-installer.git
```
2. Navigate inside directory
```
cd minecraft-installer
```
3. Make installer script executable
```
cdmod +rx minecraft-installer
```
4. Run the script
```
./minecraft-installer
```
You have installed Minecraft to your system.Pre-Depends: dpkg (>= 1.14.0), wget | curl, ca-certificates
Open it your application menu and enjoy.

## References
[Icon](https://icon-icons.com/icon/minecraft-logo/168974) by [VectorLogoZone](https://icon-icons.com/users/DmkIGLRdReSCIBJ7pItgP/icon-sets/)

## Minecraft binary dependecies extracted from debian package
```
Pre-Depends: dpkg (>= 1.14.0), wget | curl, ca-certificates
Depends: default-jre, libasound2 (>= 1.0.23), libatk-bridge2.0-0 (>= 2.5.3), libatk1.0-0 (>= 2.2.0), libatspi2.0-0 (>= 2.9.90), libc6 (>= 2.16), libcairo2 (>= 1.6.0), libcups2 (>= 1.4.0), libdbus-1-3 (>= 1.5.12), libdrm2 (>= 2.4.38), libexpat1 (>= 2.0.1), libgbm1 (>= 8.1~0), libfontconfig1 (>= 2.8.0), libgcc1 (>= 1:4.1.1), libgdk-pixbuf2.0-0 (>= 2.22.0), libglib2.0-0 (>= 2.39.4), libgtk-3-0 (>= 3.18.9), libnspr4 (>= 2:4.9-2~), libnss3 (>= 2:3.22), libpango1.0-0 (>= 1.14.0) | libpango-1.0-0 (>= 1.14.0), libpangocairo-1.0-0 (>= 1.14.0), libstdc++6 (>= 4.8.0), libx11-6 (>= 2:1.4.99.1), libxcomposite1 (>= 1:0.3-1), libxcursor1 (>> 1.1.2), libxdamage1 (>= 1:1.1), libxext6, libxfixes3, libxi6 (>= 2:1.2.99.4), libxrandr2 (>= 2:1.2.99.3), libxrender1, libxss1, libxtst6, libx11-xcb1, libxcb-dri3-0, libxcb1 (>= 1.9.2), libbz2-1.0, lsb-base (>= 4.1), xdg-utils (>= 1.0.2), wget, libcurl3 | libcurl4, libuuid1
```

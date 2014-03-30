
Download
==========

2014-3-29

Fedora packages
    wget -r -np -- http://spot.fedorapeople.org/steam/fedora-19/
    wget -r -np  http://spot.fedorapeople.org/steam/steam.repo

Steam speced package
    wget http://repo.steampowered.com/steam/archive/precise/steam_1.0.0.39.tar.gz


Tree
======

    ├── README.md
    └── spot.fedorapeople.org
        └── steam
            ├── fedora-19
            │   ├── drpms
            │   │   ├── index.html
            │   │   ├── index.html?C=M;O=A
            │   │   ├── index.html?C=M;O=D
            │   │   ├── index.html?C=N;O=A
            │   │   ├── index.html?C=N;O=D
            │   │   ├── index.html?C=S;O=A
            │   │   ├── index.html?C=S;O=D
            │   │   ├── SDL2-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.i686.drpm
            │   │   ├── SDL2-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.src.drpm
            │   │   ├── SDL2-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.x86_64.drpm
            │   │   ├── SDL2-debuginfo-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.i686.drpm
            │   │   ├── SDL2-devel-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.i686.drpm
            │   │   ├── SDL2-devel-2.0-0.1.20121107hg6659.fc19_2.0-0.2.20130412hg7062.fc19.x86_64.drpm
            │   │   ├── steam-1.0.0.34-1.fc19_1.0.0.36-1.fc19.i686.drpm
            │   │   ├── steam-1.0.0.34-1.fc19_1.0.0.36-1.fc19.src.drpm
            │   │   ├── steam-1.0.0.36-1.fc19_1.0.0.39-1.fc19.i686.drpm
            │   │   └── steam-1.0.0.36-1.fc19_1.0.0.39-1.fc19.src.drpm
            │   ├── index.html
            │   ├── index.html?C=M;O=A
            │   ├── index.html?C=M;O=D
            │   ├── index.html?C=N;O=A
            │   ├── index.html?C=N;O=D
            │   ├── index.html?C=S;O=A
            │   ├── index.html?C=S;O=D
            │   ├── repodata
            │   │   ├── 52741e070db97c6420998825ac77aa2d4b03c51660d1007d5b617338e6366f69-prestodelta.xml.gz
            │   │   ├── 5ea26e117b6ffc9392f4254d3034505a9437bf97f53a7568e715d11f82b2f4df-other.xml.gz
            │   │   ├── b079338dab13290c1635f3a642c2153da223a05666c963bf74c98247fb779e47-primary.sqlite.bz2
            │   │   ├── d12597f24140c561a4bde20f8a523f26c94f69cc0d81e1a194412256fafcff78-primary.xml.gz
            │   │   ├── d97734d66a9d05d8373cd4cbabc818d729867d19782f456d1a7b23f0cd967d17-prestodelta.xml.gz
            │   │   ├── da4a881c134578278585e288c0754e46ab1cadbe94e5331797fc9ce4f3fe6f26-filelists.sqlite.bz2
            │   │   ├── db75dce2570430d5c01dbc0f52b8d763f87e1c65098a46bc5ce4754a6fd63aba-filelists.xml.gz
            │   │   ├── f67519ffee83506c715d38607f306975b078d57859b2f2fbf45e044c3f968fc7-other.sqlite.bz2
            │   │   ├── f68b0612bdb3bea5e951c2d3a65f2f59ea894fe2ced760229b52c4206268b8f7-prestodelta.xml.gz
            │   │   ├── index.html
            │   │   ├── index.html?C=M;O=A
            │   │   ├── index.html?C=M;O=D
            │   │   ├── index.html?C=N;O=A
            │   │   ├── index.html?C=N;O=D
            │   │   ├── index.html?C=S;O=A
            │   │   ├── index.html?C=S;O=D
            │   │   └── repomd.xml
            │   ├── SDL2-2.0-0.2.20130412hg7062.fc19.i686.rpm
            │   ├── SDL2-2.0-0.2.20130412hg7062.fc19.src.rpm
            │   ├── SDL2-2.0-0.2.20130412hg7062.fc19.x86_64.rpm
            │   ├── SDL2-debuginfo-2.0-0.2.20130412hg7062.fc19.i686.rpm
            │   ├── SDL2-debuginfo-2.0-0.2.20130412hg7062.fc19.x86_64.rpm
            │   ├── SDL2-devel-2.0-0.2.20130412hg7062.fc19.i686.rpm
            │   ├── SDL2-devel-2.0-0.2.20130412hg7062.fc19.x86_64.rpm
            │   ├── steam-1.0.0.39-1.fc19.i686.rpm
            │   └── steam-1.0.0.39-1.fc19.src.rpm
            └── steam.repo
    5 directories, 52 files


Extract
=========

rpm2cpio steam-1.0.0.39-1.fc19.src.rpm | cpio -dium


    ├── [           ]  rpm-extract/
    │   ├── [       2427]  steam-1.0.0.34-fedora.patch
    │   ├── [       4266]  steam-1.0.0.34-fedora-rpmnames.patch
    │   ├── [       5110]  steam-1.0.0.34-fedora-steamdeps.patch
    │   ├── [    2521856]  steam_1.0.0.39.tar.gz
    │   ├── [       6475]  steam.spec
    │   └── [           ]  tgz-extract/
    │       └── [           ]  steam/
    │           ├── [    2426032]  bootstraplinux_ubuntu12_32.tar.xz
    │           ├── [        623]  check_version.sh*
    │           ├── [         27]  COPYING -> steam_install_agreement.txt
    │           ├── [           ]  debian/
    │           │   ├── [      10114]  changelog
    │           │   ├── [          2]  compat
    │           │   ├── [       1118]  control
    │           │   ├── [        225]  copyright
    │           │   ├── [         85]  rules*
    │           │   ├── [           ]  source/
    │           │   │   └── [         13]  format
    │           │   ├── [          0]  steam.install
    │           │   ├── [         33]  steam-launcher.install
    │           │   ├── [          8]  steam-launcher.manpages
    │           │   └── [        625]  steam-launcher.postinst
    │           ├── [           ]  icons/
    │           │   ├── [           ]  16/
    │           │   │   └── [        626]  steam.png
    │           │   ├── [           ]  24/
    │           │   │   └── [       1397]  steam.png
    │           │   ├── [           ]  256/
    │           │   │   └── [      64657]  steam.png
    │           │   ├── [           ]  32/
    │           │   │   └── [       2022]  steam.png
    │           │   └── [           ]  48/
    │           │       ├── [       4527]  steam.png
    │           │       └── [       2013]  steam_tray_mono.png
    │           ├── [           ]  lib/
    │           │   └── [           ]  udev/
    │           │       └── [           ]  rules.d/
    │           │           └── [         94]  99-steam-controller-perms.rules
    │           ├── [       5020]  Makefile*
    │           ├── [        325]  README
    │           ├── [       5390]  steam*
    │           ├── [        438]  steam.6
    │           ├── [      10541]  steamdeps*
    │           ├── [       2191]  steam.desktop
    │           ├── [       8822]  steam_install_agreement.txt
    │           ├── [       2641]  steam-key.asc
    │           ├── [        112]  steam.list
    │           └── [           ]  xz-extract/
    │               ├── [           ]  linux32/
    │               │   └── [     264574]  steamerrorreporter*
    │               ├── [        840]  steamdeps.txt
    │               ├── [       8822]  steam_install_agreement.txt
    │               ├── [      21206]  steam.sh*
    │               └── [           ]  ubuntu12_32/
    │                   ├── [     693253]  crashhandler.so*
    │                   ├── [    5543712]  steam*
    │                   └── [           ]  steam-runtime/
    │                       ├── [           ]  common-licenses/
    │                       │   ├── [      11358]  Apache-2.0
    │                       │   ├── [       6111]  Artistic
    │                       │   ├── [       1499]  BSD
    │                       │   ├── [          8]  GFDL -> GFDL-1.3
    │                       │   ├── [      20431]  GFDL-1.2
    │                       │   ├── [      22962]  GFDL-1.3
    │                       │   ├── [          5]  GPL -> GPL-3
    │                       │   ├── [      12632]  GPL-1
    │                       │   ├── [      18092]  GPL-2
    │                       │   ├── [      35147]  GPL-3
    │                       │   ├── [          6]  LGPL -> LGPL-3
    │                       │   ├── [      25383]  LGPL-2
    │                       │   ├── [      26530]  LGPL-2.1
    │                       │   └── [       7651]  LGPL-3
    │                       ├── [         10]  COPYING -> README.txt
    │                       ├── [           ]  i386/
    │                       │   ├── [           ]  lib/
    │                       │   │   └── [           ]  i386-linux-gnu/
    │                       │   │       └── [     116232]  libgcc_s.so.1
    │                       │   └── [           ]  usr/
    │                       │       ├── [           ]  lib/
    │                       │       │   ├── [           ]  gcc/
    │                       │       │   │   └── [           ]  i686-linux-gnu/
    │                       │       │   │       └── [          3]  4.6.3 -> 4.6
    │                       │       │   └── [           ]  i386-linux-gnu/
    │                       │       │       ├── [         19]  libstdc++.so.6 -> libstdc++.so.6.0.16
    │                       │       │       ├── [     905712]  libstdc++.so.6.0.16
    │                       │       │       ├── [         15]  libX11.so.6 -> libX11.so.6.3.0
    │                       │       │       ├── [    1254264]  libX11.so.6.3.0
    │                       │       │       ├── [         15]  libXau.so.6 -> libXau.so.6.0.0
    │                       │       │       ├── [       9588]  libXau.so.6.0.0
    │                       │       │       ├── [         15]  libxcb.so.1 -> libxcb.so.1.1.0
    │                       │       │       ├── [     132660]  libxcb.so.1.1.0
    │                       │       │       ├── [         17]  libXdmcp.so.6 -> libXdmcp.so.6.0.0
    │                       │       │       └── [      21824]  libXdmcp.so.6.0.0
    │                       │       └── [           ]  share/
    │                       │           └── [           ]  doc/
    │                       │               ├── [           ]  gcc-4.6-base/
    │                       │               │   └── [      25503]  copyright
    │                       │               ├── [           ]  libgcc1 -> gcc-4.6-base/
    │                       │               ├── [           ]  libstdc++6 -> gcc-4.6-base/
    │                       │               ├── [           ]  libx11-6/
    │                       │               │   └── [      47104]  copyright
    │                       │               ├── [           ]  libxau6/
    │                       │               │   └── [       1223]  copyright
    │                       │               ├── [           ]  libxcb1/
    │                       │               │   └── [       1780]  copyright
    │                       │               └── [           ]  libxdmcp6/
    │                       │                   └── [       1265]  copyright
    │                       └── [       1629]  README.txt
    └── [    2533154]  steam-1.0.0.39-1.fc19.src.rpm
    
    36 directories, 74 files



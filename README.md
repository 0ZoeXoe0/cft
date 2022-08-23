# CARA INSTALL

1. apt update
2. apt  upgrade          (Y trus N,N,N)
3. apt install git
4. apt install wget
5. git clone https://github.com/0ZoeXoe0/cft.git
6. cd cft && bash install.sh
7. cd

# INSTALL METACORE

1. LINK CORE META CONTOHNYA
   wget https://github.com/MetaCubeX/Clash.Meta/releases/download/v1.10.0/Clash.Meta-android-arm64-v1.10.0.gz
2. NAMA CORE META YANG LU DOWNLOAD
   gunzip Clash.Meta-android-arm64-v1.10.0.gz
3. mv Clash.Meta-android-arm64-v1.10.0 gas
4. mv gas $PREFIX/bin
5. cd $PREFIX/bin
6. chmod 755 gas
7. cd

#  EDIT CONFIG

!!! JANGAN DI UBAH FORMAT SELAIN (proxies:) !!!

    HARUS MAKE BUG IP/GK BISA DOMAIN

1. micro .config/clash/config.yaml

2. SAVE: CTRL terus S
3. EXIT: CTRL terus Q

# JALANIN CLASH NYA

1. gas

# ATUR APN

PROXY : 127.0.0.1
PORT : 7890

# MASUK WEB PANEL

http://127.0.0.1:9090/ui/#/proxies

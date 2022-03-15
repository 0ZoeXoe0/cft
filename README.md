# CARA INSTALL

1. apt update
2. apt  upgrade          (Y trus N,N,N)
3. apt install git
4. apt install wget
5. git clone https://github.com/0ZoeXoe0/cft.git
6. cd cft && bash install.sh
7. cd

# INSTALL METACORE

!!! CONTOH ARMv8, KALAU MAU ARMv7 GANTI 8 KE 7 !!!

1. wget https://github.com/0ZoeXoe0/cft/releases/download/METACORE/Clash.Meta-linux-armv8-develop-52c37f7.gz
2. gunzip Clash.Meta-linux-armv8-develop-52c37f7.gz
3. mv Clash.Meta-linux-armv8-develop-52c37f7 gas
4. mv gas /data/data/com.termux/files/usr/bin/
5. cd /data/data/com.termux/files/usr/bin/
6. chmod 755 gas
7. cd

#  EDIT CONFIG

!!! JANGAN DI UBAH FORMAT SELAIN (proxies:) !!!

1. micro .config/clash/config.yaml

2. SAVE: CTRL terus S
3. EXIT: CTRL terus Q

# JALANIN CLASH NYA

1. gas

# MASUK WEB PANEL

http://127.0.0.1:9090/ui/#/proxies

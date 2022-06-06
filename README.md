# allow-ufw-azure-japaneast

## ufw で以下実行しておけばok
```
sudo ufw allow from 172.16.2.0/24 to any port 14159
sudo ufw allow from 20.210.0.0/17 to any port 14159
sudo ufw allow from 20.78.192.0/18 to any port 14159
sudo ufw allow from 20.78.0.0/17 to any port 14159
sudo ufw allow from 20.194.128.0/17 to any port 14159
sudo ufw allow from 20.63.128.0/18 to any port 14159
sudo ufw allow from 20.89.0.0/17 to any port 14159
sudo ufw allow from 20.191.160.0/19 to any port 14159
sudo ufw allow from 40.115.212.59/32 to any port 14159
```

japaneast の Azure VM のみ許容してる。漏れがあったらまた追記

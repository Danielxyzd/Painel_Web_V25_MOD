![Login](https://user-images.githubusercontent.com/105602625/183294180-8cfc6772-409a-4497-a9aa-71b1cec85f73.jpg)

# SISTEMAS RECOMENDADO
</br>
⚠  VPS RECOMENDADA PARA PAINEL WEB: https://www.avirahost.com.br/aff.php?aff=108 ⚠

```
Debian 8
Ubuntu 14
```

# ATUALIZAR PACOTES DO SISTEMA
```
apt-get update -y; apt-get upgrade -y;
```

# INSTALAR PAINEL WEB V25
```
wget https://raw.githubusercontent.com/JeanRocha91x/Painel_Web_V25_MOD/main/gestorssh/install ; bash install
```

# DEFINIR/ALTERAR SENHA ROOT
```
wget https://raw.githubusercontent.com/JeanRocha91x/Painel_Web_V25_MOD/main/gestorssh/senharoot ; bash senharoot
```

# SINCRONIZAR, CASO NÃO SEJA SSHPLUS PRO!
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/JeanRocha91x/Painel_Web_V25_MOD/main/gestorssh/sincpainel && chmod +x sincpainel && dos2unix sincpainel && ./sincpainel
```

# SINCRONIZAR, CASO SEJA SSHPLUS PRO!
```
apt install dos2unix -y; wget https://raw.githubusercontent.com/JeanRocha91x/Painel_Web_V25_MOD/main/gestorssh/sincrazy && chmod +x sincrazy && dos2unix sincrazy && ./sincrazy
```

## :octocat: Credits
1. @crazy_vpn - Developer of SSHPlus Manager
2. @swittecnologia - Contributor 
```
☆ https://t.me/swittecnologia ☆
```

![Painel](https://user-images.githubusercontent.com/105602625/183294181-51292f4e-a636-4896-90fa-baf33f86f7bf.jpg)

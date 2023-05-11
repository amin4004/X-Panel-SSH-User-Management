<p dir="auto">
<img alt="GitHub release (latest by date)" src="https://img.shields.io/github/v/release/Alirezad07/X-Panel-SSH-User-Management">
</p>

# X Panel SSH User Management

## Introduction
X-Panel is a web-based control panel for SSH VPN accounting. With the help of X-Panel you can easily configure users and set your desirable limits.

### Features
Unlimited user creation<br>
Limiting bandwidth usage and setting expiration date<br>
Capable of calculating expiration date on first connection<br>
Limiting the amount of connections per user<br>
View online users<br>
Backup & Restore capability<br>
Telegram Bot support<br>
Setting optional port number for control panel access<br>
Fake address (Evade Censorship)<br>
IP blacklist (Blacklisting adult websites and …)<br>
Multi-server support (Soon…)<br>
API support (Soon…)<br>


### Installation guide
Supported operating systems<br>
- **Ubuntu 18+ (recommended: Ubuntu 20)** <br>

If your currently installed XPanel is below version 2 you must first remove the panel with the command below:<br>
```
rm -rf /var/www/html/
mkdir /var/www/html/
chmod 777 /var/www/html/
```

To install the XPanel simply input the following command in the terminal:<br>
```
bash <(curl -Ls https://raw.githubusercontent.com/Alirezad07/X-Panel-SSH-User-Management/main/install.sh --ipv4)
```

Fixing the known video & voice call issue in the application:<br>
```
bash <(curl -Ls https://raw.githubusercontent.com/Alirezad07/X-Panel-SSH-User-Management/master/fix-call.sh --ipv4)
```

**Server optimization**
Use the following command to install or remove<br>
```
bash <(curl -Ls https://raw.githubusercontent.com/Alirezad07/X-Panel-SSH-User-Management/main/TCP-Tweaker --ipv4)
```


### Enabling SSL
```
bash <(curl -Ls https://raw.githubusercontent.com/Alirezad07/X-Panel-SSH-User-Management/main/ssl.sh --ipv4)
```
With the above command you can install SSL on the panel **(First pay attention to tips below)** <br>
1- Make sure to update the panel BEFORE installing the SSL<br>
2- Do not use any other commands to activate SSL<br>
3- Set the server’s IP in your domain or subdomain<br>
4- Input the above command in the terminal and proceed with the installation<br>
**SSL is now active on your selected port**



### Supporting us
If X-Panel has been useful to you with supporting us you can help developing this web application.<br>
Tether TRC20 USDT: `TYQraQ5JJXKyVD6BpTGoDYNhiLbFRfzVtV`<br>
ETH: `0x6cc08b2057EfAe4d76Af531e145DeEd4B73c9D7e`


# Instruction
The script is provided by the Information Office of ECNU. This repository is only for the convenience of logging in to the server. The script takes effect on July 13, 2023

# Using
``` bash
cd ~
git clone https://github.com/jerryzz668/ECNU-Login
mv ECNU-Login/.auth-setting .
mv ECNU-Login/auth_client .
chmod +x auth_client

# login
./auth_client -u <account> -p <passwd>

# logout
./auth_client -u <account> auth --logout
```


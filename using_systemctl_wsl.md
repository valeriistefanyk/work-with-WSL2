# Решение проблемы с невозможностью выполнить systemctl в WSL2
Из найденых решений работающим и простым оказался скрипт [DamionGans](https://github.com/DamionGans/ubuntu-wsl2-systemd-script) 

## Использование
Выполнить комманды:

```
git clone https://github.com/DamionGans/ubuntu-wsl2-systemd-script.git
cd ubuntu-wsl2-systemd-script/
bash ubuntu-wsl2-systemd-script.sh
# Enter your password and wait until the script has finished
Then restart the Ubuntu shell and try running systemctl
```

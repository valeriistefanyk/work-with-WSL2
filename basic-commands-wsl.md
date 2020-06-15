## Основные команды, использующиеся на начальном этапе

* Подробная информация обо всех дистрибутивах:
  ```
  wsl --list --verbose
  ```

* Если дистрибутив на архитектуре WSL 1 - используйте эту команду для преобразования дистрибутива в архитектуру WSL 2:
  ```
  wsl --set-version <Distro> 2
  ```
  , где <Distro> - конкретный дистрибутив Linux (к примеру, Ubuntu)

* Изменяет версию установки по умолчанию (WSL 1 или 2) для новых дистрибутивов:
  ```
  wsl --set-default-version <Version>
  ```

* Немедленно завершает работу всех запущенных дистрибутивов и облегченной виртуальной машины WSL 2:
  ```
  wsl --shutdown
  ```

## Запуск дистрибутива
Запускать дистрибутив можно как с помощью команды `wsl` в powershell, cmd, bash и т.д., так и т.к. дистрибутив скачивается с Microsoft Store - запустить как приложение.

В мае 2020 Microsoft официально выпустила [Windows Terminal](https://www.microsoft.com/en-us/p/windows-terminal/9n0dx20hk701?activetab=pivot:overviewtab) - централизованная точка доступа к оболочкам вроде PowerShell, cmd, azure cloud, WSL, и др. Запуск дистрибутива можно производить и с оттуда. 

![Windows Terminal 1](https://raw.githubusercontent.com/valeriistefanyk/working-with-WSL2/master/images/windows_terminal1.png)

![Windows Terminal 2](https://raw.githubusercontent.com/valeriistefanyk/working-with-WSL2/master/images/windows_terminal2.png)

[###Минимальные требования](https://learn.microsoft.com/en-us/windows/wsl/install#prerequisites;)
- Машина с "Windows 10 version 2004 and higher"
- Уметь читать;

[###Установка](https://learn.microsoft.com/en-us/windows/wsl/install#install-wsl-command)
- Загрузить из магазина [Windows Terminal](https://apps.microsoft.com/store/detail/windows-terminal/9N0DX20HK701) (Рекомендуется Microsoft);
- Загрузить из магазина [Microsoft Power Shell](https://apps.microsoft.com/store/detail/powershell/9MZ1SNWT0N5D) (Более продвинутая версия PS с плюшками);
- Открыть терминал (Win+X -> Terminal)
- Выполните ``wsl --install``,
> По умолчанию будет установлена LTS версия Ubuntu,
> Для установки иных дистрибутивов выполнить: ``wsl --install -d <Distribution Name>`` (Будет работать для установки любого еще не установленого дистрибутива),
> Чтобы увидеть список доступных для скачивания дистрибутивов: ``wsl --list --online``;
> [Более подробно об установке различных диструбутивов](https://learn.microsoft.com/en-us/windows/wsl/install#change-the-default-linux-distribution-installed)
    
[###Первый запуск](https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-username-and-password)   
- После установки для запуска WSL можно воспользоваться ярлыком соответствующего дистрибутива (должен появиться в списке приложений), выпадающим меню опций для запуска в Windows Terminal (my way) или выполнить команду ``wsl``, при первом запуске будет предложено установить пароль и логин для администратора;
- [Если забыл пароль](https://learn.microsoft.com/en-us/windows/wsl/setup/environment#set-up-your-linux-username-and-password)
- Затем рекомендуется установить последние обновления системы: ``sudo apt update && sudo apt upgrade``

[###Настройка окружения]()
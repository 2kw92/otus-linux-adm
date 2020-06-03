### Базовая подготовка хостов и настройка сети

Базовая подготовка сводится к следующим действиям:
- Назначить IP-адреса и корректные DNS-серверы;
- Задать имена машин;
- Назначенные IP-адреса сопоставить с именами машин в /etc/hosts;
- Синхронизировать время с внешним источником для первоначальной установки FreeIPA;
- Установить пакеты, с помощью которых вам будет проще производить отладку (например, policycoreutils-python, bind-utils, X11 или иные).
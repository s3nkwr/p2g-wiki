---
order: 7
authors:
  - SimonSays2310
---
# "Открытый ключ профиля отсутствует. Для этого сервера требуются защищённые профили."

![missingkey](/minecraft/missingkey.png)

Для исправления этой ошибки нужно заменить параметр `enforce-secure-profile` на `false` в server.properties, после чего перезапустить сервер.

```properties
enforce-secure-profile=true // [!code --]
enforce-secure-profile=false // [!code ++]
```

Если вы не владелец сервера, то тут могут быть две причины появления этой ошибки:

1. Вы пытаетесь зайти на лицензионный сервер с пиратки;

2. Вы пытаетесь зайти на сервер с модом NoChatReports, отключив подписывание своих сообщений (дабы на них нельзя было пожаловаться в Mojang). В таком случае вам придётся либо включить их подписывание, либо же обратиться к владельцу сервера, дабы он отключил эту настройку/не играть на таком сервере.
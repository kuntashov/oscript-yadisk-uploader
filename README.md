# Скрипт на 1Script для загрузки и публикации файлов на Яндекс.Диск

Примеры использования:

```shell
oscript yadisk-uploader.os -publish C:\Temp\image.png
```

В консоль выведет публичную ссылку, например:

```
https://yadi.sk/i/EKsY57BvoY7BN
```

На Яндекс.Диске файлы вы сможете найти в папке `/Прилоожения/OScript.YaDisk.Uploader`.

### Требования

Для работы скрипта необходима последняя версия [стандартной библиотеки OScript](https://github.com/EvilBeaver/oscript-library), а также [библиотека для работы с Яндекс.Диском](https://github.com/kuntashov/oscript-yadisk).

### Настройка OAuth-токена 

Перед использованием скрипта необходимо получить OAuth-токен для приложения, перейдя по ссылке

https://oauth.yandex.ru/authorize?response_type=token&client_id=982900c5b5874c2ba009bb217ecc4658

и подтвердить разрешение для приложения OScript.YaDisk.Uploader.

В ответ вы получите токен авторизации, который нужно сохранить в файле oauth_token.txt в папке со скриптом.
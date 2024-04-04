
# Адаптация главной страницы под мобильные устройства


## Cайт https://fabrika.hi-tech.md

Данный проект находится на движке `OpenCart`. Для работы с файлами сайта, проект необходимо скачать с [Google Drive](https://drive.google.com/file/d/1AfmA5z-wxLVLCygdM6LbNuIKIWKK-SbQ/view?usp=sharing) на локальный сервер. База данных находится в архиве `www` - дамп `fabrika.sql`. 

Админ панель находится по адресу: https://fabrika.hi-tech.md/admin_ht

Логин: **admin** 
Пароль: **admin**

На данный момент главная страница не адаптированна под мобильные устройства 

**Пример**

![Logo](https://img001.prntscr.com/file/img001/boEZWNalTpGOMs_ml5z3zg.png)


## Задача

- установить и сконфигурировать все необходимое для работы с проектом.
- адаптировать главную страницу под мобильные устройства.


## Примечания

- файл конфигурации `config.php`
- файл дампа базы данных `fabrika.sql`
- блоки с главной страницы находятся в админ панели в меню модуля `"Настройка темы->Модули->Статический блок`

## Установка

1) файлы с архива `www` перенести в корень папки на локальном сервере (для примера если это `OpenServer` то путь будет `C:\OSPanel\domains\`)
2) сконфигурировать пути и данные для БД (`C:\OSPanel\domains\fabrika.hi-tech.md\admin_ht\config.php` - для админ панели `C:\OSPanel\domains\fabrika.hi-tech.md\config.php` - для сайта)
3) импорт БД `fabrika.sql` название базы данных:`fabrika` логин: `root` пароль: `-`

## Feedback

Вопросы можно задать в ТГ [@sergeyoancha](https://t.me/sergeyoancha)


![Logo](https://hi-tech.md/images/logos/2/logo_hi_tech.svg)


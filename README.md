# Тестовое задание для PHP разработчика  
  
## Написать консольное приложение на PHP

Задача:
* Написать консольное приложение для проверки ошибок на сайтах при помощи PHP
* Написать мини-документацию по использованию
* Загрузить в Git репозиторий и предоставить ссылку на него  
  
Пример запуска приложения:
```php checkHost.php test-domain.com```  
  
Пункты проверки:
1. Заголовки сервера
2. Наличие tittle, description, h1 на странице
3. Проверка путей до favicon, img, js и css скриптов
4. Проверка на наличие ошибок PHP
5. Проверка наличия robots.txt и sitemap.xml
6. Если проверите главную страницу на pageSpeed (Google), это будет Вашим преимуществом 

Дополнительно:
* Проверять все страницы сайта
* Вести логирование (2 файла) с временными отметками
    * Файл с ошибками
    * Файл с проверенными страницами
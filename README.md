## Русский перевод шаблона Markdown для phpDocumentor 3.x

### Установка через Composer
- Добавьте репозиторий в файл composer.json:
```json
{
  "repositories": [
    {
      "type": "git",
      "url": "https://github.com/luckygun777/phpdocumentor-markdown-theme-ru"
    }
  ]
}
```
- Установите библиотеку:
```bash
# composer require --dev phpdocumentor-markdown-theme-ru:dev-current
```
- Укажите в файле phpdoc.xml путь к шаблону:
```xml
<template name="./vendor/luckygun777/phpdocumentor-markdown-theme-ru/themes/markdown"/>
```
## Оригинальный шаблон взят отсюда:
* [https://github.com/Saggre/phpDocumentor-markdown]

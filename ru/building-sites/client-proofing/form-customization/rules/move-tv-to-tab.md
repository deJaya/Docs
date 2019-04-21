---
title: Переместить телевизор на вкладку
translation: building-sites/client-proofing/form-customization/rules/move-tv-to-tab
---

## Правило перемещения телевизора на вкладку

Правило «Переместить телевизор на вкладку» переместит любой телевизор на указанную вами вкладку.

## использование

Укажите идентификатор вкладки для перехода в поле «имя» правила. Затем укажите идентификатор телевизора с префиксом «tv» в поле «значение».

Список доступных вкладок:

| ID                     | Описание                                                    |
| ---------------------- | ----------------------------------------------------------- |
| modx-resource-settings | Первая вкладка, или вкладка Создать / Редактировать ресурс. |
| modx-page-settings     | Вторая вкладка или вкладка «Параметры страницы».            |

Вы также можете создать вкладку с помощью правила [Новая вкладка»](display/revolution20/New+Tab "Новая вкладка") и перенести туда телевизор.

## Примеры

Пример правила для перемещения TV 1 на первую вкладку на странице создания ресурса будет выглядеть так:

![](/download/attachments/18678100/rule-tvMove.png?version=1&modificationDate=1279291685000)

## Смотрите также

```php
[[getResources@section? &parents=`1353` &context=`revolution`]]
```
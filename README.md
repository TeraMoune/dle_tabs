DLE TABS ~~FOR CSS~~ JavaScript
=
> Данный хак позволяет добавлять в новость вкладки. Их полезность заключается в том, что они позволяют существенно сократить площадь, занимаемую информацией, выводимой в новости. К тому же это оригинально и красиво.

> Автор для 9.x: ``rocksmart``. Доработка и исправление под 10.x **by MaD**

> Еще одна доработка под 13> версию, **TeraMoune**
>> Пример немного изменён, добавлен `title` добавляющий заголовок в тело таба.
>>
>> Добавлен `color` добавляющий цветовое оформление.
>>
>> Использует JavaScript плагин от Пафнутого, и слегка изменённый мной [tabsToSelect](https://github.com/TeraMoune/tabsToSelect) вместо CSS

**Пример кода табов**
```
[tab]

[section=tab1 title="Заголовок"]text1[/section]
[section=tab2 color="#faceff"]text2[/section]
[section=tab3]text3[/section]
[section=tab4]text4[/section]

[/tab]
```
#Инструкция по установке DLE Табов
--------------
 - Установить xml плагин.
 - Всё.

Проверялся на 13.0 версии, и не достаточно тщательно :D И так как я использую FroalaEditor, то и проверял в основном на нём. Другие редакторы вроде бы тоже могут но пока я не проверял их.

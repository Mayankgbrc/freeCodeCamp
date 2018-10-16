---
title: Attributes
localeTitle: Атрибуты
---
# Атрибуты HTML

Элементы HTML могут иметь атрибуты, которые содержат дополнительную информацию об элементе.

Атрибуты HTML обычно входят в пары имя-значение и всегда идут в открывающий тег элемента. Имя атрибута говорит, какой тип информации вы предоставляете об элементе, а значение атрибута - это фактическая информация.

Например, элемент привязки ( `<a>` ) в документе HTML создает ссылки на другие страницы или другие части страницы. Вы используете атрибут `href` в открывающемся теге `<a>` чтобы сообщить браузеру, где ссылка отправляет пользователя.

Ниже приведен пример ссылки, которая отправляет пользователей на домашнюю страницу freeCodeCamp:

```html

<a href="www.freecodecamp.org">Click here to go to freeCodeCamp!</a> 
```

Обратите внимание, что имя атрибута ( `href` ) и значение («www.freeCodeCamp.org») разделены знаком равенства, а кавычки окружают значение.

Существует много разных атрибутов HTML, но большинство из них работают только с определенными элементами HTML. Например, атрибут `href` не будет работать, если он помещен в открывающий `<h1>` .

В приведенном выше примере значение, предоставленное `href` может быть любой допустимой ссылкой. Однако некоторые атрибуты имеют только набор допустимых параметров, которые вы можете использовать, или значения должны быть в определенном формате. Атрибут `lang` указывает браузеру язык по умолчанию содержимого HTML-элемента. Значения `lang` атрибут должны использовать стандартные языковые или коды стран, такие как `en` на английском языке, или `it` для итальянки.

## Логические атрибуты

Некоторым атрибутам HTML не требуется значение, потому что у них есть только один параметр. Они называются логическими атрибутами. Наличие атрибута в теге применит его к этому элементу HTML. Тем не менее, это нормально записать имя атрибута и установить его равным одному параметру значения. В этом случае значение обычно совпадает с именем атрибута.

Например, элемент `<input>` в форме может иметь `required` атрибут. Для этого требуется, чтобы пользователи заполнили этот элемент, прежде чем они смогут отправить форму.

Вот примеры, которые делают то же самое:

```html

<input type="text" required > 
 <input type="text" required="required" > 
```

## Другие источники

[Ссылки HTML](#) [Атрибут Href](#) [Атрибут Ланга](#) [Элемент ввода HTML](#) [Обязательный атрибут](#)
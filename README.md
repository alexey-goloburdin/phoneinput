# Маска ввода телефона для российских и других номеров

Пример работы — [phoneinput.to.digital](phoneinput.to.digital).

Другие страные не игнорируются, номера нероссийских тефонов успешно вводятся, но оставляются без маски. Посмотрите [видео](https://www.youtube.com/watch?v=Lxj_v5z0xRE) о процессе написания маски и о том, почему её нужно использовать.

## Как использовать

```html
<html>
<head>
    <script src="phoneinput.js"></script>
</head>
<body>
    <input type="tel" data-tel-input placeholder="Phone" maxlength="18" />
</body>
</html>
```

JS код в `phoneinput.js` найдет все элементы `input` с `data-tel-input` атрибутом и обработает их.

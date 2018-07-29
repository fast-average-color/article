# Усреднённый цвет в JavaScript

По работе делал листалку фотографий. Сопровождающий текст было решено положить на усреднённый цвет фото. Тема среднего цвета заинтересовала, и я решил 
посмотреть какие ещё варианты можно использовать в верстке.

## Фон
Рассчитываем средний цвет фотографии и устанавливаем цвет подложки. [Пример](https://hcodes.github.io/fast-average-color/examples/background.html)
![Background](./images/bg.png)

## Градиент
Средний цвет высчитывается у верхней или нижней части картинки и используется в подложке для текста. Между картинкой и подложкой установлен плавный градиент. Стиль Яндекс.Дзена. [Пример](https://hcodes.github.io/fast-average-color/examples/gradient.html)
![Gradient](./images/gradient.png)

Градиент в стиле Minecraft — средний цвет высчитывается частями (горизональными полосками). [Пример](https://hcodes.github.io/fast-average-color/examples/gradient_stripes.html)
![Minecraft gradient](./images/minecraft.png)


## Рамка
Как багет у картины, средний цвет высчитывается отдельно у каждой из сторон фотографии.
[Пример](https://hcodes.github.io/fast-average-color/examples/border.html)
![Border](./images/border.png)

## Тень
Вычисленный средний цвет используется в задании цвета падающей тени. [Пример](https://hcodes.github.io/fast-average-color/examples/box-shadow.html)
![Box shadow](./images/box_shadow.png)

В CSS у элемента можно задать несколько теней. Для каждой из сторон фотографии вычислим средний цвет и установим отдельную тень. [Пример](https://hcodes.github.io/fast-average-color/examples/box-shadow-4-sides.html)
![Box shadow, 4 sides](./images/box_shadow_4.png)

## Видео
Предыдущий пример применим в динамике для видео. [Пример](https://hcodes.github.io/fast-average-color/examples/ambilight.html#4Sides)
![Video, box shadow, 4 sides](./images/video_box_shadow.png)

Разделим стороны экрана на большее количество частей (30), в которых вычислим средний цвет для отбрасываемой тени, совсем как у [Philips Ambilight](https://ru.wikipedia.org/wiki/Ambilight). [Пример](https://hcodes.github.io/fast-average-color/examples/ambilight.html#ManyPoints)
![Video, Ambilight](./images/video_ambilight.png)

## Текстовая фотография
Фотографию заполняем текстом, под каждым символом вычисляем средний цвет и применяем его к символу. [Примеры](https://hcodes.github.io/fast-average-color/examples/text-photo.html) с другими браузерами.
![Text photo](./images/firefox.png)

## Использование

Ссылки:
- [fast-average-color в Github](https://github.com/hcodes/fast-average-color)
- [fast-average-color в npm](https://www.npmjs.com/package/fast-average-color)
- [Все примеры](https://hcodes.github.io/fast-average-color/examples/background.html)
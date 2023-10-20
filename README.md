# Slider v1.0

Плагин позволяет создавать слайдер
Для начала ознакомьтесь с  https://shelkov90.github.io/modul_slider/docs/started-welcome.html.**

## Быстрый старт

### Установка

Загрузите таблицу стилей и JS

#### HTML

Поместите  таблицу стилей на [вверху]:

```html
<link rel="stylesheet" href="slider.css" />
```

Поместите скрипты в нижнюю часть: 

```html
<script src="slider.js"></scri>
```

### Использование
Добавьте в структуру элемент контейнера 

``` HTML
	<div id="slider-container" class="slider-container">
		<h2 id="slider-title">My Slider</h2>
		<div class="slider">
			<div class="slide active">
				<img src="img/7.avif" alt="Slide 1">
			</div>
			<div class="slide">
				<img src="img/8.avif" alt="Slide 2">
			</div>
			<div class="slide">
				<img src="img/9.avif" alt="Slide 3">
			</div>
		</div>
		<div class="prev-arrow" id="prevArrow">←</div>
		<div class="next-arrow" id="nextArrow">→</div>
	</div>
```
** ПРИМЕЧАНИЕ. ** Вы можете использовать другой класс или id. В таком случае при подключении плагина необходимо указать соответствующий класс.


## Документация

Документация, включенная в это репо в корневом каталоге и общедоступна на https://multiply.github.io/Multiply/. Документация также может выполняться локально.



## License

The code and the documentation are released under the [MIT License](LICENSE).

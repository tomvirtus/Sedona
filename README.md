# Sedona
Профессиональный HTML и CSS" - Уровень 1 третий проект
Техническое задание на вёрстку
Название сайта: Седона
Домен: пока нет
Общие технические требования
Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение.
Сетка: три колонки равной ширины (33%), стоящие вплотную друг к другу без отступов.
Два варианта вёрстки: — под фиксированную ширину 768px или 1200px: с центровкой основного контента, с некоторыми блоками, которые тянутся на всю ширину; — с дополнительной резиновостью (необязательный вариант): диапазон ширин от 768px до 1200px (смотрите макеты с суффиксом «-768», папка слоёв «Guides»).
Используемые фреймворки: нет.
Кроссбраузерность: IE10+, Chrome, Firefox, Opera, Safari.
Типографика: частично определена в макете (прочее — на усмотрение разработчика).
Используемые шрифты: PT Sans (есть на http://google.com/fonts).
С макетом предоставлен styleguide.psd, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет.
С макетом предоставлен иконочный шрифт, нужно использовать его в вёрстке. Названия слоёв с иконками соответствуют CSS-классам иконок.

Пояснения для учащихся
Иконочный шрифт сгенерирован на http://fontello.com — вы можете загрузить конфиг генератора (файл symbols-sedona/config.json) на http://fontello.com и увидеть все классы и символы иконок, а symbols-sedona/demo.html содержит демонстрацию и пример подключения иконок к странице.
В макетах есть скрытые слои с всплывающими окнами. Такие слои в блоке слоёв фотошопа выделены синим цветом.
Макеты верстаются постепенно, не нужно сразу выполнять все требования.
Пожелания к поведению блоков
Все макеты:
Контентная область центрируется и не может быть уже макетной ширины.
Логотип — это ссылка на главную страницу.
Главное меню: четыре ячейки по 20% ширины, в каждой из них контент лежит по центру. Между второй и третьей есть отступ для расположения логотипа так же шириной 20%.
При достижении 1200px (или 768px, если верстается фиксированная версия с этой шириной) сетка перестаёт масштабироваться дальше, и слева и справа от неё появляется серый фон, на который сайт бросает лёгкую тень.
sedona-index.psd:
Крупное фото: фотография занимает 100% ширины, в её нижней части есть белая маска, которая также масштабируется на 100% ширины, но в отличие от фотографии меняет свои пропорции (то есть высота остаётся постоянной, а ширина — 100%).
Фотографии, занимающие по две трети ширины вставляются так, чтобы обрезаться сверху и снизу при увеличении размера (ширина 66%, высота подстраивается под ширину, чтобы не нарушать пропорций, но фото не выходит за отведённую для него зону).
Кнопка «Поиск гостиницы в Седоне» управляет отображением формы поиска гостиницы (смотрите папку слоёв «search form»), необходимо дополнить анимацией «выезда» сверху вниз.
Блок карты — достаточная реализация — обычное изображение.
Блок карты — реализация по желанию — интерактивная карта, которая также масштабируется на 100% ширины.
sedona-hotels.psd:
Главное меню и футер совпадают с главной страницей.
Фоновое фото другое (размытое и меньшей высоты), но также масштабируется на 100% ширины.
Блок «Стоимость в сутки» — при наведении на любой из маркеров появляется указатель cursor: pointer, делать маркеры подвижными не обязательно, цена меняться не должна.
Фильтр: верстать с помощью формы, кнопка «Показать» отвечает за отправку формы, при выключенном JavaScript должен осуществляться переход на отдельную страницу (отдельную страницу верстать не нужно).

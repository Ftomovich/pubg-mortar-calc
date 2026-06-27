# 🎯 PUBG Mortar / Distance Calculator

Веб-инструмент для измерения дистанции и стрельбы с мортиры в PUBG.
Чистый HTML+JS, без сервера — идеально для GitHub Pages.

## Возможности
- Выбор карт сбоку
- Зум колесом мыши (в точку под курсором) + перетаскивание (ПКМ/средняя кнопка)
- Кнопки − / 100% / + внизу (клик по проценту = вписать карту)
- Две точки ЛКМ → дистанция в метрах
- Сетка 100 м с включением/выключением (жирные линии = 1 км)
- Подписи километров (вкл/выкл)

## Как добавить карты
Положи HD-картинки карт (квадратные, например 4096×4096 PNG) в папку maps/:
maps/erangel.png, maps/miramar.png, maps/taego.png, maps/deston.png,
maps/rondo.png, maps/vikendi.png, maps/sanhok.png, maps/paramo.png,
maps/karakin.png, maps/haven.png

Официальные карты: https://pubg.com/ru/game-info/maps/erangel

Размеры карт уже заданы в index.html (массив MAPS, поле size в метрах).
Чтобы добавить/убрать карту — просто отредактируй этот массив.

## Публикация на GitHub Pages
1. Создай репозиторий (или используй существующий).
2. Залей index.html, README.md и папку maps/ с картинками.
3. Settings → Pages → Source: main / root → Save.
4. Через минуту сайт доступен по адресу https://ТВОЙ_НИК.github.io/ИМЯ_РЕПО/
5. Эту ссылку вставляй в руководство Steam.

made by horsse — improved build
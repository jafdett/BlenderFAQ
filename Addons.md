# Аддоны Blender / Blender Add-ons. Введение
## Что это? 
Аддоны это дополнительные программы, написанные сторонними разработчиками (а иногда и основыми), использующие внутренние API основной программы и расширяющие ее возможности. 

## Я не смогу без них работать в Blender?
Нет, сможете, но их использование обычно расширяет возможности и упрощает работу, автоматизирует рутинные операции. 

## Где найти addon-ы?
- https://blenderartists.org
- https://blendermarket.com
- https://gumroad.com

## Классификация
Addon-ы делятся на два типа: встроенные и внешние. Встроенные поставляются сразу с Blender, но по-умолчанию обычно выключены.
Включить их очень просто: через Preferences - Add-ons. 
Внешние addon-ы надо сначала найи в интернете, потом скачать и установить. Внешние аддоны могут быть бесплатными и платными, также они могут поставляться под разными лицензиями.


## Как установить Addon?
Обычно автор прилагает к аддону инструкции, но вот что нужно делать, если их нет:
1. Скачайте файл с zip-архивом аддона. Если аддон находится на Гитхабе, то поищите справа ссылку на релизы, там обычно должны  быть уже готовые архивы. 
2. В Blender откройте меню настроек (Preferences - Add-ons) и нажмите Install (в верхней части меню). Далее выберите файл с архивом, дальше Blender все сделаем сам. 
3. Теперь аддон появится в общем списке и можно нажать галочку напротив него, чтобы его включить. 

## Как им управлять?

## Как его удалить?

# Список addon-ов по категориям. 
В каждой категории сначала идут встроенные (не отмечены никак). <br>
Потом бесплатные внешние: у них есть ссылка, а потом платные: у них тоже есть ссылка и они отмеченны символом **$**

## Моделирование 
- LoopTools - дополнительные операции с вершинами, ребрами и поверхностями: выравнивание, выстроение по кругу, по кривой, задание общего промежутка между вершинами и прочее
- BoolTools - быстрые булевые операции за счет автоматизации наложение модификатора Boolean.

## Текстурирование 

## Риг
- Rigify 
- [WiggleBones](https://blenderartists.org/t/wiggle-bones-a-jiggle-bone-implementation-for-2-8/1154726) 
- [X-Muscle System](https://blendermarket.com/products/x-muscle-system) **$**
- [AutoRig PRO](https://blendermarket.com/products/auto-rig-pro) **$**

## Анимация

## Работа с HardSurface
- Carver
- [MeshMachine](https://blendermarket.com/products/meshmachine) **$**
- [DecalMachine](https://blendermarket.com/products/decalmachine) **$** 
- [HardOPS](https://blendermarket.com/products/hardopsofficial) **$**
- [BoxCutter](https://blendermarket.com/products/boxcutter) **$**

## Работа со Sculpt
- [MeshFairing](https://github.com/fedackb/mesh-fairing) 
- [Extended Sculpt Tools](https://biman.gumroad.com/l/dUbp) **$** 
- [SpeedSculpt](https://blendermarket.com/products/speedsculpt) **$** 

## Ретопология
- Bsurface
- F2
- [MiraTools](https://blenderartists.org/t/miratools/637385) 
- [Retopoflow 3](https://blendermarket.com/products/retopoflow) **$**, есть бесплатная версия на [Github](https://github.com/CGCookie/retopoflow). 


## Интерфейс
- [Screencast Keys](https://github.com/nutti/Screencast-Keys) - показывает нажатия кнопок на клавиатуре, а также действия с мышью

## Геоданные
- [blender-osm](https://prochitecture.gumroad.com/l/blender-osm) - загрузка данных из OpenStreetMap
- [Maps Models Importer](https://github.com/eliemichel/MapsModelsImporter) - загрузка данных из Google Maps

## Rendering 
- [LuxCore Render](https://github.com/LuxCoreRender/BlendLuxCore/releases) 

## Волосы и шерсть
- [Hair Tool](https://bartoszstyperek.gumroad.com/l/hairtool) **$**


## Импорт / экспорт
- [SCS Blender Tools](https://github.com/SCSSoftware/BlenderTools) - инструменты для редактирования ассетов в играх от SCS Software
- [Unreal Blender Tools](https://epicgames.github.io/BlenderTools/) - средства для работы с Unreal Engine 4

## Природные явления и живая природа
- Sapling tree generator
- Real Snow
- IvyGen
- A.N.T. Landscapes
- Sun Position
- Dynamic Sky

## Архитектура
- Archimesh
- Archipack

## Ускорение работы и дополнительные инструменты
- Node Wrangler
- MeasureIT
- BoltFactory
- Extra Objects
- tinyCAD
- [Pie menu editor](https://blendermarket.com/products/pie-menu-editor) **$**

## Работа с камерой
- Add camera rig
- [Real camera](https://3d-wolf.com/products/camera/) - позволяет управлять камерой Blender, как настоящей (автоэкспозиция, автофокус)
- [Photographer 4](https://chafouin.gumroad.com/l/HPrCY) **$** - добавляет новую физическую камеру, настройки физического освещения и интерфейсы микшера для источников света, эмиссионных материалов и миров для EEVEE, Cycles и LuxCore 2.5. ([демо](https://www.youtube.com/watch?v=q_IzKyDD2KY)) . Есть бесплатная версия [Photographer 2](https://chafouin.gumroad.com/l/FWQf), но она работает на версиях до 2.9.
- [Cinepack](https://blendermarket.com/products/cinepack-pre-animated-camera-moves) **$** - Предварительно анимированные движения камеры ([демо](https://youtu.be/tWnuaHjTGcM)).

## Работа с UV развёрткой
- Magic UV
- [TexTools](http://renderhjs.net/textools/blender/)
- [UV Packer](https://www.uv-packer.com/blender/) - это автоматизированное приложение для UV-упаковки одним щелчком мыши.
- [UV Squares](https://github.com/Radivarig/UvSquares) - инструмент для UV Editor в Blender, который преобразует выделеные шэлы UV в квадратную сетку.
- [Texel Density Checker](https://mrven.gumroad.com/l/CEIOR) - Рассчитать плотность текселей для модели с текстурой разного размера (512–4096 пикселей) или с нестандартным размером и соотношением сторон. Аддон бесплатный, но вы можете отблагодарить автора и купить его по той же ссылке.
- [Uv Packmaster 3](https://blendermarket.com/products/uvpackmaster) **$** - Один из самых эффективных упаковщиков UV ([UV Packmaster features](https://uvpackmaster.com/for-blender/features/)),([UV Packmaster FAQ](https://uvpackmaster.com/for-blender/uvpackmaster-3-faq/))
- [Zen UV](https://blendermarket.com/products/zen-uv) **$** - это не просто набор инструментов, это готовый конвейер для быстрого создания UV в Blender ([демо](https://youtu.be/Yj2SecY-c1Y))([документация](https://zen-masters.github.io/Zen-UV/)).

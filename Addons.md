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
Настройки аддона находятся внутри меню Preferences - Addons. Настройки есть далеко не у всех аддонов. 
Кроме того, дополнительные, оперативные настройки (те, которые используются во время работы), обычно скрываются в боковой панели, которая выезжает справа по нажатию на кнопку n. Там есть несколько табов, настройки могут быть в любом из них, обычно это указывается в документации.  

## Как его удалить?
![Remove_addons](https://user-images.githubusercontent.com/48691922/148991639-d1af339d-cf0e-4772-9489-868e592e26d8.jpg)
- в Blender откройте меню настроек (Preferences - Add-ons).
- найдите в списке аддонов тот, который хотите удалить.
- раскройте окно аддона, нажав на стрелочку слева от названия аддона, и нажмите кнопку **Remove** 

## Совместимость
> **ВАЖНО:** Аддоны имеют такую важную особенность, как совместимость с версиями Blender! Это касается сторонних аддонов, т.е. аддонов, которые не входят в "коробку" с программой. Если вы перейдёте по ссылке для скачивания соответствующего аддона, то **обязательно ознакомьтесь с его описанием**. Как правило, одним из первых пунктов будет указано, с какими версиями Blender совместим этот аддон.
> Аддон может работать с версиями, не указанными в описании, но гарантировать стабильность и правильность его функционирования никто не сможет. Использование несовместимых аддонов может повлечь за собой сбои в работе программы и потерю данных!

# Список addon-ов по категориям. 
В каждой категории сначала идут встроенные (не отмечены никак). <br>
Потом бесплатные внешние: у них есть ссылка, а потом платные: у них тоже есть ссылка и они отмеченны символом **$**

## Блокинг (драфт)
- [WonderMesh](https://blendermarket.com/products/wonder-mesh) **$** -- аддон, который позволяет создавать 3D-примитивы (плоскость, куб, окружность, сфера, цилиндр, конус, капсула, тор, резьба) с множеством настроек, которые -- и это очень важно! -- возможно менять даже после манипуляций с этими примитивами на уровне объекта (все стандартные трансформации + работа с некоторыми модификаторами). Есть бесплатная версия на [Github](https://github.com/WiresoulStudio/W_Mesh_28x/releases)

## Моделирование 
- LoopTools - дополнительные операции с вершинами, ребрами и поверхностями: выравнивание, выстроение по кругу, по кривой, задание общего промежутка между вершинами и прочее
- BoolTools - быстрые булевы операции за счет автоматизации наложения модификатора Boolean.

## Текстурирование 
[Bpainter](https://blendermarket.com/products/bpainter) - мощный аддон для текстурирования а-ля Substance Painter прямо в Blender **$**

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
- [Sculpt Alphas Manager](https://github.com/Ryxx/Sculpt-Alphas-Manager) - менеджер альфа-изображений для скульпта. [Видео](https://www.youtube.com/watch?v=wHR8baLhnoA&ab_channel=StevenScott
) с пояснениями.
- [Brush manager](https://tingjoybits.gumroad.com/l/zLBPz) - менеджер кистей для скульпта. Цена начинается от 0$, но можно и заплатить, сколько пожелаете. 
- [Blender Sculpt Layers](https://mifth.gumroad.com/l/blender_sculpt_layers) **$** У Blender пока нет нативных слоев для скульпта, но этот аддон их добавляет. 
- [Extended Sculpt Tools](https://biman.gumroad.com/l/dUbp) **$** 
- [SpeedSculpt](https://blendermarket.com/products/speedsculpt) **$** 
- [Paint Wheel](https://jfranmatheu.gumroad.com/l/blender_sculpt_paint_wheel) **$**  Круговое меню а-ля Zbrush с кистями и цветами


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
- MeasureIT - аддон, который позволяет производить измерения. 
- Stored Views - сохраняйте и восстанавливайте пользовательские виды, точку зрения и расположение камер.
- BoltFactory - настоящая фабрика болтов и гаек.
- Extra Objects - аддон, позволяющий создавать дополнительные примитивные и не только примитивные объекты.
- tinyCAD
- [Pie menu editor](https://blendermarket.com/products/pie-menu-editor) **$**

## Работа с камерой
- Add camera rig
- [Real camera](https://3d-wolf.com/products/camera/) - позволяет управлять камерой Blender как настоящей (автоэкспозиция, автофокус)
- [Photographer 4](https://chafouin.gumroad.com/l/HPrCY) **$** - добавляет новую физическую камеру, настройки физического освещения и интерфейсы микшера для источников света, эмиссионных материалов и миров для EEVEE, Cycles и LuxCore 2.5 ([демо](https://www.youtube.com/watch?v=q_IzKyDD2KY)). Есть бесплатная версия [Photographer 2](https://chafouin.gumroad.com/l/FWQf), но она работает на версиях до 2.9.
- [Cinepack](https://blendermarket.com/products/cinepack-pre-animated-camera-moves) **$** - Предварительно анимированные движения камеры ([демо](https://youtu.be/tWnuaHjTGcM)).
- [Fspy](https://fspy.io/) - уже не аддон, а отдельная программа, но плотно работает с Blender: позволяет выставить камеру в Blender, в точности как она установлена на снимке. 

## Работа с UV развёрткой
- Magic UV
- [TexTools](http://renderhjs.net/textools/blender/)
- [UV Packer](https://www.uv-packer.com/blender/) - это автоматизированное приложение для UV-упаковки одним щелчком мыши.
- [UV Squares](https://github.com/Radivarig/UvSquares) - инструмент для UV Editor в Blender, который преобразует выделеные шэлы UV в квадратную сетку.
- [Texel Density Checker](https://mrven.gumroad.com/l/CEIOR) - Рассчитать плотность текселей для модели с текстурой разного размера (512–4096 пикселей) или с нестандартным размером и соотношением сторон. Аддон бесплатный, но вы можете отблагодарить автора и купить его по той же ссылке.
- [Uv Packmaster 3](https://blendermarket.com/products/uvpackmaster) **$** - Один из самых эффективных упаковщиков UV ([UV Packmaster features](https://uvpackmaster.com/for-blender/features/)),([UV Packmaster FAQ](https://uvpackmaster.com/for-blender/uvpackmaster-3-faq/))
- [Zen UV](https://blendermarket.com/products/zen-uv) **$** - это не просто набор инструментов, это готовый конвейер для быстрого создания UV в Blender ([демо](https://youtu.be/Yj2SecY-c1Y))([документация](https://zen-masters.github.io/Zen-UV/)).

## "Мосты" - аддоны для обмена данными с другим софтом
- [Headus UVlayout Bridge](https://github.com/schroef/uvlayout_bridge) - аддон для экспорта объектов из Blender в Headus UVlayout и обратного импорта развёрнутого объекта. Имеет множество опций и возможностей автоматизации.
> Этот аддон требует, чтобы в системе был установлен Headus UVlayout.
- [HeadusUVLayout/RizomUV bridge (2 in 1)](https://titus.gumroad.com/l/B2RUVL) **$** - аддон для экспорта объектов из Blender в Headus UVlayout или RizomUV  и обратного импорта развёрнутого объекта. [(демо)](https://www.youtube.com/watch?v=XusjghptcWI)
> Этот аддон требует, чтобы в системе были установлены Headus UVlayout и RizomUV.

## Аддоны All in One (многофункциональные аддоны)
- [BagaPie](https://blenderartists.org/t/bagapie-modifier-free-addon/1310959) - это универсальный и бесплатный аддон, который создаёт пресеты из модификаторов и геометрических нод (Он в основном предназначен для архитектуры) ([демо](https://youtu.be/nDeK29aAUps)),([документация](https://www.f12studio.fr/bagapie)). Аддон бесплатный, но вы можете отблагодарить автора и купить его.

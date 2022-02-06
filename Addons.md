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
- [WonderMesh](https://blendermarket.com/products/wonder-mesh) **$** &mdash; аддон, который позволяет создавать 3D-примитивы (плоскость, куб, окружность, сфера, цилиндр, конус, капсула, тор, резьба) с множеством настроек, которые &mdash; и это очень важно! &mdash; возможно менять даже после манипуляций с этими примитивами (все стандартные трансформации + работа с некоторыми модификаторами). Есть бесплатная версия на [Github](https://github.com/WiresoulStudio/W_Mesh_28x/releases).
- [Black Mesh](https://blendermarket.com/products/black-mesh) **$** &mdash; аддон для быстрого концептирования, определения базовых форм будущих моделей.
- [Simply Concept](https://blendermarket.com/products/simply-concept) **$** &mdash; аддон для быстрого концептирования, определения базовых форм будущих моделей.

## Моделирование 
- LoopTools - дополнительные операции с вершинами, ребрами и поверхностями: выравнивание, выстроение по кругу, по кривой, задание общего промежутка между вершинами и прочее
- BoolTools - быстрые булевы операции за счет автоматизации наложения модификатора Boolean.
- [Cut Copy Paste](https://moth3r.gumroad.com/l/paste) Этот аддон предоставляет расширенные функции копирования/вставки для 3D-объектов и элементов режима редактирования.
- [Face Cutter](https://blendermarket.com/products/face-cutter) **$** &mdash; это удобный инструмент для моделирования, предназначенный для простой резки ngon`ов
- [MACHIN3tools](https://machin3.gumroad.com/l/MACHIN3tools) &mdash; это бесплатная постоянно развивающаяся коллекция инструментов блендера и круговых меню в одном настраиваемом пакете.

## Работа с нодами
- [NodeRelax](https://github.com/Shahzod114/NodeRelax-Blender-Addon) &mdash; Расслабляющая кисть для нодов, помогает легче расположить нодв. Хоткей: Shift+R

## Текстурирование 
- [Bpainter](https://blendermarket.com/products/bpainter) **$** &mdash;  мощный аддон для текстурирования а-ля Substance Painter прямо в Blender 

## Риг
- Rigify &mdash; создает автоматические риги и контролы для двухногих и четырехногих существ. Перед использованием посмотрите уроки по нему, или прочтите документацию, нужно осознать принципы его работы.
- [WiggleBones](https://blenderartists.org/t/wiggle-bones-a-jiggle-bone-implementation-for-2-8/1154726) 
- [X-Muscle System](https://blendermarket.com/products/x-muscle-system) **$**
- [AutoRig PRO](https://blendermarket.com/products/auto-rig-pro) **$**

## Анимация

## Работа с HardSurface
- Carver &mdash; Бесплатный аналог BoxCutter. Позволяет визуально вырезать объемы из моделей. Итогом работы будет исходная модель и множество вырезающих мешей, в комплекте с настроенными boolean модификаторами. Таким образом, моделирование происходит в неразрушающем режиме. 
- [MeshMachine](https://blendermarket.com/products/meshmachine) **$**
- [DecalMachine](https://blendermarket.com/products/decalmachine) **$** 
- [HardOPS](https://blendermarket.com/products/hardopsofficial) **$**
- [BoxCutter](https://blendermarket.com/products/boxcutter) **$**
- [Destructive extrude](https://github.com/Darcvizer/Destructive-Extrude) &mdash; аддон, доводящий до ума встроенный инструмент Блендера Extrude Manifold. Инструмент экструдирования, основанный на Булевых операциях. Аддон относится к экспериментальным, находится в бете, так что возможны непредсказуемые результаты.

## Работа со Sculpt
- [MeshFairing](https://github.com/fedackb/mesh-fairing) 
- [Sculpt Alphas Manager](https://github.com/Ryxx/Sculpt-Alphas-Manager) &mdash; менеджер альфа-изображений для скульпта. [Видео](https://www.youtube.com/watch?v=wHR8baLhnoA&ab_channel=StevenScott
) с пояснениями.
- [Brush manager](https://tingjoybits.gumroad.com/l/zLBPz) &mdash; менеджер кистей для скульпта. Цена начинается от 0$, но можно и заплатить, сколько пожелаете. 
- [Blender Sculpt Layers](https://mifth.gumroad.com/l/blender_sculpt_layers) **$** &mdash; У Blender пока нет нативных слоев для скульпта, но этот аддон их добавляет. 
- [Extended Sculpt Tools](https://biman.gumroad.com/l/dUbp) **$** 
- [SpeedSculpt](https://blendermarket.com/products/speedsculpt) **$** 
- [Paint Wheel](https://jfranmatheu.gumroad.com/l/blender_sculpt_paint_wheel) **$**  &mdash; Круговое меню а-ля Zbrush с кистями и цветами

## Ретопология
- Bsurface &mdash; построение топологии поверх других объектов с помощью annotate tool - то есть вы просто рисуете на поверхности линии и они превращаются в геометрию! 
- F2 &mdash; кнопка F на стероидах. Позволяет строить поверхности волшебным образом по двум ребрам или по трем точкам. Очень удобен для ретопологии.
- [MiraTools](https://blenderartists.org/t/miratools/637385) &mdash; многофункциональный аддон, применяется не только для ретопологии.
- [Draw X-Ray](https://bartoszstyperek.gumroad.com/l/draw_xray) **$** &mdash; (есть и бесплатная версия с меньшим фукнционалом). Устраняет одну из проблем  ретопологии в Blender - правильно отображает сетку поверх другого объекта. 
- [SpeedRetopo](https://pitiwazou-1.gumroad.com/l/speedretopo) **$** &mdash; интегрирующий аддон для других аддонов и функций Blender для ускорения процесса ретопологии, ничего нового не вносит, просто собирает все в одно удобное боковое или pie-меню. 
- [Retopoflow 3](https://blendermarket.com/products/retopoflow) **$** &mdash; есть бесплатная версия на [Github](https://github.com/CGCookie/retopoflow). Один из самых продвинутых аддонов ретопологии для Blender. Обладает рядом инструментов для современной ретопологии и даже свой собственный пользовательский интерфейс. К недостаткам стоит отнести медленную работу, особенно на тяжелых и сложных моделях. 
- [Tesselator - Quadrilateral Remeshing](https://blendermarket.com/products/tesselator) **$** &mdash; это аддон для ретопологии, который поможет вам легко создавать обычные четырехугольные и треугольные сетки из скульптов.
- [Softwrap](https://www.blendermarket.com/products/softwrap) **$** &mdash; интересный аддон с совершенно особенным подходом: с его помощью натягивается уже готовая лоуполи болванка поверх хайполи скульта. 

## Интерфейс
- [Screencast Keys](https://github.com/nutti/Screencast-Keys) &mdash; показывает нажатия кнопок на клавиатуре, а также действия с мышью

## Геоданные
- [blender-osm](https://prochitecture.gumroad.com/l/blender-osm) -&mdash;загрузка данных из OpenStreetMap
- [Maps Models Importer](https://github.com/eliemichel/MapsModelsImporter) &mdash; загрузка данных из Google Maps

## Rendering 
- [LuxCore Render](https://github.com/LuxCoreRender/BlendLuxCore/releases) 
- Поддержка движка Appleseed в аддоне [Blenderseed](https://github.com/appleseedhq/blenderseed)

## Волосы и шерсть
- [Hair Tool](https://bartoszstyperek.gumroad.com/l/hairtool) **$**

## Импорт / экспорт
- FBX import/export &mdash; must have аддон, позволяет экспортировать/импортировать FBX формат - стандартный в индустрии формат для обмена данными между 3D-программами. На данный момент осуществляется поддержка только бинарного формата.
- COLLADA DAE import/export &mdash; формат обмена данными между 3D-программами. Является текстовым, XML-совместимым.
- USD import/export &mdash; формат обмена данными между 3D-программами, созданный Pixar. Может быть как текстовым, так и бинарным (usdc и usdz).
- SVG import/export &mdash; импорт/экспорт векторной графики в открытом формате SVG. Поддерживается практически всем графическим ПО.
- STL import/export &mdash; работа с форматом STL - еще один формат обмена данными между 3D-программами. В основном используется в чертежных программах, а также в технологиях 3D-печати. Может быть как текстовым, так и бинарным.
- OBJ import/export &mdash; формат 3D-объектов от Wavefront. До появления FBX был основным форматом обмена данными. Не поддерживает анимации и разделение пивотов объектов (пивот всегда будет в центре экспортируемой сцены). Является текстовым форматом.
- glTF &mdash; новый, прогрессивный формат хранения 3D-сцен и моделей. Основан на JSON. Есть поддержка бинарной версии (формат glb). Поддерживает информацию о сцене: камеры и источники света, скелетную анимацию, материалы и шейдеры.
- [SCS Blender Tools](https://github.com/SCSSoftware/BlenderTools) &mdash; инструменты для редактирования ассетов в играх от SCS Software
- [Unreal Blender Tools](https://epicgames.github.io/BlenderTools/) &mdash; средства для работы с Unreal Engine 4

## Природные явления и живая природа
- Sapling tree generator &mdash; генератор деревьев
- Real Snow &mdash; делает снег, почти как настоящий
- IvyGen -&mdash;генгератор листвы 
- A.N.T. Landscapes &mdash; создание процедурных гор
- Sun Position &mdash; располагает и анимирует источник света в соответствии с реальным положением cолнца.  Использует географическую позицию, время и дату
- Dynamic Sky &mdash;создает процедурное небо и солнце. Можно создать сцену на открытом воздухе или в помещении с разными настройками освещения. 
- [Graswald](https://blendermarket.com/products/graswald) **$** &mdash; мощный аддон для генерации травы и листьев.
- [The Grove](https://www.thegrove3d.com/) **$** &mdash; еще один мощный аддон для гегнерации деревьев и кустов.

## Архитектура
- Archimesh
- Archipack

## Ускорение работы и дополнительные инструменты
- Node Wrangler &mdash; ускорение работы с нодами в shader editor и композере, может добавлять типичные связки нод одним кликом, объединять ноды, удалять ненужные и многое другое. 
- MeasureIT &mdash; аддон, который позволяет производить измерения. 
- Stored Views &mdash; сохраняйте и восстанавливайте пользовательские виды, точку зрения и расположение камер.
- BoltFactory &mdash; настоящая фабрика болтов и гаек.
- Extra Objects &mdash; аддон, позволяющий создавать дополнительные примитивные и не только примитивные объекты.
- tinyCAD &mdash; добавляет некоторые CAD функции в Blender.
- [Pie menu editor](https://blendermarket.com/products/pie-menu-editor) **$** - создание своих собственных круговых меню.

## Работа с камерой
- Add camera rig
- [Real camera](https://3d-wolf.com/products/camera/) &mdash; позволяет управлять камерой Blender как настоящей (автоэкспозиция, автофокус)
- [Photographer 4](https://chafouin.gumroad.com/l/HPrCY) **$** &mdash; добавляет новую физическую камеру, настройки физического освещения и интерфейсы микшера для источников света, эмиссионных материалов и миров для EEVEE, Cycles и LuxCore 2.5 ([демо](https://www.youtube.com/watch?v=q_IzKyDD2KY)). Есть бесплатная версия [Photographer 2](https://chafouin.gumroad.com/l/FWQf), но она работает на версиях до 2.9.
- [Cinepack](https://blendermarket.com/products/cinepack-pre-animated-camera-moves) **$** &mdash; Предварительно анимированные движения камеры ([демо](https://youtu.be/tWnuaHjTGcM)).
- [Fspy](https://fspy.io/) - уже не аддон, а отдельная программа, но плотно работает с Blender: позволяет выставить камеру в Blender, в точности как она установлена на снимке. 

## Работа с UV развёрткой
- Magic UV
- [TexTools](http://renderhjs.net/textools/blender/)
- [UV Packer](https://www.uv-packer.com/blender/) &mdash; это автоматизированное приложение для UV-упаковки одним щелчком мыши.
- [UV Squares](https://github.com/Radivarig/UvSquares) &mdash; инструмент для UV Editor в Blender, который преобразует выделеные шэлы UV в квадратную сетку.
- [Texel Density Checker](https://mrven.gumroad.com/l/CEIOR) &mdash; Рассчитать плотность текселей для модели с текстурой разного размера (512–4096 пикселей) или с нестандартным размером и соотношением сторон. Аддон бесплатный, но вы можете отблагодарить автора и купить его по той же ссылке.
- [Uv Packmaster 3](https://blendermarket.com/products/uvpackmaster) **$** &mdash; Один из самых эффективных упаковщиков UV ([UV Packmaster features](https://uvpackmaster.com/for-blender/features/)),([UV Packmaster FAQ](https://uvpackmaster.com/for-blender/uvpackmaster-3-faq/))
- [Zen UV](https://blendermarket.com/products/zen-uv) **$** &mdash; это не просто набор инструментов, это готовый конвейер для быстрого создания UV в Blender ([демо](https://youtu.be/Yj2SecY-c1Y))([документация](https://zen-masters.github.io/Zen-UV/)).

## "Мосты" - аддоны для обмена данными с другим софтом
- [Blender to Substance 3D Painter](https://github.com/DigiKrafting/blender_addon_substance_painter) &mdash; Мост который позволяет отправить модель(сцену, коллекцию) в Substance 3D Painter, а после текстурирования импортирует и применяет полученные текстурные карты на объекты внутри Blender.
> Для работы аддона требуется, чтобы в системе был установлен Adobe Substance 3D Painter.
- [Headus UVlayout Bridge](https://github.com/schroef/uvlayout_bridge) &mdash; аддон для экспорта объектов из Blender в Headus UVlayout и обратного импорта развёрнутого объекта. Имеет множество опций и возможностей автоматизации.
> Для работы аддона требуется, чтобы в системе был установлен Headus UVlayout.
- [HeadusUVLayout/RizomUV bridge (2 in 1)](https://titus.gumroad.com/l/B2RUVL) **$** &mdash; аддон для экспорта объектов из Blender в Headus UVlayout или RizomUV  и обратного импорта развёрнутого объекта. [(демо)](https://www.youtube.com/watch?v=XusjghptcWI)
> Для работы аддона требуется, чтобы в системе были установлены Headus UVlayout и RizomUV.

## Аддоны All in One (многофункциональные аддоны)
- [BagaPie](https://blenderartists.org/t/bagapie-modifier-free-addon/1310959) &mdash; это универсальный и бесплатный аддон, который создаёт пресеты из модификаторов и геометрических нод (Он в основном предназначен для архитектуры) ([демо](https://youtu.be/nDeK29aAUps)),([документация](https://www.f12studio.fr/bagapie)). Аддон бесплатный, но вы можете отблагодарить автора и купить его.

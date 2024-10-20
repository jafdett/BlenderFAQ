<p align="center">
  <a href="#">
    <img src="https://github.com/Mejgan4ik/Blender_CG_FAQ_images/blob/main/logo-2.png" />
  </a>
</p>
<div align="center">
  <a href="https://t.me/blender_cg_ru">
    <img alt="Telegram" src="https://github.com/Mejgan4ik/Blender_CG_FAQ_images/blob/main/Bage_TG.png" />
  </a>
<div align="left">
 
# Содержание
## Общие вопросы про Blender
- [Что такое Blender?](#whatisblender)<br>
- [Он бесплатный?](#isitfree)<br>
- [Но ведь его все равно рано или поздно купит Autodesk?](#autodeskbuy)<br>
- [На каких платформах Blender доступен?](#whatplaforms)<br>
- [Почему лучше использовать английский интерфейс программы](#whyenglish)<br>
- [Может ли Blender в 2d?](#2d)<br>
- [А что с автоматизацией?](#automation)<br>
- [О скриншотах](#screenshots)<br>
- [Каким образом можно передать модели в другие программы или получить их из них?](#importexport)<br>
- [У меня нет numpad-а, как быть?](#nonumpad)<br>
- [Какие настройки стоит сделать сразу на свежеустановленном Blender?](#initsetup)<br>
- [Как поменять единицы измерения?](#units)<br>
- [Типичные ошибки начинающих](#mistakes)<br>
## Общие вопросы про 3d графику
- [Что такое pipeline?](#whatispipeline)<br>
- [Какие методы создания 3d моделей существуют?](#3dmethods)<br>
- [Что такое hardsurface?](#whatishardsurface)<br>
- [Что такое highpoly, midpoly и lowpoly?](#whatispoly)<br>
- [Texel Density (TD) - Что это и с чем его едят?](https://habr.com/ru/articles/315146/) - статья на эту тему.
- [Так рёбра или грани?](#Edgesandfaces)<br>

## Железо
- [Какие видеокарты поддерживаются?](#gpusupported)<br>
- [Какой мне нужен компьютер для Blender?](#whatcomputer)<br>
- [Мне кажется, что Blender не рендерит на видеокарте](#nocard)<br>
## Какие еще программы могут понадобиться мне?
- [Рефборды](#refboards)<br>
- [Программы для скриншотов](#screenshots_soft)<br>
- [Конвертеры видео](#videoconverters)<br>
## Информационные ресурсы
- [С чего мне начать?](#wheretostart)<br>
- [Где искать ответы на возникающие вопросы?](#questions)<br>
- [Но ведь я не знаю английский! Как мне смотреть видео?](knowenglish)<br>
- [Стоит ли смотреть уроки, курсы и туторы для более старых версий?](#oldtutors)<br>
- [Где можно посмотреть новости про Blender?](#blendernews)<br>
- [Где можно посмотреть работы, сделанные в Blender?](#blenderworks)<br>
- [Большой список каналов и уроков](#biglist)<br>
## Контент
- [Где взять модели?](#getmodels)<br>
- [Где взять текстуры, материалы или HDRI для фонов?](#textures)<br>
- [Где можно взять звуковые эффекты и музыку для своих проектов?](#sounds)<br>
- [Ссылки на IES-библиотеки?](#iesget)<br>
## Аддоны
- [Где мне взять аддоны?](#addons)<br>
- [Как перенести настройки и аддоны в новую версию Blender?](#settingsmove)<br>
## Моделирование
- [Я хочу научиться моделировать машины, какие курсы посоветуете?](#carcreation)<br>
- [Я открыл blend-файл и вижу, что некоторые ребра модели выделены разными цветами, что это?](#edgecolor)<br>
- [Я куда-то нажал и вся моя сцена пропала, ничего на экране нет, или виден только какой-то один объект](#slash)<br>
## Риг
- [Что такое риг?](#whatisrig)<br>
- [Полезные ресурсы по ригу](#rigresources)<br>
## Скульпт
- [Что такое Sculpt?](#whatiscsuplt)<br>
- [Какие ресурсы помогут обучиться скульпту?](#sculptresources)<br>
- [Посоветуйте курсы по Sculpt для начинающих](#sculptcourses)<br>
- [Какие есть еще программы для скульптинга?](#elsesculpt)<br>
## Рендеринг
- [Что такое рендеринг?](#whatisrendering)<br>
- [Какие рендер-движки существуют для Blender?](#renderengines)<br>
- [Какой render-движок предпочесть?](#chooserender)<br>
- [Blender умеет рендерить одновременно на процессоре и видеокарте?](#gpuandcpu)<br>
## Диагностика проблем
- [Как снять логи?](#logs)<br>

# Общие вопросы
## Что такое Blender? <a name="whatisblender"></a>
**Blender** -  это opensource-программа для 3d моделирования, скульптинга, анимации, рендера и многого другого.

Посмотрите [этот ролик](https://www.youtube.com/watch?v=R7TLwKwixZA) про создание мультфильма Spring или [этот](https://youtu.be/X4MXWcx4jUA) про создание мультфильма Sprite Fright. Там возможности Blender сразу станут понятны.

## Он бесплатный?<a name="isitfree"></a>
Да, его можно просто скачать, без регистрации и SMS на сайте https://blender.org/download. Также есть архив старых версий, вот тут: https://download.blender.org. 
Можно скачивать alpha и beta версии: https://builder.blender.org/download/daily/. <br>
Более того, он распространяется под лицензией GPL v2 и его разрабатывает Blender Foundation под руководством отца-основателя: [Тона Рузендаля](https://ru.wikipedia.org/wiki/%D0%A0%D0%BE%D0%B7%D0%B5%D0%BD%D0%B4%D0%B0%D0%BB%D1%8C,_%D0%A2%D0%BE%D0%BD).

## Но ведь его все равно рано или поздно купит Autodesk? <a name="autodeskbuy"></a>
Нет, так не выйдет. Лицензия GPL v2 это исключает. 

## На каких платформах Blender доступен?<a name="whatplaforms"></a>
Windows, macOS и Linux

## Почему лучше использовать английский интерфейс программы?<a name="whyenglish"></a>
1. Подавляющее большинство обучающих курсов, уроков и статей написано именно под английский интерфейс, как следствие, вам будет намного проще повторять действия за автором, не теряя время на перевод и поиск нужных функций в русскоязычном интерфейсе.
2. В процессе изучения программы вы сможете подтянуть свой английский!
3. Так вы повышаете шанс на быстрое решение своей задачи при обращении за помощью: даже в русскоязычных сообществах английский интерфейс программы является негласным стандартом.
> Можно пойти на компромисс: оставить весь интерфейс на английском, но включить русские подсказки. Это можно сделать через меню _Preferences -> Interface -> Language (Русский)_, но оставить только чекбокс _Affect -> Tooltips_.

## Может ли Blender в 2d? <a name="2d"></a>
Сначала нужно понять, что такое 2d. Можно делать плоские модели или располагать их так, что они будут выглядеть плоскими, делать в них риг, анимацию - и это будет 2d.
Но есть и классический инструмент для 2d: это новый Grease Pencil. Это очень мощный инструмент для 2d рисования и анимации. С его помощью был сделан ролик [Hero](https://www.youtube.com/watch?v=pKmSdY56VtY). А еще с его помощью можно делать вот такие [акварели](https://www.youtube.com/watch?v=h0r7GdC5Bu0).

## А что с автоматизацией? <a name="automation"></a>
У Blender есть богатый Python API. С помощью Python можно писать программы, которые работают прямо внутри Blender и имеют доступ практически ко всем его функциям. Документация по API доступна здесь: https://docs.blender.org/api/current/. Именно с помощью Python API написано большинство addon-ов для Blender. 

## О скриншотах <a name="screenshots"></a>
При общении в чатах и на форумах для того, чтобы проиллюстрировать свой вопрос, часто требуется сделать скриншот или даже записать скринкаст. 
Многие не знают, что в операционных системах уже есть встроенные средства для этого, и фотографируют экран на телефон. Так делать не нужно: качество картинки сильно страдает, появляется муар, и понять, что на ней изображено, довольно сложно. 
Вместо этого нужно использовать средства ОС:
* **Windows**: нажмите <kbd>Win</kbd> + <kbd>G</kbd> и выберите нужный пункт;
* **macOS**: нажмите <kbd>Command</kbd> + <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>4</kbd> (область экрана сразу попадет в буфер обмена) или <kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>3</kbd> или <kbd>4</kbd> (будет сохранен в файл);
* **Linux**: зависит от среды рабочего стола. Чаще всего программы для создания скриншотов используют клавишу <kbd>Print Screen</kbd>.

Кроме того, существуют специальные програмы для этого:
- клиент Яндекс.Диск содержит встроенное средства захвата экрана;
- ShareX (только Windows), есть версия в Steam;
- LightShot - кроссплатформенная;
- Monosnap - кроссплатформенная.

## Каким образом можно передать модели в другие программы или получить их из них? <a name="importexport"></a>
Рано или поздно возникает вопрос про передачу моделей из Blender в другие программы либо про импорт из других программ в Blender. 
Рекомендуется для этого использовать формат **FBX**: де-факто это стандарт индустрии, все современные 3d программы его поддерживают. К сожалению, это закрытый формат, разработанный Autodesk, поэтому совместимость между программами может быть неполной. Для того, чтобы иметь возможность делать импорт-экспорт, нужно включить аддон в настройках. Вместе с Blender в комплекте идут встроенные аддоны для импорта/экспорта других форматов: FBX, OBJ, PLY, STL, SVG.

## У меня нет numpad-а, как быть? <a name="nonumpad"></a>
Включите опцию эмуляции numpad в настройках: _Preferences -> Input -> Emulate Numpad_.

## Какие настройки стоит сделать сразу на свежеустановленном Blender? <a name="initsetup"></a>
1. Если у вас нет numpad, то сделайте как написано пунктом выше.
2. Включите сразу Orbit Around Selection: _Preferences -> Navigation -> Orbit Around Selection_. Тогда при вращении вид всегда будет центрироваться относительно выбранного.

## Как поменять единицы измерения? <a name="units"></a>
Есть [видео](https://www.youtube.com/watch?v=IggufPpkMCc) про это. 

## Типичные ошибки начинающих <a name="mistakes"></a>
- Слишком темные сцены в финальных рендерах. Света нужно много, хорошую модель можно испортить плохим светом, а плохую модель можно выгодно подать только за счет света. Светом можно творить не хуже, чем остальными изобразительными средствами. Изучайте постановку света, в этом вам поможет [курс Blender Guru](https://www.youtube.com/watch?v=Ys4793edotw&list=PLjEaoINr3zgH9vCr47kSS5W8PEJBNIiwK). Также можно смотреть любые книги и курсы по фотографии - там этому много уделяется внимания. 
- Игнорирование референсов, попытки сделать все "из головы". Многие считают, что если использовать референсы, то это уже будет не их работа, а как будто это будет плагиат. Но 3d штука совсем непростая, и пытаться сделать сразу все - очень сложно, кроме того, дизайн персонажей, механизмов или локаций - это отдельные дисциплины, которым тоже надо учиться, все сразу точно не выйдет. Поэтому можно начать просто с поиска референсов и воспроизведения их в 3d. Следующий этап - это комбиниирование своей сцены из набора референсов. Но работать вообще без референсов не рекомендуется и даже профессионалы так не делают. 
- Слишком большой поликаунт, там, где он не нужен. Всегда поликаунт должен отвечать требованиям сцены и чем он ниже - тем лучше. Если можно одно и то же передать тысячью полигонов или миллионом, то, конечно, лучше меньше, а не больше. Например на сцене с танком совершенно не нужна резбьа на болтах в его обшивке. Также не нужны вообще никакие поверхности, которых не будет видно на финальной модели.
- Использование не самой последней стабильной версии. Не нужно сидеть на старых версиях, ведь Blender бесплатный и за установку самой последней версии вы не заплатите и копейки. А баги будут исправлены и новые возможности будут радовать глаз.
- Открыть более новый blend-файл в старой версии Blender. Тут возможны любые спецэффекты, вплоть до сбоя Blender и аварийного выхода. Лучше открыть в той же версии, в которой делался файл изначально. В обратную сторону, все должно быть хорошо, то есть файлы, созданные в более ранних версиях - в более поздних будут открываться и ничего взрываться не должно. 
- Попытки сразу сделать сложную модель. Попробуйте что-то более простое. Понятно, что хочется сразу сделать шедевр, но так вряд ли выйдет, нужно идти от простого к сложному.
- Переключение интерфейса на русский язык. Да, все мы любим русский язык, но масса уроков на английском, плюс в сообществе принят английский интерфейс. Вам придется все время в голове переводить название пунктов меню и кнопок и не факт, что вы это сделаете правильно. Плюс ваши скриншоты, если вы запросите помощь, будут трудны для восприятия. Но вы можете включить перевод только для подсказок по наведению мышью (tooltips).  
- Рендер видео в mp4 или avi файл. Так делать не надо, хоть Blender это и умеет. Дело в том, что рендер анимации дело очень долгое и если произойдет сбой (например кончится место на диске), то вообще весь результат будет потерян и придется начать с начала. А если вы будете рендерить видео в png покадрово (опция по-умолчанию), то потом сможете это все собрать в видеоредакторе без всяких проблем в ту же самую видеопоследовательность. При этом при сбое в Blender у вас останутся все кадры, которые он отрендерил до этого и вы сможете начать снова с места сбоя.
- DirectX vs OpenGL карты нормалей. Отличаются они друг от друга инвертированным зеленым каналом. В итоге модель с несоответствующей картой будет выглядеть странно, те места, которые должны быть вдавлены - будут выпуклыми и наоборот. Разные программы работают с разными форматами и надо знать, какой из них у вас есть. Понятно, что сконвертировать один в другой просто, это можно сделать и в Blender с помощью  инвертирования зеленого канала в материалах. Blender использует OpenGL формат. 
- Если что-то идет не так, модификатор неправильно применяется, выглядит все как-то странно, то первое что надо сделать - применить трансформы. То есть нажать <kbd>CRL</kbd> + <kbd>A</kbd> и там выбрать Rotation & Scale. Делать это надо в Object mode.
- Если предыдущий совет не помог и все равно все выглядит как-то странно, то проверьте куда направлены нормали. Для этого в меню Viewport Overlays надо нажать галочку Face Orientation
- Следующее, что часто случается - двойная геометрия. Чтобы избавиться от нее - выделите все вершины, которые вы подозреваете в двойственности и нажмите M, после этого выберете By distance. Это действите объединит вершины, которые находятся между собой на определенной дистанции. Эту дистанцию можно регулировать через меню в левом нижнем углу экрана, которое появится сразу после операции.
- Z-файтинг. Ситуация, когда у вас одно и то же место в пространстве занимает две или больше поверхности. Выглядит это как мерцание поверхности при перемещениях камеры или объекта. Найдите и удалите дубликат.
- Использование видеокарт от AMD. Нет, ну они в целом работают, и даже в Cycles с недавнего времени, благодаря HIP, стало сильно лучше, но, все же, если еще не купили - лучше возьмите карту от Nvidia, вообще не пожалеете. Подробнее смотрите в разделе про железо. 

  

# Общие вопросы про 3d графику

## Что такое pipeline? <a name="whatispipeline"></a>
**Pipeline** (или конвейер) - это название всего набора действий для получения готового результата. Этот набор охватывает всё от самого начала производства продукта и до его конца. Pipeline также накладывает определенные требования на программы, используемые в производстве продукта, и даже на методы работы внутри этих программ. 
Пример типичного pipline для создания игрового персонажа:
![3d pipeline](http://www.plantuml.com/plantuml/svg/FP1DIiOm68JtFKNSwSTtYEyIkd8JQC0kKgJc0Ft1RXJKbU1AFK6q5aD_sYlCUoE745m4oZCFymuztJbTELkKkTMtsPcxCTOegvsf2fqT55xXyICT5apmsO7a3HjMwJ5Yb_QwF9SQGHegAvLmLFo-PxZ8mr6HUNpHsAG1qmkbsC6I5yoi8Q4n497X0nDRPda4YoCZVCSeBTMTR-ORUEo9OKmlhnIxFNxnJQsc64Uc59-SCN5EArqSoHaKFKy6Z778_v6GLYJm79q5NlfuxsJAFFsZFm00)

## Какие методы создания 3d моделей существуют? <a name="3dmethods"></a>
- Полигональное моделирование или low poly: просто вытягиваете полигоны, манипулируете вершинами, ребрами и поверхностями. 
- Subdiv: применяется модификатор Subdivision surface - сразу виден highpoly, но при этом работа с моделью идет через low poly. Применяются поддерживающие петли (edge loops) для придания остроты нужным граням. 
- Boolean: придание формы за счет вырезания, добавления и пересечения геометрии. 
- Скульпт (чаще применяют для органики): работа с high poly моделью без учета топологии при помощи инструментов, напоминающих инструменты для работы с пластилином или глиной. 
- процедурное моделирование: построение моделей программными методами. Например с помощью geometry nodes в Blender или в Houdini.
- Построение моделей в CAD программах с последующим импортом и ретопологией в полигональных программах, таких как Blender.
- NURBS.
- Metaballs: создание геометрии с помощью меташаров - объектов, имеющих свойство объединяться друг с другом при приближении на определенное расстояние. Позволяет быстро прототипировать модели. В современном моделировании метод используется редко, чаще всего для получения базовых форм перед скульптом. 

## Что такое hardsurface?<a name="whatishardsurface"></a>
Hardsurface - это обобщенное название моделей с "твердыми" поверхностями. Например, ими могут быть оружие, предметы окружения или автомобили.
В принципе, всё, что нас окружает, делится на hardsurface и органику.
Для моделирования hardsurface применяется множество методов, описанных выше, а для моделирования органики чаще всего используется скульпт.

## Что такое highpoly, midpoly и lowpoly?<a name="whatispoly"></a>
Это условные названия уровней количества полигонов в модели:
- **highpoly**: самый высокий уровень, он может начинаться от 150 тысяч и выше, до десятков миллионов полигонов. Обычно модели с таким количеством полигонов не являются конечным результатом и получаются после скульпта или SubDiv моделирования, а также требуют ретопологию для дальнейшего использования в играх или анимации;
- **midpoly**: среднее количество полигонов;
- **lowpoly**: низкополигональная модель, условно от 2 тысяч до 100 тысяч полигонов. 
Для разных областей использования границы количества полигонов могут сдвигаться. Например, для мобильных игр требуются модели с как можно меньшим количеством полигонов, в то время как для настольных компьютеров это количество может быть гораздо выше, но в том и другом случае модель будут называть low poly. 

## Так рёбра или грани?<a name="Edgesandfaces"></a>
Очень часто люди путают эти понятия, и это сбивает многих с толку, когда например идёт обсуждение вопросов в чатах.

Давайте раз и навсегда разберёмся с этим вопросом и поставим в нём точку.

Оба эти понятия чётко определены в стереометрии. **Стереометрия** — раздел евклидовой геометрии, в котором изучаются свойства фигур в пространстве.

Многогранник представляет собой геометрическое тело, ограниченное конечным числом плоских многоугольников, любые два из которых, имеющие общую сторону, не лежат в одной плоскости. При этом сами многоугольники называются **гранями**, их стороны – **ребрами** многогранника, а их вершины – вершинами многогранника. 

Фигура, образованная всеми гранями многогранника, называется его поверхностью (полной поверхностью), а сумма площадей всех его граней – площадью (полной) поверхности. 

Например **Куб** – это многогранник, имеющий шесть граней, которые являются равными квадратами. Стороны квадратов называются ребрами куба, а вершины – вершинами куба.


# Железо 
## Какие видеокарты поддерживаются?<a name="gpusupported"></a>
Blender имеет ряд условий относительно поддержки видеокарт. В основном, работают почти все современные варианты, доступные на рынке.

### NVIDIA
- **CUDA**: видеокарты новее _GeForce 400_ с поддержкой CUDA **3.0 и выше**;
- **OptiX**: видеокарты с поддержкой CUDA **5.0 и выше**, а также с драйвером **470+**. Основная масса поддержки - модели RTX.

> **ВАЖНО:** на компьютерах с установленной macOS последняя версия системы, на которой можно использовать видеокарту NVIDIA с поддержкой CUDA - **10.13.6**.

### AMD
- **OpenCL**: видеокарты на архитектуре **CGN 2 и новее**. Для корректной работы на Linux должен использоваться PRO драйвер.
- **HIP**: видеокарты на архитектуре **RDNA** и новее, а также с драйвером **AMD Radeon Software 21.12.1** или **AMD Radeon PRO Software 21.Q4**. Появилось в Blender 3.0.

> **ВАЖНО:** поддержка OpenCL для Windows и Linux **закончилась** в версии 2.93. На компьютерах с установленной macOS последняя версия системы, на которой можно использовать видеокарту AMD - **10.13.6**.

### Apple
- **Metal**: компьютеры Apple на базе Apple Silicon, а также на базе Intel с видеокартами AMD с установленной macOS 12.2 и новее, однако для поддержки всего актуального функционала API требуется macOS 13.0. Появилось в Blender 3.1.

### Intel
- **oneAPI**: видеокарты Intel Arc A-серии на архитектуре Xe HPG. Появилось в Blender 3.3.

### Таблица совместимости

|               | Версия Blender    | Windows   | Linux | macOS (Intel)     | macOS (ARM)   |
|---------------|:-----------------:|:---------:|:-----:|:-----------------:|:-------------:|
| **CUDA**      | все               | +         | +     | + (до 10.13.6)    |               |
| **OptiX**     | 2.81+             | +         | +     |                   |               |
| **OpenCL**    | все до 2.93       | +         | +     | + (до 10.13.6)    |               |
| **HIP**       | 3.0+              | +         | +     |                   |               |
| **Metal**     | 3.1+              |           |       | + (с 12.3)        | + (с 12.2)    |
| **oneAPI**    | 3.3+              | +         | +     |                   |               |

## Какой мне нужен компьютер для Blender?<a name="whatcomputer"></a>
Это комплексный вопрос. Многое зависит от того, что вы собираетесь делать в Blender. <br>
Системные требования довольно щадящие. Они указаны на [официальном сайте](https://www.blender.org/download/requirements/).

В первую очередь стоит обратить внимание на CPU, память и видеокарту. 
Некоторые процессы в Blender многопоточные (например, Cycles) и поэтому могут использовать все доступные ядра процессора. Стало быть, чем больше ядер у CPU, тем лучше. 

Видеокарта - лучше всего работает GPU от Nvidia. Понятно, что самые последние серии и более высокого уровня работают лучше всего. Но даже 950Ti все еще может помочь в рендерах. 

Память. Ее не бывает много. Blender будет работать и на 8Gb, но лучше 16, а еще лучше 32. 
Также желателен SSD. 

Для скульта мощность видеокарты не так важна, можно жить даже на встроенной графике, но тут играют решающую роль память и CPU. 

## У меня есть дискретная видеокарта, NVIDIA 3060. Запускаю рендер Cycles и вижу, что она не используется, а процессор загружен на 100%<a name="nocard"></a>
Рендер на видеокарте не включен в настройках и его надо просто включить: Preferences - System - Render device.

## Да, я включил рендер на видеокарте в настройках, но по графикам нагрузки Windows все равно вижу, что видеокарта не используется. 
Возможно вы смотрите не туда, в графике GPU надо нажать на выпадающий список и там выбрать CUDA. 
![Cuda screenshot](https://github.com/jafdett/BlenderFAQ/blob/main/cuda.jpg)


# Какие еще программы могут понадобиться мне?
## Рефборды<a name="refboards"></a>
Класс программ для сбора рефов, по сути это просто просмотрщики изображений, но не каждого по отдельности, а собранных вместе на доску. Очень полезно при конструировании сцены. 
Самая популярная - **PureRef**. Ее можно взять бесплатно на сайте https://www.pureref.com.
Вторая открытая программа для этого - Kuadro. Ее можно взять здесь: http://kruelgames.com/tools/kuadro.

## Программы для скриншотов<a name="screenshots_soft"></a>
Смотрите [здесь](#screenshots).

## Конвертеры видео<a name="videoconverters"></a>
Перегонка видео из одного формата в другой, с перекодированием или без него, редактирование и наложение эффектов. 
- Бесплатная, opensource Avidemux: https://avidemux.org

# Информационные ресурсы
## С чего мне начать?<a name="wheretostart"></a>
Лучше всего начать изучение программы с «основ», которые коротко, но исчерпывающе изложены в официальном курсе от создателей программы.

[Основы Blender 2.8 на английском языке](https://www.youtube.com/playlist?list=PLa1F2ddGya_-UvuAqHAksYnB0qL9yWDO6)

[Тот же курс, но переведенный на русский](https://www.youtube.com/playlist?list=PLW-edvk8DPoAiurQIgT06jfR720tP3GFC)

Далее стоит обратить внимание на ряд бесплатных курсов, в которых вы сможете более подробно изучить инструменты, а также различные техники, методы и подходы к решению тех или иных задач в ходе моделирования конкретной сцены:

- Мини-курс [«Blender для новичков»](https://www.youtube.com/watch?v=5KY7PXalXKU&list=PLrsq-o51mMFGdzc7VTGw7Kq7G-qTguKkm) от VideoSmile
- Видео [«Blender за 1 час!»](https://www.youtube.com/watch?v=BWRNNXa-S3Y) от VideoSmile
- [Курс по основам Blender 2.8+](https://www.youtube.com/playlist?list=PLuuJ7EJSjEfMETY8txzRpXHPH08Eg7kA6) от Артёма Слаквы
- "Wagon", [Курс по моделированию кареты](https://www.youtube.com/watch?v=VlvK6Dchd2o&list=PL4Fzlpumqxe2kPhvLlVBN0CXLa5ovk9qA&index=1) от Университета Кайно  
- [Курс по моделированию пончика](https://www.youtube.com/watch?v=TPrnSACiTJ4&list=PLjEaoINr3zgEq0u2MzVgAaHEBt--xLB6U) в Blender 2.8+ от Blender Guru
- [Курс по моделированию пончика в переводе на русский](https://www.youtube.com/watch?v=ryq4Vj7G5NA&list=PLkxXQ3ugQK2PEUO9a2_FZMmXGXy83P4XN) от Дениса Кожара
- [Мини-курс по моделированию стула](https://www.youtube.com/watch?v=Hf2esGA7vCc&list=PLjEaoINr3zgEL9UjPTLWQhLFAK7wVaRMR) в Blender 2.8+ от Blender Guru
- [Курс по UV развёртке](https://www.skillshare.com/classes/Blender-2-8-UV-Mapping/722747378) от Darrin Lile (Blender Foundation Certified Instructor)
- [Курс по созданию персонажа (моделирование, текстурирование, РИГ)](https://www.youtube.com/playlist?list=PLok698dKQ_Hj10eKx73qPJRktkB1r8SN5) от TomCAT - Characters, Art and Tutorials
- [Курс по текстурированию и материалам](https://www.udemy.com/course/become-a-material-guru-in-blender-cycles/) От Joakim Tornhill (**платный**)
- Blender Избушка [Бесплатный курс по созданию комплексных сцен в программе Блендер](https://www.youtube.com/watch?v=wsyiPcvTbR4&list=PLOVSu7-KesPiP5ABIc8owgMgNH9q16x1k&pp=iAQB) от Андрея Соколова
- Курс «Фабрика». [Обучение Blender с нуля.](https://www.youtube.com/watch?v=Q8Q8HBj-Ua8&list=PLn6DikVGbeEiJFNb2_wfV2zg4BDm8xvsQ&pp=iAQB) от Knower School
- Мини-курс ["Blender для новичков"](https://www.youtube.com/watch?v=5KY7PXalXKU&list=PLrsq-o51mMFGdzc7VTGw7Kq7G-qTguKkm) от VideoSmile
- [Blender 4.0 Курс "Пончик 🍩"](https://www.youtube.com/watch?v=3Ru613FJDXU&list=PLkxXQ3ugQK2N2PPxmeOivCT4tP4ne_V1y) - на русском для начинающих. Обновлённый курс от Дениса Кожара
- Бесплатный курс для начинающих [«Dungeon»](https://www.youtube.com/watch?v=eyCW2_1RYNQ&list=PL4Fzlpumqxe2Iq5agLgd5WLULW0ydj1wS) от университета Kaino
- Мини-курс ["Blender 3d illustration 1.0"](https://www.youtube.com/watch?v=j7h5WO5V1rw&list=PLbZPZS35Led3g2cP2wxVEljiaj_aougM2) от Vladimir Lavrinenko
- Курс [«Енот»](https://www.youtube.com/watch?v=fDOotm6bxUY&list=PLn6DikVGbeEgMvn_JJyX1Rnrt3Wlj0rvk). Скульптинг персонажа в Blender от Knower School
- [Тропическая сцена в Blender](https://youtu.be/CsNgljHnbhA) от Артёма Слаква
- Мини-курс ["Blender для новичков"](https://www.youtube.com/watch?v=LefGzhpue2o&list=PLkK_aXLst8Xyn-jxMs4rApy7gjCEPBKFX) от Артёма Слаква
- Курс по созданию автомобиля (**платный**) от CG Maters ([Gumroad](https://cgmasters.gumroad.com/l/3d-cars), [Blender Market](https://blendermarket.com/products/3d-cars-inside-and-out-in-blender))
- Отличный [плейлист](https://www.youtube.com/playlist?list=PLIY3FrDmckDdPx6j8oVSkKyPsRAleXWSI) с уроками по одному из самых популярных методов моделирования "под сабдив" (Subdivision Surface) от CG Lama
- Свежий [курс для начинающих](https://www.youtube.com/playlist?list=PL9XnkFunepA_e3ExUKOqwJZURaatY5rL4) от Александра Родионова, по ходу изучения которого вы получите готовую сцену с роботом.
- Полноценный курс по моделированию стилизованного [персонажа](https://www.youtube.com/playlist?list=PL9XnkFunepA_e3ExUKOqwJZURaatY5rL4) от Daniel Kreuter.
- [Полуторачасовое видео про текстурирование от BlenderGuru](https://www.youtube.com/watch?v=uHCJoNEWjXo)

## Где искать ответы на возникающие вопросы?<a name="questions"></a>
1. Ответы на большинство вопросов можно найти в официальной документации к программе: https://docs.blender.org/manual/en/latest/
2. Используйте Google и Яндекс! Сформулируйте вопрос (лучше на английском), и вперед - найдется всё!
3. То же самое актуально и для YouTube: просто ищите там по ключевым словам вашего вопроса и добавьте "Blender". Например, если вам нужно узнать что-то про ретопологию, запрос будет такой: "Retopology Blender".
4. Приходите в Телеграм-чат [Blender_cg_ru](https://t.me/blender_cg_ru) - там помогут. 

## Но ведь я не знаю английский! Как мне смотреть видео?<a name="knowenglish"></a>
Яндекс [анонсировал](https://yandex.ru/blog/company/smotrite-po-russki-yandeks-zapustil-zakadrovyy-perevod-video) технологию машинного перевода видео на YouTube.

## Стоит ли смотреть уроки, курсы и туторы для более старых версий?<a name="oldtutors"></a>
Между версиями 2.7x и 2.8+ действительно существует огромная разница, ведь в версиях новее 2.80 включительно был полностью переработан интерфейс, и обучаться работе в них на основе версии 2.7х будет неэффективно. К тому же версии старее 2.80 попросту морально устарели (не обновляются разработчиком).

Что же касается версий 2.8х, 2.9х, 3.х, то в вопросе интерфейса они практически идентичны, и вы с лёгкостью сможете ориентироваться во всех трёх линейках.

На данный момент [актуальной стабильной версией](https://www.blender.org/download/) является версия 3.х, но вы можете смело пользоваться учебным материалом на базе 2.8х+ версий. Только учтите, что некоторые функции всё же меняли своё местоположение в ходе эволюции, и если ваша версия новее той, которая у автора видео, то возможно вам придётся поискать её новое место.

## Где можно посмотреть новости про Blender? <a name="blendernews"></a>
- официальный [сайт](https://www.blender.org/news/)
- официальный [канал на YouTube](https://www.youtube.com/user/BlenderFoundation)
- [канал](https://www.youtube.com/c/BlenderDevelopers) разработчиков

## Где можно посмотреть работы, сделанные в Blender?<a name="blenderworks"></a>
- [Artstation](https://artstation.com)
- [Render.ru](https://render.ru)
- [Blenderartists.org](https://blenderartists.org)
- [Blender Nation](https://www.blendernation.com)

## Большой список каналов и уроков <a name="biglist"></a>
### Зарубежные авторы:
[Blazraidr](https://www.youtube.com/c/blazraidr)<br>
[Blender Animation Studio](https://www.youtube.com/c/BlenderAnimationStudio)<br>
[Blender Sensei](https://www.youtube.com/c/BlenderSenseiOfficial)<br>
[BlenderDiplom](https://www.youtube.com/c/BlenderDiplom)<br>
[CG Geek](https://www.youtube.com/c/CGGeek)<br>
[CG Masters](https://www.youtube.com/user/blengine)<br>
[Grant Abbitt](https://www.youtube.com/c/GrantAbbitt)<br>
[masterxeon1001](https://www.youtube.com/c/masterxeon1001)<br>
[YanSculpts](https://www.youtube.com/c/yansculpts)<br>
[CG Boost](https://www.youtube.com/c/CGBoost)<br>
[CGRogue](https://www.youtube.com/c/3DBanditTutorials)<br>
[Blender Guru:](https://www.youtube.com/c/BlenderGuruOfficial)<br>
[Remington graphics:](https://www.youtube.com/c/RemingtonCreative)<br>
[CG Cookie](https://www.youtube.com/c/CGCookieBlender)<br>
[Sardi Pax](https://www.youtube.com/c/SardiPax/)<br>
[Wayward Art Company](https://www.youtube.com/c/WaywardArtCompany)<br>
[MaxEdge](https://www.youtube.com/c/MaxEdge420)<br>
[Sketching in blender](https://www.youtube.com/c/sketchinginblender)<br>
[Polyfjord](https://www.youtube.com/c/Polyfjord)<br>
[Joey Carlino](https://www.youtube.com/c/JoeyCarlino)<br>
[CrossMind Studio](https://www.youtube.com/c/CrossMindStudio)<br>
[IanHubert](https://www.youtube.com/user/mrdodobird/videos)<br>
[Midge Sinnaeve](https://www.youtube.com/channel/UCChYCkbgArLsCl5DWlxuKhQ/videos)<br>
[CGMatter](https://www.youtube.com/channel/UCy1f4m64dwCwk8CBZ_vHfPg/videos)<br>
[Default Cube](https://www.youtube.com/channel/UCdpWKLNfbROyoGPV46-zaUQ/videos)<br>
[SouthernShotty](https://www.youtube.com/channel/UCOWrbryuVEPUMSSgayuLURg/videos)<br>
[Gleb Alexandrov](https://www.youtube.com/user/GlebAlexandrov/videos)<br>
[Ducky 3D](https://www.youtube.com/channel/UCuNhGhbemBkdflZ1FGJ0lUQ/videos)<br>
[Royal Skies LLC](https://www.youtube.com/channel/UC2U5mRfclG1Rrr1ztNkpGKA/videos)<br>
[Chris Prenninger](https://www.youtube.com/user/chrisprenn/videos)<br>
[Jayanam](https://www.youtube.com/user/jayanamgames/videos)<br>
[FlippedNormals](https://www.youtube.com/user/FlippedNormalsTuts/videos)<br>
[Curtis Holt](https://www.youtube.com/channel/UCzghqpGuEmk4YdVewxA79GA/videos)<br>
[Polygon Runway](https://www.youtube.com/channel/UCGSJevmBuDyxjLLOBNaYMGA/videos)<br>
[Steven Scott](https://www.youtube.com/channel/UCiy-QcXrvu9hhe4arymNcfw/videos)<br>
[Blender NPR](https://www.youtube.com/user/blendernpr/videos)<br>
[Martin Klekner](https://www.youtube.com/user/CamperCz/videos)<br>
[Danny Mac 3D](https://www.youtube.com/user/djmccabie/videos)<br>
[Daniel Krafft - DSO](https://www.youtube.com/channel/UCojEXrCBzO-cP2N5YlRcrWw/videos)<br>
[Imphenzia](https://www.youtube.com/user/ImphenziaMusic/videos)<br>
[Saqib Hussain](https://www.youtube.com/user/sh2708mf/videos)<br>
[CBaileyFilm](https://www.youtube.com/channel/UCXguhzOm29mBTYDuxKjxn5A/videos)<br>
[Josh Gambrell](https://www.youtube.com/c/JoshGambrell/videos)<br>
[Peter France](https://www.youtube.com/c/PeterFrance/videos)<br>
[Cédric Lepiller](https://www.youtube.com/c/pitiwazou/videos)<br>
[FlyCat](https://www.youtube.com/channel/UCnXU0MjnApXHZkf3uGYbLSA/videos)<br>
[Stylized Station](https://www.youtube.com/c/StylizedStation/videos)<br>
[Iridesium](https://www.youtube.com/c/Iridesium/videos)<br>
[Lightning Boy Studio](https://www.youtube.com/channel/UCd9i2MKimSaKezat1xkn8-A/videos)<br>
[Giulia Marchetti](https://www.youtube.com/c/GiuliaMarchetti3d/videos)<br>
[CG Fast Track](https://www.youtube.com/c/CGFastTrack/videos)<br>
[3DGreenhorn](https://www.youtube.com/c/3DGreenhorn/videos)<br>
[Bad Normals](https://www.youtube.com/c/BadNormals/videos)<br>
[Kevandram](https://www.youtube.com/user/kevandram/videos)<br>
[Noggi](https://www.youtube.com/c/Noggi_Video/videos)<br>

### Русскоязычные авторы:
[Blender 3D - уроки](https://www.youtube.com/c/Blender3dUa)<br>
[Denis Kozhar](https://www.youtube.com/channel/UCf2LGgt4l6NoroDrHx8uD_Q)<br>
[fastaboutblender](https://www.youtube.com/user/fastaboutblender)<br>

# Контент
## Где взять модели?<a name="getmodels"></a>
- https://blendswap.com
- https://blenderkit.com
- https://sketchfab.com
- https://cgtrader.com
- https://free3d.com
- https://downloadfree3d.com
- https://turbosquid.com
- https://open3dmodel.com
- https://renderpeople.com
- https://3dsky.org/
- https://www.3ds-models.org
- https://www.blender-models.com/

## Где взять текстуры, материалы или HDRI для фонов?<a name="textures"></a>
- https://blenderkit.com
- http://blendermada.com
- https://polyhaven.com
- https://ambientcg.com
- https://sharetextures.com
- https://cgbookcase.com
- https://3dtextures.me
- https://texturebox.com
- https://texture.ninja
- https://freepbr.com
- http://hdrlabs.com/sibl/archive.html
- https://3dassets.one
- https://www.3dxo.com
- https://texturefun.com
- https://c4dcenter.com
- https://wildtextures.com
- https://www.textures.com/ [$]
- https://matlib.gpuopen.com
- https://www.scanslibrary.com [$]
- https://www.poliigon.com [$]
- https://texturing.xyz [$]
- https://www.sketchuptextureclub.com/textures
- https://www.archinspirations.com/materials
- https://www.texturecan.com
- https://www.solarsystemscope.com/textures/
- https://hdrmaps.com/hdris
- https://www.hdri-hub.com/hdrishop/freesamples/freehdri
- https://hdri-skies.com/
- https://www.ihdri.com

## Где можно взять звуковые эффекты и музыку для своих проектов?<a name="sounds"></a>
- https://freesound.org/
- https://zvukogram.com
- https://zvukipro.com
- https://motionarray.com/browse/sound-effects/free/
- https://uppbeat.io/
- https://gamesounds.xyz
- https://soundbible.com
- https://99sounds.org
- https://www.freesfx.co.uk
- https://mixkit.co/free-sound-effects/
- https://mixkit.co/free-stock-music/
- https://www.unminus.com/

## Ссылки на IES-библиотеки?<a name="iesget"></a>
- https://ieslibrary.com/en/home

 [Видеоурок](https://www.youtube.com/watch?v=l-uz3BHOqNo) о том, как использовать IES-файлы

# Аддоны
## Где мне взять аддоны?<a name="addons"></a>
Многие полезные аддоны поставляются вместе с программой, но по умолчанию не активированы. Их можно активировать в настройках программы (Edit/Preferences/add-ons).
Также существуют ресурсы, на которых авторы выкладывают свои аддоны.
Многие из них являются платными, но в большинстве случаев плата за них вполне оправдана.
- [Blender market](https://blendermarket.com/categories/scripts-and-addons)
- [Gumroad](https://gumroad.com/)
- [Github](https://github.com)

Более подробно про аддоны смотрите [дополнительный документ](https://github.com/jafdett/BlenderFAQ/blob/main/Addons.md)

## Как перенести настройки и аддоны в новую версию Blender? <a name="settingsmove"></a>
Blender обновляется и развивается очень динамично, вследствие чего регулярно появляются новые версии программы. Однако, скачав с сайта Blender очередной релиз, всегда необходимо настроить его удобным для себя образом.

Для того, чтобы вручную не восстанавливать все пользовательские настройки и не переустанавливать аддоны, в новую версию Blender можно быстро перенести настройки и аддоны из предыдущей версии. Для этого:
- при первом запуске Blender в окне с заставкой можно нажать на кнопку *“Load 2.ХХ Settings”*. После чего в текущую версию Blender будут перенесены настройки и аддоны из версии, указанной на кнопке;
- или же, если вы хотите контролировать процесс переноса настроек самостоятельно, можно вручную перенести файлы с настройками и аддонами.
Для этого нужно на вашем компьютере открыть следующую папку:

  **Windows**
  ```
  C:\Users\<имя пользователя>\AppData\Roaming\Blender Foundation\Blender
  ```
  **macOS**
  ```
  /Users/<имя пользователя>/Library/Application Support/Blender
  ```
  **Linux**
  ```
  <расположение home пользователя>/.config/blender
  ```

  В ней будет перечень папок с названиями различных версий Blender, ранее установленных на вашем компьютере. Нужно здесь же сделать копию папки с версией, из которой вы хотите взять настройки и аддоны, и переименовать ее в номер новой версии Blender.

# Моделирование
## Я хочу научиться моделировать машины, какие курсы посоветуете? <a name="carcreation"></a>
[Master Car Creation in Blender](https://www.blendermarket.com/products/master-car-creation-in-blender)

## Я открыл blend-файл и вижу, что некоторые ребра модели выделены разными цветами, что это? ?<a name="edgecolor"></a> 
Это способ передать Blender, что с этими ребрами надо делать нечто особенное, а что именно - ниже:

- ![#f03c15](https://placehold.co/15x15/f03c15/f03c15.png) `Красный` - шов развертки UV, значение: on/off
- ![#1589F0](https://placehold.co/15x15/1589F0/1589F0.png) `Синий` - вес для модификатора Bevel, значение от -1 до 1. 0 - Веса нет, 1 - максимальный вес
- ![#1589F0](https://placehold.co/15x15/B70A8F/B70A8F.png) `Пурпурный` - Crease, способ сообщить кривизну грани без дополнительной геометрии, что даст более или менее плавный переход между плоскостями, расположенными под углом друг к другу. Работает только вместе с Subdivision Surface модификатором, значения от 0.0 ло 1.0
- ![#1589F0](https://placehold.co/15x15/02F6EB/02F6EB.png) `Голубой` - Sharp - делает ребро острым, значения: on/off
- ![#1589F0](https://placehold.co/15x15/78F37A/78F37A.png) `Зеленый` - Freestyle. Если включен Freestyle render в настройках рендера, то на финальной картинке это ребро будет изображено линией. Обычно применяют для отображения сетки на финальном рендере или для получения изображений "рисованного вида". Значение on/off.

Эти значения можно задавать в Edit Mode, через контекстное меню, вызываемое по <kbd>Ctrl</kbd> + <kbd>E</kbd>. Этим же способом можно их и очистить. Но, обычно, они выставлены на модели не просто так, а выполняют вполне определенную функцию. 

## Я куда-то нажал и вся моя сцена пропала, ничего на экране нет или виден только какой-то один объект<a name="slash"></a>
Вы включили режим изоляции текущего объекта (Local view). Полезный режим, позволяет скрыть все ненужное и сосредоточиться только на выделенном объекте. 
Включается и выключается с помощью Numpad <kbd>/</kbd>. Также в этой ситуации может помочь кнопка <kbd>Home</kbd> -  она устанавливает текущий вид так, чтобы в него попали все объекты сцены. 


# Риг 
## Что такое риг?<a name="whatisrig"></a>
Риг (rig) - это процесс создания виртуального скелета из специальных "костей". После того, как модель готова, в нее вставляют эти кости. Затем кости привязываются к сетке объекта. Между костями и регионами сетки объекта выстравивается связь на основе весов. Таким образом определяется, насколько движения данной кости будут влиять на деформацию сетки. Кости могут быть связаны или не связаны между собой. 
## Полезные ресурсы по ригу <a name="rigresources"></a>
[Полтора риггера](https://www.youtube.com/watch?v=3LUEHGNftzU&list=PL-bOYlU2MrHKY2B4lovH82ABv33KHTfvy&index=11)<br>
[Ригифай](https://www.youtube.com/watch?v=-JSFcSxsaTs&list=PLdcL5aF8ZcJv68SSdwxip33M7snakl6Dx&index=1)<br>
[Развесовка Character weight paint workflow](https://www.youtube.com/watch?v=LPYs3pZEzPY&list=PLdcL5aF8ZcJsFEdlMJ7To0Iu9s-XCFV3W&index=1)<br>


# Скульпт
## Что такое Sculpt? <a name="whatiscsuplt"></a>

**Sculpt** - это набор методов моделирования 3d объекта, имитирующих работу с пластилином или глиной. **Sculpt** гораздо больше похож на работу с традиционными материалами, чем что-либо другое в 3d. 
Работа в этом режиме осуществляется инструментами-кистями. С их помощью можно перемещать участки модели, сдвигать, вырезать или добавлять объем, делать царапины, надувать или делать отверстия. 

Обычно результатом **Sculpt** является высокополигональная модель с неправильной топологией. Это связано с тем, что компьютер самостоятельно рассчитывает топологию во время работы в этом режиме, а человеку предоставляется высокая свобода творчества. 
Большое количество полигонов при **Sculpt** получается из-за желания и возможности передать как можно больше деталей. 
Blender довольно эффективно работает в Sculpt mode с моделями до 5 миллионов полигонов. Для сравнения: хорошая игровая модель с высоким уровнем детализации вряд ли выходит за рамки 100 тысяч полигонов. 

Готовая модель после **Sculpt** может выглядеть очень хорошо, но при этом она обычно непригодна для дальнейшего использования в работе. Для нее не получится сделать UV-развертку, затекстурировать, заригать и анимировать. Чтобы вернуть правильную топологию, применяют процесс, называемый "ретопологией": построение дополнительной сетки с правильной топологией поверх существующей highpoly-модели. Тем самым достигается две цели: снижение поликаунта в десятки или даже сотни раз и построение правильной топологии для облегчения развертки, текстурирования, рига и анимации. Процесс ретопологии не так уж прост и требует некоторого опыта, но он приходит только с практикой и пониманием того, как устроена топология моделей и для чего в тех или иных местах нужны определенные петли из ребер. 
Для упрощения ретопологии существует множество [аддонов](https://github.com/jafdett/BlenderFAQ/blob/main/Addons.md) как встроенных, так и внешних. 
Также существуют и методы автоматической ретопологии, в том числе и встроенные в Blender: это модификатор Remesh и ремешер, доступный по <kbd>Ctrl</kbd> + <kbd>R</kbd> прямо в Sculpt mode. Есть и внешние программы для этого - например, [Instant Meshes](https://github.com/wjakob/instant-meshes).
Как правило, результат авторетопологии сильно хуже, чем ручной. Человек в этой области пока еще побеждает компьютер, но алгоритмы совершенствуются. 

Но ведь при этом пропадут детали, если мы снизим поликаунт? Да, пропадут. Но тут нам на выручку приходит другой процесс, который называется "запекание нормалей": перенос информации о геометрии в специальный плоский файл изображения - карту нормалей. В дальнейшем, подключив эту карту к материалу модели, вы получите иллюзию высокой детализации на модели с низким количеством полигонов. Именно на этом принципе и построены практически все компьютерные 3д-игры. 

**Sculpt** обычно применяют при моделировании органических объектов. Но есть техники для скульпта и hardsurface (то есть механических) объектов. 
Также с помощью Sculpt можно наносить повреждения на модель: царапины, сколы, вмятины. 
Сильная сторона Blender в том, что Sculpt mode можно комбинировать с другими режимами. Например, если в процессе скульпта понадобится смоделировать некоторую деталь, то это легко можно сделать техниками lowpoly моделирования и добавить эту деталь к основной модели, после чего продолжить скульпт.

## Какие ресурсы помогут обучиться скульпту? <a name="sculptresources"></a>
- [Yan Sculpts](https://www.youtube.com/c/yansculpts)
- [CG Boost](https://www.youtube.com/c/CGBoost)
- [SpeedChar aka Niko](https://www.youtube.com/channel/UCZmZjz7XvWfKz4fMjLwrNmQ)
- Книга "Анатомия для скульпторов"
- Курсы от [Scott Eaton](https://www.scott-eaton.com)

## Посоветуйте курсы по Sculpt для начинающих <a name="sculptcourses"></a>
- [Лепка большой каменной глыбы в деталях](https://www.artstation.com/learning/courses/3Va/intro-to-sculpting-in-blender/chapters/8OjR/intro)
- [Скульпт пчелки &mdash; игрового персонажа (с субтитрами на русском)](https://youtube.com/playlist?list=PLX1M0uFI6g-bv0kMcPLyMYLx4yMVyzClN)
- [Большой открытый урок по лепке анатомически верной модели человека](https://www.youtube.com/watch?v=C7pCNy0xyt8)

## Какие есть еще программы для скульптинга?<a name="elsesculpt"></a>
В первую очередь это, конечно же, **Zbrush** - уникальная программа, предназначенная только для cкульпта. Она платная, есть в нескольких версиях, славится своим инопланетным интерфейсом и логикой, но при этом очень мощная и де-факто является стандартом индустрии. 
Также есть Sculptris (бесплатный, но не развивается), Mudbox и 3D Coat (платные). На мобильных устройствах стоит попробовать Nomad Sculpt. 

# Рендеринг
## Что такое рендеринг? <a name="whatisrendering"></a>
**Рендеринг** это процесс получения финальной картинки или анимационного ролика. Существует множество рендер-движков, то есть программ, которые выполняют рендеринг. Blender из коробки оснащен тремя рендер движками: Cycles, EEVEE и Workbench. 
Рендер-движки делятся на unbiased и biased:
* **unbiased** - это физически корректные движки, то есть полностью расчитывающие распространение света в сцене, все его преломления, отражения, рассеивания и даже подповерхностное рассеивание. Платить за такие возможности приходится временем расчета картинки;
* **biased-движки** применяют ряд трюков для расчета сцены, то есть они не физически корректны, зато очень быстрые. При некоторых условиях картинку в biased движке трудно отличить от unbiased картинки. Исторически они происходят из игровых движков и OpenGL. Типичные примеры - это Unreal Engine, Unity, а внутри Blender - EEVEE и Workbench.


## Какие рендер-движки существуют для Blender?<a name="renderengines"></a>
### Встроенные
1. **Cycles** (с недавнего времени это Cycles-X, более быстрый, чем старый). Это unbiased-движок, то есть физически корректный. 
2. **EEVEE** - biased, но практически realtime движок рендера. Появился в версии 2.80. Является дальнейшим развитием OpenGL движка. Для работы желательна дискретная видеокарта. 
3. **Workbench** - похож на EEVEE, но предназначен для предпросмотра статичных картинок и анимаций на промежуточных этапах работы над сценами. Не предназначен для финальных рендеров. 

### Внешние
1. [LuxCore Render](https://luxcorerender.org) - opensource, бесплатный unbiased движок, больше всего похож на Cycles, но со своими особенностями. Многие его любят за правильную передачу каустики и стекла. 
2. [Renderman](https://rmanwiki.pixar.com/display/RFB24/RenderMan+for+Blender+24.0) - движок от Pixar, можно подключить к Blender
3. [PovRay](http://www.povray.org) - еще один opensource unbiased движок. 
4. [Corona](https://blenderartists.org/t/download-corona-renderer-for-blender-3-0-bcorona-3se-v1-4-is-out/1345600) - коммерческий unbiased движок, существует [addon](https://blenderartists.org/t/download-corona-renderer-for-blender-3-0-bcorona-3se-v1-4-is-out/1345600) для работы с ним.
5. [Octane](https://render.otoy.com/forum/viewtopic.php?f=7&t=72241) - коммерческий, unbiased. Для Blender - [бесплатный](https://render.otoy.com/forum/viewtopic.php?f=7&t=72241).
6. [appleseed](https://appleseedhq.net/) - бесплатный opensource unbiased движок, существует [addon](https://github.com/appleseedhq/blenderseed) для работы с ним.

## Какой render-движок предпочесть?<a name="chooserender"></a>
Начните с **Cycles**, он вполне конкурентен по сравнению даже с коммерческими платными движками. Кроме того, он работает со встроенной нодовой системой материалов, и по нему есть очень много уроков. 
Следующий на очереди - **EEVEE**. Он точно так же работает с системой материалов, но при этом дает еще и очень быстрый результат. Можно даже моделировать с включенным финальным рендером **EEVEE**! 
А потом можно попробовать **LuxCore** и т.д.


## Blender умеет рендерить одновременно на процессоре и видеокарте? <a name="gpuandcpu"></a>
Да, такая возможность появилась в 2.8x версиях.

# Диагностика проблем
## Как снять логи? <a name="logs"></a>
Если вы столкнулись с ситуацией вылета программы и не знаете, по какой причине это может происходить, первым делом попытайтесь достать все доступные логи. Для этого нужно сделать следующее:
1. зайти в терминал:

    **Windows:** доступно несколько вариантов:
    * Пуск -> в поиске вбить cmd (Командная строка) или PowerShell
    * <kbd>Win</kbd> + <kbd>X</kbd> -> Windows PowerShell

    **Linux:** в большинстве оболочек терминал открывается комбинацией <kbd>Ctrl</kbd> + <kbd>Alt</kbd> + <kbd>T</kbd>

    **macOS:** <kbd>Cmd</kbd> + <kbd>Пробел</kbd> (откроется Spotlight) -> Terminal

2. выполнить команду:

    **Windows:**

    ```
    <папка блендера>/blender.exe

    # например C:\blender-2.93\blender.exe
    # или, если путь с пробелом, то: "C:\Program Files\blender-2.93\blender.exe"
    ```
    > В процессе ввода команды можно нажимать клавишу TAB  для того, чтобы весь путь к файлам не приходилось набирать вручную. С ее помощью можно вводить только первую букву слова и, нажав на нее, вы получите полное соответствующее значение. 

    **Linux:**

    ```
    <папка блендера>/blender

    # например /home/user/blender-2.93/blender
    # или, если путь с пробелом, то: /home/user/My\ Blender\ Path/blender
    ```

    **macOS:**
    ```
    <путь к Blender.app>/Blender.app/Contents/MacOS/Blender

    # например: /Applications/Blender.app/Contents/MacOS/Blender
    # или, если путь с пробелом, то: /Users/lupa/My\ Blender\ Path/Blender.app/Contents/MacOS/Blender
    ```
    > **ВАЖНО:** обратите внимание, что путь, в котором содержится символ пробела, должен быть экранирован: в Windows путь целиком оборачивается в одинарные кавычки (**'**), в Linux и macOS символ экранируется обратной косой чертой (**\\**).

3. Blender откроется в контексте терминала. После запуска **не закрывайте его**. В момент вылета все логи останутся именно там;
4. скопируйте полученные данные.

Также, помимо ручного поиска нужной информации, сборка Blender для Windows содержит несколько скриптов, которые снимают данные о видеокарте. Они находятся рядом с исполняемым файлом и называются **blender_debug_gpu** и **blender_debug_log**.

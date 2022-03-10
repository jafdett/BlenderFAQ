# BlenderFAQ

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
## Общие вопросы про 3d графику
- [Что такое pipeline?](#whatispipeline)<br>
- [Какие методы создания 3d моделей существуют?](#3dmethods)<br>
- [Что такое hardsurface?](#whatishardsurface)<br>
## Железо
- [Какие видеокарты поддерживаются?](#gpusupported)<br>
- [Какой мне нужен компьютер для Blender?](#whatcomputer)<br>
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
- [Ссылки на IES-библиотеки?](#iesget)<br>
## Аддоны
- [Где мне взять аддоны?](#addons)<br>
- [Как перенести настройки и аддоны в новую версию Blender?](#settingsmove)<br>
## Моделирование
- [Я хочу научится моделировать машины, какие курсы посоветуете?](#carcreation)<br>
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
1. Подавляющее большинство обучающих курсов, уроков и статей написаны именно под английский интерфейс, как следствие вам будет намного проще повторять действия за автором, не теряя время на перевод и поиск этой функций в русскоязычном интерфейсе;
2. В процессе изучения программы вы сможете подтянуть свой английский!
3. Так вы повышаете шанс на быстрое решение своей задачи при обращении за помощью: даже в русскоязычных сообществах английский интерфейс программы является негласным стандартом.
> Можно пойти на компромис: оставить весь интерфейс на английском, но включить русские подсказки. Это можно сделать через Preferences - Interface - Language (Русский), но оставить только чекбокс Affect - Tooltips.

## Может ли Blender в 2d? <a name="2d"></a>
Сначала нужно понять, что такое 2d. Можно делать плоские модели, или располагать их так, что они будут выглядеть плоскими, делать в них риг, анимацию и это будет 2d.
Но есть и классический инструмент для 2d: это новый Grease Pencil, это очень мощный инструмент для 2d рисования и анимации. С его помощью был сделан ролик [Hero](https://www.youtube.com/watch?v=pKmSdY56VtY). А еще с его помощью можно делать вот такие [акварели](https://www.youtube.com/watch?v=h0r7GdC5Bu0).

## А что с автоматизацией? <a name="automation"></a>
У Blender есть богатое Python API - с помощью Python можно писать программы, которые работают прямо внутри Blender и имеют доступ практически ко всем его функциям. Документация по API доступна здесь: https://docs.blender.org/api/current/. Именно с помощью Python API написано большинство addon-ов для Blender. 

## О скриншотах <a name="screenshots"></a>
При общении в чатах и на формумах для того, чтобы проиллюстрировать свой вопрос, часто требуется сделать скриншот или даже записать скринкаст. 
Многие не знают, что в операционных системах уже есть встроенные средства для этого и фотографируют экран на телефон. Так делать не нужно: качество картинки сильно страдает, появляется муар и понять что на ней довольно сложно. 
Вместо этого нужно использовать средства ОС.<br> 
На Windows: нажмите <kbd>Win</kbd> + <kbd>G</kbd> и выберите нужный пункт.<br> 
На macOS: нажмите <kbd>Command</kbd> + <kbd>Control</kbd> + <kbd>Shift</kbd> + <kbd>4</kbd> (область экрана сразу попадет в буфер обмена ) или <kbd>Command</kbd> + <kbd>Shift</kbd> + <kbd>3</kbd> или <kbd>4</kbd> (будет сохранен в файл).

Кроме того, существуют специальные програмы для этого:
- Клиент Яндекс.Диск содержит встроенное средства захвата экрана
- ShareX (только Windows), есть версия в Steam
- LightShot - кроссплатформенная

## Каким образом можно передать модели в другие программы или получить их из них? <a name="importexport"></a>
Рано или поздно возникает вопрос про передачу моделей из Blender в другие программы либо про импорт из других программ в Blender. 
Рекомендуется для этого использовать формат FBX: де-факто это стандарт индустрии, все современные 3d программы его поддерживают. К сожалению это закрытый формат, разработанный Autodesk, поэтому совместимость между программами может быть не полной. Для того чтобы иметь возможность делать импорт-экспорт нужно включить аддон в настройках. Вместе с Blender идут в комплекте встроенные аддоны для импорта/экспорта форматов: FBX, OBJ, PLY, STL, SVG.

## У меня нет numpad-а, как быть? <a name="nonumpad"></a>
Включите опцию эмуляции numpad в настройках (Preferences - Input - Emulate Numpad)

## Какие настройки стоит сделать сразу на свежеустановленном Blender? <a name="initsetup"></a>
1. Если у вас нет numpad, то сделайте как написано пунктом выше.
2. Включите сразу Orbit Around Selection (Preferences - Navigation - Orbit Around Selection), тогда вид при вращении будет всегда центрироваться относительно выбранного.

# Общие вопросы про 3d графику

## Что такое pipeline? <a name="whatispipeline"></a>
**Pipeline** (или конвейр) - это название всего набора действий для получения готового результата. Этот набор охватывает все, от самого начала производства продукта и до самого конца. Pipeline также накладывает определенные требования на программы, используемые в производстве продукта и даже на методы работы внутри этих программ. 
Пример типичного pipline для создания игрового персонажа:
![3d pipeline](http://www.plantuml.com/plantuml/svg/FP1DIiOm68JtFKNSwSTtYEyIkd8JQC0kKgJc0Ft1RXJKbU1AFK6q5aD_sYlCUoE745m4oZCFymuztJbTELkKkTMtsPcxCTOegvsf2fqT55xXyICT5apmsO7a3HjMwJ5Yb_QwF9SQGHegAvLmLFo-PxZ8mr6HUNpHsAG1qmkbsC6I5yoi8Q4n497X0nDRPda4YoCZVCSeBTMTR-ORUEo9OKmlhnIxFNxnJQsc64Uc59-SCN5EArqSoHaKFKy6Z778_v6GLYJm79q5NlfuxsJAFFsZFm00)

## Какие методы создания 3d моделей существуют? <a name="3dmethods"></a>
- Полигональное моделирование или low poly: просто вытягиваете полигоны, манипулируете вершинами, ребрами и поверхностями. 
- Subdiv: применяется модификатор Subdivision surface - сразу виден highpoly, но при этом работа с моделью идет через low poly. Применяются поддерживающие петли (edge loops) для придания остроты нужным граням. 
- Boolean: придание формы за счет вырезания, добавления и пересечения геометрий. 
- Скульпт (чаще применяют для органики): работа с high poly моделью без учета топологии при помощи инструментов, напоминающих инструменты работы с пластилином или глиной. 
- процедурное моделирование: построение моделей программными методами, например с помощью geometry nodes в Blender или в Houdini.
- Построение моделей в CAD программах, с последующим импортом и ретопологией в полигональных программах, таких как Blender
- NURBS
- Metaballs: создание геометрии с помощью меташаров, объектов имеющих свойство объединяться друг с другом при приближении на определенное расстояние. Позволяет быстро прототипировать модели. В современном моделировании метод используется редко, чаще всего для получения базовых форм перед скульптом. 

## Что такое hardsurface?<a name="whatishardsurface"></a>
Hardsurface это обобщенное название моделей с "твердыми" поверхностями, например оружие, предметы окружения, автомобили.
В принципе, все что нас окружает делится на hardsurface и органику.
Для моделирования hardsurface применется множество методов, описанных выше, а для моделирования органики - чаще всего используется Sculpt.

# Железо 
## Какие видеокарты поддерживаются?<a name="gpusupported"></a>
Blender имеет ряд условий относительно поддержки видеокарт. В основном, работают почти все современные варианты, доступные на рынке.

### NVIDIA
- **CUDA**: видеокарты новее _GeForce 400_ с поддержкой CUDA **3.0 и выше**;
- **OptiX**: видеокарты с поддержкой CUDA **5.0 и выше**, а также с драйвером **470+**. Основная масса поддержки - модели RTX.

> **ВАЖНО:** на компьютерах с установленной macOS последняя версия системы, на которой можно использовать видеокарту NVIDIA с поддержкой CUDA - **10.13.6**.

### AMD
- **OpenCL**: видеокарты на архитектуре **CGN 2 и новее**. Для корректной работы на Linux должен использоваться PRO драйвер.
- **HIP**: видеокарты на архитектуре **RDNA** и новее, а также с драйвером **AMD Radeon Software 21.12.1** или **AMD Radeon PRO Software 21.Q4**. Появилось в Blender 3.0. На данный момент поддерживается только на Windows.

> **ВАЖНО:** поддержка OpenCL для Windows и Linux **закончилась** в версии 2.93. На компьютерах с установленной macOS последняя версия системы, на которой можно использовать видеокарту AMD - **10.13.6**.

### Apple
- **Metal**: компьютеры Apple на базе Apple Silicon с установленной macOS 12.0 и новее. Появилось в Blender 3.0.

### Intel
- Рендеринг на видеоядре недоступен.

### Таблица совместимости

|               | Версия Blender    | Windows   | Linux | macOS (Intel)     | macOS (ARM)   |
|---------------|:-----------------:|:---------:|:-----:|:-----------------:|:-------------:|
| **CUDA**      | все               | +         | +     | + (до 10.13.6)    |               |
| **OptiX**     | 2.81+             | +         | +     |                   |               |
| **OpenCL**    | все до 2.93       | +         | +     | + (до 10.13.6)    |               |
| **HIP**       | 3.0+              | +         |       |                   |               |
| **Metal**     | 3.0+              |           |       |                   | + (с 12.0)    |

## Какой мне нужен компьютер для Blender?<a name="whatcomputer"></a>
Это комплексный вопрос. Многое зависит от того, что вы собираетесь делать в Blender. <br>
Системные требования довольно щадящие. Они указаны на [официальном сайте](https://www.blender.org/download/requirements/).

В первую очередь стоит обратить внимание на CPU, память и видеокарту. 
Некоторые процессы в Blender многотредовые (например Cycles) и поэтому могут использовать все доступные ядра процессора. Стало быть, чем больше ядер у CPU - тем лучше. 

Видеокарта - лучше всего работает GPU от Nvidia. Понятно, что самые последние серии и более высокого уровня работают лучше всего. Но даже 950Ti все еще может помочь в рендерах. 

Память. Ее не бывает много. Blender будет работать и на 8Gb, но лучше 16, а еще лучше 32. 
Также желателен SSD. 

Для скульта мощность видеокарты не так важна, можно жить даже на встроенной графике, но тут играют решающую роль память и CPU. 

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

## Где искать ответы на возникающие вопросы?<a name="questions"></a>
1. Ответы на большинство вопросов можно найти в официальной документации к программе: https://docs.blender.org/manual/en/latest/
2. Используйте Google и Яндекс! Сформулируйте вопрос (лучше на английском) и вперед - найдется все!
3. То же самое и в YouTube, просто ищите там по ключевым словам вашего вопроса и добавьте "Blender". Например, вам нужно узнать про ретопологию - запрос будет такой: "Retopology Blender".
4. Приходите в Телеграм-чат [Blender_cg_ru](https://t.me/blender_cg_ru), там помогут. 

## Но ведь я не знаю английский! Как мне смотреть видео?<a name="knowenglish"></a>
Яндекс [анонсировал](https://yandex.ru/blog/company/smotrite-po-russki-yandeks-zapustil-zakadrovyy-perevod-video) технологию машинного перевода видео на YouTube.

## Стоит ли смотреть уроки, курсы и туторы для более старых версий?<a name="oldtutors"></a>
Между версиями 2.7x и 2.8+ действительно существует огромная разница, ведь в версиях начиная с 2.80 был полностью переработан интерфейс, и обучаться работе в версиях старше 2.8х на основе версии 2.7х будет не эффективно. К тому же версии младше 2.80 попросту морально устарели (не обновляются разработчиком). 

Что же касается версий 2.8х, 2.9х, 3.х, то в вопросе интерфейса они практически идентичны, и вы с лёгкостью сможете ориентироваться во всех трёх линейках.

На данный момент [актуальной стабильной версией](https://www.blender.org/download/) является версия 3.0, но вы можете смело пользоваться учебным материалом на базе 2.8х + версий. Только учтите при этом, что некоторые функции всё же меняли своё местоположение в ходе эволюции и если ваша версия старше той, которая у автора видео, то возможно вам придётся поискать её.


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
[blazraidr](https://www.youtube.com/c/blazraidr)<br>
[Blender Animation Studio](https://www.youtube.com/c/blazraidr)<br>
[Blender Sensei](https://www.youtube.com/c/blazraidr)<br>
[BlenderDiplom](https://www.youtube.com/c/blazraidr)<br>
[CG Geek](https://www.youtube.com/c/blazraidr)<br>
[CG Masters](https://www.youtube.com/c/blazraidr)<br>
[Grant Abbitt](https://www.youtube.com/c/blazraidr)<br>
[masterxeon1001](https://www.youtube.com/c/blazraidr)<br>
[YanSculpts](https://www.youtube.com/c/blazraidr)<br>
[CG Boost](https://www.youtube.com/c/blazraidr)<br>
[CGRogue](https://www.youtube.com/c/blazraidr)<br>
[Blender Guru:](https://www.youtube.com/c/blazraidr)<br>
[Remington graphics:](https://www.youtube.com/c/blazraidr)<br>
[CG Cookie](https://www.youtube.com/c/blazraidr)<br>
[Sardi Pax](https://www.youtube.com/c/blazraidr)<br>
[Wayward Art Company](https://www.youtube.com/c/blazraidr)<br>
[MaxEdge](https://www.youtube.com/c/blazraidr)<br>
[sketching in blender](https://www.youtube.com/c/blazraidr)<br>
[Polyfjord](https://www.youtube.com/c/blazraidr)<br>
[Joey Carlino](https://www.youtube.com/c/blazraidr)<br>
[CrossMind Studio](https://www.youtube.com/c/blazraidr)<br>

### Русскоязычные авторы:

[Blender 3D - уроки](https://www.youtube.com/c/blazraidr)<br>
[Denis Kozhar](https://www.youtube.com/c/blazraidr)<br>
[fastaboutblender](https://www.youtube.com/c/blazraidr)<br>

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
- https://freepbr.com/
- http://hdrlabs.com/sibl/archive.html


## Ссылки на IES-библиотеки?<a name="iesget"></a>
- https://ieslibrary.com/en/home
 
 [Видеоурок](https://www.youtube.com/watch?v=l-uz3BHOqNo) о том, как использовать IES-файлы

# Аддоны
## Где мне взять аддоны?<a name="addons"></a>
Многие полезные аддоны поставляются вместе с программой, но по умолчанию не активированы. Их можно активировать в настройках программы (Edit/Preferences/add-ons)
А так же существуют ресурсы, на которых авторы выкладывают свои аддоны.
Многие из них являются платными, но в большинстве случаев плата за них вполне оправдана.
- [Blender market](https://blendermarket.com/categories/scripts-and-addons)
- [Gumroad](https://gumroad.com/)
- [Github](https://github.com)

Более подробно про аддоны смотрите [дополнительный документ](https://github.com/jafdett/BlenderFAQ/blob/main/Addons.md)

## Как перенести настройки и аддоны в новую версию Blender? <a name="settingsmove"></a>
Blender обновляется и развивается очень динамично, вследствие чего регулярно появляются новые версии программы. Однако, скачав с сайта Blender очередной релиз, всегда необходимо настроить его удобным для себя образом.

Для того, чтобы вручную не восстанавливать все пользовательские настройки и не переустанавливать аддоны, в новую версию Blender можно быстро перенести настройки и аддоны из предыдущей версии. Для этого:
- При первом запуске Blender в окне с заставкой можно нажать на кнопку *“Load 2.ХХ Settings”*. После чего в текущую версию Blender будут перенесены настройки и аддоны из версии, указанной на кнопке.
- Или же, если вы хотите контролировать процесс переноса настроек самостоятельно, можно вручную перенести файлы с настройками и аддонами.
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
## Я хочу научится моделировать машины, какие курсы посоветуете? <a name="carcreation"></a>
[Master Car Creation in Blender](https://www.blendermarket.com/products/master-car-creation-in-blender)

# Скульпт
## Что такое Sculpt? <a name="whatiscsuplt"></a>

**Sculpt** это набор методов моделирования 3d объекта, имитирующих работу с пластилином или глиной. **Sculpt** гораздо больше похож на работу с традиционными материалами, чем что-либо другое в 3d. 
Работа в этом режиме осуществляется инструментами-кистями. С их помощью можно перемещать участки модели, сдвигать, вырезать или добавлять объемы, делать царапины, надувать или делать отверстия. 

Обычно результатом **Sculpt** является высокополигональная модель с неправильной топологией. Это связано с тем, что компьютер самостоятельно определяет топологию во время работы в этом режиме, а человеку предоставляетя большая свобода творчества. 
Большое количество полигонов при **Sculpt** получается из-за желания и возможности передать как можно больше деталей. 
Blender довольно эффективно работает в Sculpt mode с моделями до 5 миллионов полигонов. Для сравнения - хорошая игровая модель с высоким уровнем детализации вряд ли выходит за рамки 100 тысяч полигонов. 

Готовая модель после **Sculpt** может выглядеть очень хорошо, но при этом она обычно непригодна для дальнейшего использования в работе. Для нее не получится сделать UV-развертку, затекстурировать, заригать и анимировать. Для того, чтобы вернуть правильную топологию применяют процесс, называемый "ретопологией", то есть построение дополнительной сетки с правильной топологией поверх существующей highpoly-модели. Тем самым достигается две цели: снижение поликаунта в десятки или даже сотни раз и построение правильной топологии для облегчения рвезвертки, текстурирования, рига и анимации. Процесс ретопологии не так уж прост и требует некоторого опыта, но он приходит только с практикой и пониманием того, как устроена топология моделей и для чего в тех или иных местах нужны определенные петли из ребер. 
Для упрощения ретопологии существует множество [аддонов](https://github.com/jafdett/BlenderFAQ/blob/main/Addons.md), как встроенных, так и внешних. 
Также существуеют и методы автоматической ретопологии, в том числе и встроенные в Blender: это модификатор Remesh и ремешер, доступный по CTRL-R прямо в Sculpt mode. Есть и внешние программы для этого, например [Instant Meshes](https://github.com/wjakob/instant-meshes).
Обычно результат авторетопологии сильно хуже, чем ручной, человек в этой области пока еще побеждает компьютер, но алгоритмы совершенствуются. 

Но ведь при этом пропадут детали? Если мы снизим поликаунт? Да, пропадут. Но тут нам на выручку приходит другой процесс, который называется "запекание нормалей", то есть перенос информации о геометрии в специальный плоский файл изображения - карту нормалей. В дальнейшем, подключив эту карту к материалу модели вы получите иллюзию высокой детализации на модели с низким количеством полигонов. Именно на этом принципе и построены практически все компьютерные 3д-игры. 

**Sculpt** обычно применяют при моделировании органических объектов. Но есть техники для скульпта и hardsurface (то есть механических) объектов. 
Также с помощью Sculpt можно наносить повреждения на модель: царапины, сколы, вмятины. 
Сильная сторона Blender в том, что Sculpt mode можно комбинировать с другими режимами. Например, если в процессе скульпта понадобиться смоделировать некоторую деталь, то это легко сделать техниками lowpoly моделирования и добавить эту деталь к основной модели и продолжить скульпт.

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
В первую очередь это конечно же Zbrush - уникальная программа, предназначенная только для cкульпта. Она платная, есть в нескольких версиях, славится своим инопланетным интерфейсом и логикой, но при этом очень мощная и де-факто является стандартом индустрии. 
Также есть Sculptris (бесплатный, но не развивается), Mudbox и 3D Coat (платные). На мобильных устройствах стоит попробовать Nomad Sculpt. 

# Рендеринг
## Что такое рендеринг? <a name="whatisrendering"></a>
**Рендеринг** это процесс получения финальной картинки или анимационного ролика. Существует множество рендер-движков, то есть программ, которые выполняют рендеринг. Blender из коробки оснащен тремя рендер движками: Cycles, EEVEE и Workbench. 
Рендер-движки делятся на unbiased и biased.
Unbiased это физически-корректные движки, то есть полностью расчитывающие распространение света в сцене, все его преломления, отражения, рассеивания и даже подповерхностное рассеивание. Платить за такие возможности приходится временем расчета картинки.
Biased-движки применяют ряд трюков для расчета сцены, то есть они не физически корректны, зато очень быстрые. При некоторых условиях картинку в biased движке трудно отличить от unbiased картинки. Исторически они происходят из игровых движков и OpenGL. Типичные примеры это Unreal Engine, Unity, а внутри Blender это EEVEE и Workbench.


## Какие рендер-движки существуют для Blender?<a name="renderengines"></a>
### Встроенные
1. **Cycles** ( с недавнего времени это Cycles-X, более быстрый, чем старый). Это unbiased-движок, то есть физически-корректный. 
2. **EEVEE** - biased, но практически realtime движок рендера. Появился в версиях 2.8x. Является дальнейшим развитием OpenGL движка. Для работы желательна дискретная видеокарта. 
3. **Workbech** - похож на EEVEE, но предназначен для предпросмотра статичных картинок и анимаций на промежуточных этапах работы над сценами. Не предназначен для финальных рендеров. 

### Внешние
1. [LuxCore Render](https://luxcorerender.org) - opensource, бесплатный unbiased движок, больше всего похож на Cycles, но со своими особенностями. Многие его любят за правильную передачу каустики и стекла. 
2. [Renderman](https://rmanwiki.pixar.com/display/RFB24/RenderMan+for+Blender+24.0) - движок от Pixar, можно подключить к Blender
3. [PovRay](http://www.povray.org) - еще один opensource unbiased движок. 
4. [Corona](https://blenderartists.org/t/download-corona-renderer-for-blender-3-0-bcorona-3se-v1-4-is-out/1345600) - коммерческий unbiased движок, существует [addon](https://blenderartists.org/t/download-corona-renderer-for-blender-3-0-bcorona-3se-v1-4-is-out/1345600) для работы с ним.
5. [Octane](https://render.otoy.com/forum/viewtopic.php?f=7&t=72241) - коммерческий, unbiased. Для Blender - [бесплатный](https://render.otoy.com/forum/viewtopic.php?f=7&t=72241).
6. [appleseed](https://appleseedhq.net/) - бесплатный opensource unbiased движок, существует [addon](https://github.com/appleseedhq/blenderseed) для работы с ним.

## Какой render-движок предпочесть?<a name="chooserender"></a>
Начните с **Cycles**, он вполне конкурентен по сравнению даже с коммерческими платными движками. Кроме того, он работает со встроенной нодовой системой материалов и по нему есть очень много уроков. 
Следующий на очереди  &ndash;  **EEVEE**, он точно так же работает с системой материалов, но при этом дает еще и очень быстрый результат. Можно даже моделировать с включенным финальным рендером **EEVEE**! 
А потом можно попробовать **LuxCore** и далее везде. 


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
    # или, если путь с пробелом, то: 'C:\Program Files\blender-2.93\blender.exe'
    ```

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

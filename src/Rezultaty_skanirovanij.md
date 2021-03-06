
Результаты сканирований
`<link rel="stylesheet" type="text/css" href="assets/css/default.css" />
``
</head>
```
``
<body>
```
``
<h2>
```
Результаты сканирований
``
</h2>
```
``
<h3 data-list-level="2">
```
Список результатов
При выборе пункта меню **Результаты
сканирования** отображается список всех проведенных
сканирований. На этой странице можно посмотреть все прошедшие
сканирования. Каждое сканирование представлено одной строкой. Данные о
результатах сканирований автоматически обновляются каждые 10 секунд, что
освобождает пользователя от необходимости обновлять страницу вручную.
<img height="1152" src="/img/image61.png" width="100%" />
В списке отображаются сканирования, отсортированные по
**Id** сканирования. В таблице
присутствует следующая информация:

**Id** --- внутренний идентификатор
сканирования.
**Имя проекта** --- имя проекта, в рамках
которого проводилось сканирование.
**Имя профиля** --- профиль сканирования,
с которым было проанализировано приложение.
**Режим** --- режим сканирования, ручной
или автоматический.
**Имя пакета** --- имя анализируемого
приложения в системе Android.
**Статус** --- статус сканирования, может
принимать несколько значений:
``
<ul>
```
``
<li class="a0">
```
**Успешно** --- сканирование завершилось
без ошибок. Если сканирование в целом прошло успешно, но наблюдались
сбои в работе отдельных модулей, рядом со статусом отображается значок
`<img alt="Изображение выглядит как текст, снимок экрана, внутренний
Автоматически созданное описание" height="13.1" src="/smimg/image47.png" width="18.9" />.
При наведении на него курсора появляется более подробная информация о
сбоях.
**Создан** --- сканирование создано.
**Запускается** --- сканирование
запущено, идет процесс установки и запуска целевого приложения.
**Запущен** --- происходит процесс
сканирования.
**Анализируется** --- сканирование
остановлено, осуществляется процесс анализа собранной информации.
**Отменяется** --- сканирование было
запущено, но инициирована его отмена с использованием расположенного
справа раскрывающегося
меню.`<img alt="Изображение выглядит как текст, внутренний, снимок экрана, компьютер
Автоматически созданное описание" src="/smimg/image48.png" style="cursor: nwse-resize;" />
``
<p class="a0">
```
**Отменено** --- сканирование отменено с
использованием расположенного справа раскрывающегося меню.
``
</p>
```
``
<p class="a0">
```
**Ошибка** --- сканирование завершено с
ошибкой. Рядом со статусом отображается значок
`<img alt="Изображение выглядит как текст, снимок экрана, внутренний, компьютер
Автоматически созданное описание" height="15.1" src="/smimg/image49.png" width="16.0" />.
При наведении на него курсора появляется более подробная информация об
ошибке.
``
</p>
```
``
</li>
```
``
</ul>
```
    </li>
    <li class="a0"><strong>Изменено</strong> — время запуска сканирования.</li>

``
</ul>
```
``
<p class="a1">
```
Для отображения только необходимых результатов предусмотрен фильтр. При
выборе нескольких фильтров они работают вместе, то есть при выборе
режима **Ручной** и статуса
**Успешно** будут найдены и отображены
все успешные сканирования с ручным режимом запуска.
<img src="/img/image62.png" />
При нажатии на нужную строку в таблице **Результаты
сканирований** происходит переход к результатам
выбранного сканирования.
Кроме этого, находясь на данной странице, можно скачать PDF-отчет о
сканировании, инициировать повторный анализ или удалить результаты
сканирования. Для выполнения перечисленных действий используйте
расположенное справа раскрывающееся меню.
`<img alt="Изображение выглядит как текст, снимок экрана, внутренний, компьютер
Автоматически созданное описание" src="/smimg/image51.png" />
``
</p>
```
``
<h3 data-list-level="3">
```
Результаты сканирования
Чтобы перейти на страницу **Результат
сканирования**, нажмите на строку нужного сканирования в
таблице **Результаты сканирования**. На
открывшейся странице содержится вся информация по анализу приложения:
выявленные уязвимости, собранные за время работы приложения данные,
соответствие стандартам и требованиям. Для выбора доступно четыре или
пять вкладок в зависимости от типа сканирования: **Общая
информация**,
**Дефекты**, **Собранные
данные**, **Требования**,
**Запись сканирования**.

Общая информация

Вкладка **Общая информация** содержит
сведения о проведенном сканировании и краткую информацию о проверенном
приложении.
`<img alt="Рисунок 114" src="/smimg/image52.png" />
На этой вкладке представлена общая информация по сканированию:

**Название пакета** --- имя приложения в
системе.
**Название версии / код версии** ---
версия, указанная в манифесте приложения для более точной идентификации
анализируемого приложения.
**Target SDK/Min SDK** --- версии SDK,
для которых собрано данное приложение
**Файл** --- информация о загруженном
файле.
``
<ul>
```
``
<li class="a0">
```
**Размер** --- размер файла.
**md5** --- хэш сумма файла.
**Тип архитектуры / Архитектура** ---
архитектура сканируемого приложения (Android / iOS).
``
</li>
```
``
</ul>
```
    </li>
    <li class="a0"><strong>Проект</strong>, в рамках которого проводилось сканирование. Данное значение представлено в виде ссылки, нажав которую можно перейти в соответствующий проект.</li>
    <li class="a0"><strong>Профиль</strong>, в рамках которого проводилось сканирование. Данное значение представлено в виде ссылки, нажав которую можно перейти в соответствующий профиль сканирования.</li>
    <li class="a0"><strong>Изменено</strong> — дата сканирования.</li>
    <li class="a0"><strong>Статус</strong> — статус сканирования.</li>
    <li class="a0"><strong>Тест кейс</strong> — название используемого тест кейса.</li>

``
</ul>
```
``
<p class="a1">
```
Кнопки, расположенные в правом верхнем углу, позволяют выполнить
следующие действия:
``
</p>
```
``
<ul class="Disc">
```
``
<li class="Numbering48 a0">
```
**Повторный анализ** --- провести
повторный анализ результатов сканирования с применением актуальных
правил анализа уязвимостей для данного приложения.
``
</li>
```
``
<li class="Numbering48 a0">
```
**Скачать логи** --- скачать лог-файл
сканирования.
**Скачать отчет** --- получить подробный
отчет о результатах сканирования в формате pdf.
**Скачать приложение** --- скачать файл
сканируемого приложения.
``
</li>
```
``
</ul>
```
``
<h4 data-list-level="4">
```
Дефекты

На каждую выявленную уязвимость системой заводится дефект. Список всех
найденных во время сканирования дефектов показан в левой половине
вкладки **Дефекты**. В правой части
данный вкладки представлена информация о выявленной уязвимости с ее
детальным описанием, а также даны рекомендации по ее устранению.
<img src="/img/image74.png" />
Для удобства работы с дефектами существует возможность выбрать и
применить для отображаемых дефектов фильтр. Для этого нажмите кнопку
**Фильтр** в левом верхнем углу и
выберите из выпадающих списков одно или несколько значений для
фильтрации по параметрам **Критичность**,
**Статус **и
**Состояние**. Если выбран уровень
критичности **Высокий **и статус
**Подтвержден**, то будут отображаться
все подтвержденные дефекты с высоким уровнем критичности. Фильтр может
быть очищен по нажатию кнопки **Очистить
фильтр** справа вверху. При повторном нажатии на кнопку
**Фильтр** в левом верхнем углу, поле
фильтрации будет свернуто.
На вкладке **Дефекты** представлены
следующие сведения о дефекте:

ID дефекта в системе.
Уязвимость --- требование, соответствие которому нарушает данный дефект.
Критичность дефекта:
``
<ul>
```
``
<li class="a0">
```
«`<img alt="Picture 151" height="17.6" src="/smimg/image54.png" width="16.2" />»
--- критичный;
«`<img alt="Picture 152" height="17.5" src="/smimg/image55.png" width="15.5" />»
--- высокий;
«`<img alt="Picture 153" height="18.3" src="/smimg/image56.png" width="15.5" />»
--- средний;
«`<img alt="Picture 154" height="17.6" src="/smimg/image57.png" width="15.5" />»
--- низкий;
«`<img alt="Picture 155" height="17.5" src="/smimg/image58.png" width="15.5" />»
--- инфо.
``
</li>
```
``
</ul>
```
    </li>
    <li class="a0">Статус дефекта:
      <ul>
        <li class="a0">«<img alt="Picture 159" height="16.2" src="/smimg/image59.png" width="16.2" />» — подтвержден;</li>
        <li class="a0">«<img alt="Picture 160" height="16.1" src="/smimg/image60.png" width="16.8" />» — ложное срабатывание;</li>
        <li class="a0">«<img alt="Picture 161" height="16.9" src="/smimg/image61.png" width="16.9" />» — не обработан.</li>
      </ul>
    </li>

``
</ul>
```
``
<p class="a1">
```
Начальное заполнение значений полей дефектов производится системой
автоматически во время анализа результатов.
При нажатии на дефект в левой половине вкладки
**Дефекты** справа отображается детальная
информация о нем.
<img src="/img/image75.png" />
Приводится следующая информация:
``
</p>
```
``
<ol class="RoundSquare">
```
``
<li class="a0">
```
**ID** дефекта в системе.
****Название выявленной уязвимости. Рядом
с названием располагается иконка
«`<img src="/img/image8.png" />», нажав которую можно
скачать отчет об уязвимости в формате PDF.
Состояние дефекта:
``
<ol>
```
``
<li class="a0">
```
**Новый** --- если этот дефект был
впервые найден во время этого сканирования, либо он уже встречался
ранее, а затем проблема была решена и дефект был закрыт, но при этом
сканировании вновь проявился.
**Старый** --- если этот дефект был уже
ранее найден во время предыдущих сканирований.
**Исправленный** --- это состояние для
тех дефектов, которые были найдеры в предыдущих сканированиях, но в
текущем сканировании их уже нет.
``
</li>
```
``
</ol>
```
    </li>
    <li class="a0"><strong>Критичность</strong> дефекта. В этом поле отображается текущее значение критичности дефекта и предоставляется возможность поменять критичность, выбрав новое значение из выпадающего списка. Важно отметить, что при смене критичности дефект автоматически получает статус «Подтвержден», то есть, присваивая дефекту уровень критичности, мы признаем, что он существует.</li>
    <li class="a0"><strong>Статус</strong> дефекта. В этом поле отображается текущий статус дефекта и предоставляется возможность поменять статус, выбрав новое значение из выпадающего списка.</li>
    <li class="a0"><strong>Описание</strong> дефекта в краткой форме характеризует найденную уязвимость. Рядом с описанием располагается ссылка на Wiki-страничку с подробным описанием уязвимости, рекомендациями по исправлению, примерами исходного кода и ссылками на материалы по этой уязвимости.</li>

``
</ol>
```
``
<p class="a0-no-list">
```
**Примечание:** Отдельно следует отметить
дефекты, выявленные модулем «Поиск ранее найденной чувствительной
информации». В поле **Описание** таких
дефектов, кроме упомянутой выше информации, можно найти ссылку на
уязвимости (**Смотреть детали**), которые
послужили основанием для создания такого дефекта
(**`<a class="expandspot" data-rhwidget="ExpandSpot" data-target="expanding" href="#" style="color: #000080">подробнее`</a>[:
В основе работы данного модуля лежит анализ информации, собранной
другими модулями, вычисление популярных хеш-функций и кодирование
обнаруженных параметров с последующим повторным поиском по всем
данным]{.expandtext data-targetname="expanding"
style="color: #0000FF"}[[]{style="text-align:left;"}]{style="color:#0000ff;"}**[)]{style="text-align:left;"}.
``
</p>
```
``
<p class="a0-no-list" style="text-align: center">
```
`<img src="/img/image77.png" />

Место возникновения дефекта. Если обнаружено несколько уязвимостей
одного типа, они группируются в один дефект, а справа от данного поля
появляются стрелки, с помощью которых можно переходить между
уязвимостями. Ниже приводится важная фактическая информация по найденной
уязвимости, например, обнаруженная чувствительная информация, место ее
обнаружения, и т. п.
В поле Результат отображается фрагмент кода или содержимое файла (до
5000 знаков), в котором обнаружена уязвимость. Если необходимо загрузить
соответствующий файл целиком, нажмите ссылку
**Загрузить**, расположенную справа.

[Если в результате анализа были найдены уязвимости, которые определяются
нами как ложные срабатывания, они могут быть добавлены в исключения как
на уровне проекта, так и на уровне организации (ко всем проектам
организации). Для этого необходимо выбрать один или несколько
обнаруженных дефектов, изменить их статус на «Ложное срабатывание» и
нажать кнопку **Добавить в исключения**,
расположенную в верхнем правом углу вкладки
**Дефекты** окна
**Результат
сканирования**.]{style="color:#000000;"}
``
</p>
```
``
<p class="a0">
```
[[`<img height="1023" src="/img/image80.png" width="100%" />]{style="text-decoration:underline;"}]{style="color:#000000;"}
``
</p>
```
``
<p>
```
[В появившемся окне **Добавление
исключений** выберите, на каком уровне вы хотите
добавить исключения --- на уровне проекта или на уровне организации, а
затем нажмите кнопку
**Добавить**.]{style="color:#000000;"}
``
</p>
```
``
<p style="text-align: center">
```
[`<img height="451" src="/img/image83.png" width="50%" />]{style="color:#000000;"}
``
</p>
```
``
<p>
```
[Также можно добавить исключение для отдельной уязвимости, нажав кнопку
**Добавить исключение** рядом с
заголовком **Найдено правилом** в
описании соответствующей уязвимости.]{style="color:#000000;"}
``
</p>
```
``
<p style="text-align: center">
```
[`<img height="1001" src="/img/image84.png" width="100%" />[]{style="text-decoration:underline;"}]{style="color:#000000;"}
``
</p>
```
``
<p style="margin:0cm 0cm 8pt;text-align:left">
```
[В появившемся окне **Добавление
исключения** выберите, на каком уровне вы хотите
добавить исключение --- на уровне проекта или на уровне организации, а
затем нажмите кнопку
**Добавить**.]{style="color:#000000;"}
``
</p>
```
``
<p style="margin:0cm 0cm 8pt;text-align:center">
```
[`<img height="451" src="/img/image82.png" width="NaN" />]{style="color:#000000;"}
``
</p>
```
``
<p>
```
[В результате добавления исключений при повторном анализе результатов
или при следующем сканировании в рамках этого проекта, если выбран
уровень проекта, или для всех проектов организации, если выбран уровень
организации, такие уязвимости учитывать не
будут.]{style="color:#000000;"}

Собранные данные

На вкладке **Собранные данные**
отображается вся информация о работе приложения, собранная за время
сканирования. Информация разделена по модулям, которые отвечают за сбор
данных. Для модулей предусмотрена возможность скачивания собранных
данных в виде zip-архива с помощью кнопки **Загрузить
данные модуля**, или же, возможно скачать все данные
сканирования сразу в одном архиве с помощью кнопки
**Загрузить все данные**.
Для работы с собранными в ходе сканирования данными выберите на странице
**Результаты сканирований** вкладку
**Собранные данные**.
<img  src="/smimg/image65.png" />
На данной вкладке доступны данные, собранные во время сканирования
приложения всеми включенными в профиле модулями. Модуль для просмотра
собранных данных может быть выбран из выпадающего списка в верхнем левом
углу. Каждый из модулей собирает данные, специфичные только для него.
Соответственно, формат представления данных на вкладке отличается для
каждого модуля.
На рисунке выше в качестве примера приведены данные, собранные модулем
«Сетевая активность». В этом случае были собраны данные, переданные по
сети --- адрес, хост, протокол, время, метод, порт, а также содержание
запроса и ответа. Такого сорта дополнительная информация может оказаться
полезной в работе с результатами анализа.
На рисунке ниже приведен еще один пример, иллюстрирующий другую область
работы приложения --- данные, собранные модулем «Отслеживание Activity».
Здесь Activity --- это все различные экраны приложения, которые были
запущены во время сканирования. Для каждого экрана (Activity) приведены
его имя и параметры запуска.
`<img src="/img/image11.png" />
Результаты работы всех модулей собраны в одной системе, что значительно
упрощает их анализ. Такой подход обладает явными преимуществами по
сравнению с ситуацией, когда данные о работе приложения последовательно
и в различных форматах собираются несколькими утилитами.
Помимо предоставления пользователям возможности работы с собранными
данными, система на их основе делает выводы об уязвимостях приложения.
Правила анализа собранных данных для поиска уязвимостей подробно описаны
в
разделах `<a data-xref="{title}" href="Pravila.htm">Правила`</a> Руководства
пользователя
и `<a href="../aag/pravila_analiza_na_urovne_organizacii.htm" title="Правила анализа на уровне Организации">Правила
анализа на уровне Организации`</a> Руководства прикладного
администратора.

Требования

Для работы с требованиями выберите на странице
**Результат сканирования** вкладку
**Требования**. На этой вкладке
отображаются результаты проверки выполнения требований для
проанализированного приложения. На вкладке
**Требования** представлено соответствие
стандартам безопасности, выбранным в профиле сканирования. Требования и
стандарты, в которых были выявлены несоответствия, отмечаются красным
цветом.
`<img src="/img/image12.png" style="cursor: nwse-resize;" />
Красным цветом отмечены требования, которые не выполнены. Если кликнуть
мышкой по невыполненному требованию на вкладке **Стандарт
**в левой части, в правой части на вкладке
**Дефекты **появится список типов
дефектов, которые были проверены для выбранного требования.
`<img src="/img/image10.png" />
В случае обнаружения дефектов определенного типа при проверке
требования, этот тип дефектов отмечается значком
«`<img alt="Picture 21" height="12.4" src="/smimg/image69.png" width="13.9" />»,
а само требование считается невыполненным и отмечается красным цветом.
Если дефектов определенного типа при проверке требования выявлено не
было, такой тип дефектов отмечается значком
«`<img alt="Picture 23" height="11.4" src="/smimg/image70.png" width="14.3" />».
Требование в целом считается выполненным, если при его проверке не было
выявлено ни одного дефекта из числа относящихся к этому требованию типов
дефектов.
При нажатии в области **Дефекты **на тип
дефекта, отмеченного значком
«`<img alt="Рисунок 56" height="15.3" src="/smimg/image71.png" width="15.3" />»,
появится окно с детальной информацией по дефектам данного типа:
`<img src="/img/image68.png" />
Для возвращения к списку требований нажмите кнопку
**Вернуться к списку требований** в левом
верхнем углу.
На вкладке **Требования** доступны данные
по выполнению требований всех выбранных в профиле сканирования
стандартов. Если в профиле добавить еще один стандарт к списку
проверяемых, то после этого при просмотре результатов всех уже ранее
проведенных с этим профилем сканирований, на вкладке
**Требования** будет отображаться также
соответствие ранее собранных результатов и вновь выбранного в профиле
стандарта.

Запись сканирования

Данная вкладка доступна только для результатов автоматического
сканирования и предоставляет возможность просмотра видеозаписи
проведенного сканирования и процесс выполнения тест кейса.
<img alt="Рисунок 11" src="/smimg/image73.gif" style="cursor: nwse-resize;" />
``
</p>
```
``
<p class="a5" style="text-align: center">
```
 
``
</p>
```
``
</body>
```
``
</html>
```

# Автоматическое сканирование

Автоматическое сканирование

Для запуска сканирования в автоматическом режиме необходимо сделать
следующие шаги:

Выбрать и загрузить файл мобильного приложения с расширением *.apk или
*.ipa, для которого будет проводиться сканирование.`<br />
**Примечание:** Если пакет с выбранным
именем и хеш суммой уже загружен, в целях экономии ресурсов его
повторная загрузка не производится, а используется файл, уже имеющийся
на сервере.
Выбрать проект из выпадающего списка существующих в системе
проектов.`<br /> **Примечание:**
Для выбора доступны либо проекты с незаполненным при создании полем
**Имя пакета** (см.
раздел `<a data-xref="{title}" href="Projects.htm">Проекты`</a>),
либо те, для которых в данном поле указан пакет, выбранный в предыдущем
шаге. Таким образом, не исключена ситуация, когда в данном поле будут
отсутствовать доступные для выбора элементы. В этом случае следует
создать новый проект с пустым полем **Имя
пакета** или, указав в нем соответствующий пакет.
Выбрать профиль сканирования из выпадающего списка.
Выбрать **Автоматический** режим
сканирования из выпадающего списка.
Во вновь появившемся внизу поле выбрать имя уже существующего в системе
тест кейса для запуска сканирования в автоматическом режиме.
Выбрать архитектуру, на которой будет проводиться сканирование. Отметим,
что в данном поле будет доступна для выбора только та архитектура, на
которой был записан тест кейс и которая активна в системе.
``
</li>
```
``
</ul>
```
``
<p class="a1" style="text-align: center">
```
`<img alt="Рисунок 43" src="/smimg/image76.png" />
По нажатию кнопки **Запустить
сканирование** происходит переход на страницу
**Запуск сканирования**. Будет отображена
страница с экраном устройства без возможности взаимодействия с ним.
Передача изображения с экрана устройства необходима для анализа работы
тест кейса. В ходе сканирования на экране устройства отображаются
следующие статусы:
``
</p>
```
``
<ul class="Disc">
```
``
<li class="a1">
```
**Поиск свободного устройства** ---
осуществляется поиск свободного сканирующего агента.
``
</li>
```
``
<li class="a1">
```
**Запуск приложения** --- выполняется
запуск приложения.
``
</li>
```
``
</ul>
```
``
<p class="a1" style="text-align: center">
```
`<img alt="Рисунок 59" src="/smimg/image77.png" />
Во время проведения автоматического сканирования также идет запись
видео, которое при завершении доступно на вкладке
**Запись сканирования** на странице
**Результат сканирования** для данного
теста.
При нажатии на кнопку **К результатам
сканирований** будет осуществлен переход к странице со
списком всех сканирований. При переходе на страницу
**Результаты сканирований** можно увидеть
новую строку, отображающую текущий результат автоматического
сканирования со статусом **Запущен**. При
нажатии на строку таблицы, когда соответствующее сканирование имеет
статус **Создан**,
**Запускается** или
**Запущен** происходит возврат на
страницу с экраном устройства. После завершения сканирования приложения
статус примет значение **Анализируется**
на время обработки полученных результатов. Затем статус сканирования
поменяется на **Успешно** или
**Ошибка** в зависимости от результата.
Если нажать на строку, когда сканирование имеет статус
**Анализируется**,
**Успешно** или
**Ошибка**, произойдет переход на
страницу **Результат сканирования**, см.
раздел
`<a data-xref="{title}" href="Rezultaty_skanirovanij.htm">Результаты
сканирований`</a>.
 
``
</p>
```
``
</body>
```
``
</html>
```

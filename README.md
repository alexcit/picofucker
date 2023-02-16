# PicoFUCKER v0.0.1 (название рабочее)

Приложение - мультитул со всякими полезными штуками для Pico4 (и Pico3)

### Некоторые функции:

* установка adb драйвера
* перезагрузка adb и шлема
* запуск трансляции со шлема на комп одной кнопкой
* переключатель региона
* прошивка в пару кликов (с автообнаружением нужной прошивки)

### TODO (в порядке приоритета):

* нормальный инсталлятор
* установка приложений с флагами (-d, -t и др.) с автоматической распаковкой obb
* локализация на другие языки
* включение режима usb-модема для VD/SA по кабелю одной кнопкой
* управление приложениями на манер adb app control / sidequest
* сборник гайдов
* лаунчер игр (автоматическое скачивание и установка)
* агрегатор 3д кино
* сообщество (поиск команды, нетворкинг)

Пожелания, предложения, рекомендации, **баги** [сюда](https://t.me/pys02), либо в issues на гитхабе, для тех кто шарит.

Если у вас возникло непреодолимое желание поддержать разработку, можете сделать это на карточку  
`2200 7001 4118 1551` (тиньк). За другими способами пока в личку.

Отмечу, что я студент, которому надо работать работу и писать диплом, поэтому не могу гарантировать стабильности обновлений

# Установка (пока не запилю нормальный вариант):
**ЧИТАТЬ ВСЁ, ПОТОМ ДЕЛАТЬ** 
1. [Скачать python 3.11](https://www.python.org/ftp/python/3.11.2/python-3.11.2-amd64.exe)
2. Установить скачанный файл. В инсталляторе отметить все галочки. Особенно важно отметить галочку со словом PATH и на последнем шаге прожать "убрать лимит символов" или что-то в этом роде
3. На странице, где вы это читаете, нажать на зеленую кнопку "Code", там выбрать "Download ZIP"
4. Распаковать архив в любое место. **В ПУТИ ДО ПАПКИ НЕ ДОЛЖНО БЫТЬ РУССКИХ СИМВОЛОВ!!!**. Идеально создать папку в корне диска (D:/picofucker)
5. Открыть скачанную папку. Запустить файл `setup.bat`. Подождать. Сначала оно "зависнет", потом пойдет установка пакетов. Если что-то спросят, нажать Y, Enter. После установки окно само закроется.
9. После установки запускать через файлик `start.bat`. Можете отправить ярлык на рабочий стол. Если вас смущает черное окно консоли, можете в настройках ярлыка выбрать "Окно: Свернутое в значок"

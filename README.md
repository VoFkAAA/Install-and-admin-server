## ВКС Труконф
### Сайт: <a href = "https://trueconf.ru/">https://trueconf.ru/</a> 

<br>

<table style="border-collapse: collapse; width: 100%; text-align: center;">
    <tr style="background: #f0f0f0;">
        <th style="border: 1px solid black; padding: 8px; width: 5%;">№</th>
        <th style="border: 1px solid black; padding: 8px; width: 30%;">Задача</th>
        <th style="border: 1px solid black; padding: 8px; width: 40%;">Что сделано</th>
        <th style="border: 1px solid black; padding: 8px; width: 25%;">Комментарии</th>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px; text-align: center;">1.</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">Установить и настроить тестовое окружение</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            1. Создана виртуальная машина в VirtualBox (сеть - Bridged)<br>
            2. На ВМ установлена ОС Debian 11<br> 
            3. Установлен и зарегистрирован сервер (<a href="https://trueconf.ru/blog/baza-znaniy/kak-za-15-minut-razvernut-sistemu-videokonferenczij-na-baze-os-linux">Инструкция</a>, в частности <a href="https://drive.google.com/file/d/1boVUhuiRnulsl5iJfHWeWo964geDfGD7/view?usp=sharing">Установка на ВМ</a>)<br>
            4. Cервер доступен через веб-интерфейс Windows Home по адресу http://192.168.x.xxx
        </td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            <a href = "https://drive.google.com/file/d/1StArRbdbQy2-yv6iwfLIQQsHcpjjsXzK/view?usp=sharing">Сервер нельзя установить на Windows Home, так как нужна возможность управления группами</a>
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px; text-align: center;">2.</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">Создать учётные записи пользователей</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            1. В панели управления (в Windows) <a href = "https://drive.google.com/file/d/1lOiTcU3eSB-xdzZcfdPFJwqsGVFRjFEr/view?usp=sharing">созданы 2 пользователя</a>: vboxuserone и vboxusertwo<br>
            2. В Debian 11 создан тестовый <a href = "https://drive.google.com/file/d/1PkxZSalLoOhobZysse9mqK4JvMnS9iDr/view?usp=sharing">пользователь qa_sidorov</a>
        </td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px; text-align: center;">3.</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">Спроектировать минимум 15-20 тест-кейсов для блока Web → Settings, Security, HTTPS</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            Спроектированы  <a href = "https://docs.google.com/spreadsheets/d/131XiJP7WfbO_nUcZc_6E8-WZKj-o-PBFNV7T-DqVyiQ/edit?usp=sharing"> 52 тест-кейса в виде таблицы</a>
        </td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            Выполнены ключевые проверки основного функционала (в т.ч. негативные)
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px; text-align: center;">4.</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">Установить десктопное и мобильное приложения</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            1. Установлено <a href = "https://trueconf.ru/downloads/windows.html">десктопное приложение для Windows</a><br>
            2. Установлено <a href = "https://trueconf.ru/downloads/android.html">мобильное приложение для Android</a> 
        </td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            Подключение к серверу настроено через локальную сеть
        </td>
    </tr>
    <tr>
        <td style="border: 1px solid black; padding: 8px; text-align: center;">5.</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">Войти под учётными записями созданных (в п.2) пользователей в десктопном и мобильном приложениях</td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
            1. Выполнена авторизация <a href = "https://drive.google.com/file/d/1TmFMnh-bwZ78yAy2EezEknaGYaDdiMYp/view?usp=sharing">пользователя vboxuserone</a> в десктопном приложении<br>
            2. Выполнена авторизация <a href = "https://drive.google.com/file/d/15GJpMg_r06kFItTvRfwc7qdX6mnSUGB1/view?usp=sharing">пользователя vboxusertwo</a> в мобильном приложении<br>
            3. Выполнен <a href = "https://drive.google.com/file/d/1VHJOz4_mwCSvZux5E5YQeeCoCOtD_jxi/view?usp=sharing">прозвон</a> со смартфона на десктоп
        </td>
        <td style="border: 1px solid black; padding: 8px; text-align: left;">
        </td>
    </tr>
</table>
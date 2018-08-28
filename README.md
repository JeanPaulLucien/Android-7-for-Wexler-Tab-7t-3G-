# New Android for Wexler Tab 7t + 3G
This repository for developers and other contributors who wish to provide Android 7 support to Wexler Tab 7t

Этот проект находится в стадии разработки или подготовки к разработке. Если вы желаете помочь, дайте знать.

## Задачи и цели проекта
* Получить актуальную систему Android для устройства
  * увеличить базу доступного программного обеспечения
* увеличить производительность за счёт роста частот процессора и графики (в разумных пределах)
* сделать полноцееный телефон, добавив долгожданную возможность звонить и принимать звонки

# Документация

## Я ищу
Вся информация, которая вытащена с устройства публикуется здесь: https://github.com/JeanPaulLucien/New-Android-for-Wexler-Tab-7t/tree/from-device
Если какой-то информаций там нет, напишите в https://github.com/JeanPaulLucien/New-Android-for-Wexler-Tab-7t/issues/2

## Получение dmesg (наипростейший путь)
* нужен root. Вероятно, что уже есть, у меня работает с https://www.kingoapp.com/
* ставим Терминал https://play.google.com/store/apps/details?id=jackpal.androidterm&hl=ru и ярлык делаем на виду для удобства
* перезагружаем устройство (выкл/вкл)
* запускаем Терминал и пишем (команда на строку)
  * su
  * dmesg -> sdcard/Download/filename.txt
    * filename - имя файла на англ., можете назвать dmesg, можете ololo
  * exit - писать пока Терминал не закроется
* dmesg лежит в папке "Загрузки", делайти с ним, что хотите. Поздравляю, вы неподражаемы! 

# htaccess
htassess
Для единообразия формирования URL страниц сайтов, и предотвращения появлений дубликатов страниц, вводится стандартная часть файла. .htaccess. 
Последовательность установки:
Данный конфиг позволяет решить сдедующие задачи: 
Активация канонических директив
Установить основное зеркало сайта с www или без него
Удалить любое количество "/" стоящих рядом до 1 ///--> / 
Удалять "/" в конце URL если это файл 
 Добавлять "/" в конце URL если его там нет и это не файл
 Удалить из URL index.php
Последовательность установки:
1
Вставить код в начале .htaccess
2
При вставке требуется указать правильное зеркало сайта, раскоментировав нужное
3
Удалить старый redirect перенаправление на основное зеркало. 
4
Проверить все новые redirect(ы) на  правильную работу  в условиях данного проекта.
Код конфигурационного файла каталога .htaccess.

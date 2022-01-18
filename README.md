**Gulp**  
**HTML5**  
**SCSS**  
**Swiper**  
**LightGallery**  
**JSON** 

# gulp-scss-starter

Установка и работа с шаблоном (с правами администратора):
В терминале:
1) npm i
2) gulp
Шаблон начнет работать в режиме разработчика, без сжатия картинок и кода.

Когда верстка закончена и пришло время грузить на сервер/отдавать заказчику:
1) gulp build

Выполнится оптимизация кода и картинок. 

Внимание! 
После выполнения gulp build создаются webp файлы картинок, которые интегрируются в html и css. 
Следовательно, стоит проверить корректность их отображения.
Если после выполнения gulp build файлы редактировались, действие (gulp build) нужно повторить.

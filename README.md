# 
Подготовка:
Для начала следует разбить картинку на фрагменты и записать фрагменты в файлы, для этого используется программа - split_to_dataset.py, и при необходимости записать в файле с обучением сети количество фрагментов в файле (это выводится при работе программы)
#
Далее до обучения следовать блокам в ices_my.ipynb (при необходимости изменить параметры), из-за 3-х канальности изображения данные занимают больше места, и обучение идет не так эффективно как могло бы.
#
После обучения идут блоки с выводом прогноза (стоит изменять названия вход/выходящего изображения), после визуализация маски на изображение и сохранение изображения

# Skolkovo
в папке DDPM клонирован репозиторий из условия задания, адаптирована модель для датасета Flowers102
код в [ноутбуке](https://github.com/borinya/Skolkovo/blob/main/DDPM/train_flowers102.ipynb).
Примеры сгенерированных цветов в [папке](https://github.com/borinya/Skolkovo/tree/main/DDPM/contents )

в папке Graphs_task [модуль с классом](https://github.com/borinya/Skolkovo/blob/main/Graphs_task/graphs.py), 
[ноутбук с использованием класса графа](https://github.com/borinya/Skolkovo/blob/main/Graphs_task/Graphs.ipynb)
# класс реализован при помощи списков смежности в виде хэш таблицы(dict в питоне), по задаче спрашивают по факту длину максимального пути, но возникают нюансы в виде нечетных циклов путей в графе
# как минимум число позванных гостей $>=$ число изолированных вершин (интровертов)
# Максимум <= половина самого длинного пути в графе +  число изолированных вершин


[папка с образом докера и скриптами BASH](https://github.com/borinya/Skolkovo/tree/main/docker%2Bbash)

скрипты запускать при помощи команд:

# docker exec inspiring_borg bash ./home/word_stats.sh ./home/dracula.txt
# docker exec inspiring_borg bash ./home/making_files.sh ./home/dracula.txt

# RepoLab  
Репозиторий предназначен для хранения лабораторных и курсовых работ.  
## Часть 1. ChangeMAC  
Проект ChangeMAC получает на вход данные (Имя файла, MAC-адрес, кол-во повторяющихся адресов).
Задача - прочитать из поданного на вход файла данные, в которых могут встречаться переносы строк. 
Найти МАС-адрес, поданный на входе, в тексте файла и заменить на рандомный юникастный. МАС-адрес
может встречаться не раз. Последний аргумент указывает какое количество адресов подряд необходимо
заменить на один и тот же.
Практическое применение - формирование набора пакетов для DoS и DDoS атак.
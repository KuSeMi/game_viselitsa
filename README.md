# Консольная версия детской игры "Виселица"
С подробным описанием можно ознакомиться по ссылке:
[Ссылка](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))

Программа написана на языке Ruby [Ссылка](https://ru.wikipedia.org/wiki/Ruby)
# Описание
У пользователя есть 7 попыток, чтобы угадать слово, загаданное компьютером. Данная игра сопровождается консольной псевдографикой.
# Запуск программы
- Необходимо скачать либо клонировать репозиторий с игрой
- Перейти в командной строке/терминале в папку с файлами программы
- Установить необходимые библиотеки:
     ```
       gem install bundler
     ```
- Затем запустить в терминале с помощью интерпретатора ruby файл:

   ```
   bundle exec ruby viselitsa.rb
   ```

# Добавление новых слов в игру
- Необходимо перейти в папку с файлами программы
- Далее открыть папку "data"
- В текстовом файле words.txt нужно добавить новое слово с новой строки


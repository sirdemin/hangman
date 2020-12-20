# Висилица

Игра "Виселица" для тебя и твоих друзей!

[Статья на wikipedia](https://ru.wikipedia.org/wiki/%D0%92%D0%B8%D1%81%D0%B5%D0%BB%D0%B8%D1%86%D0%B0_(%D0%B8%D0%B3%D1%80%D0%B0))

# Скриншоты

![Начало игры](https://i.imgur.com/oSK7LTJ.png)

![Игра идёт](https://i.imgur.com/r73tSQq.png)

# Правила

* Компьютер загадывает слово и показывает сколько в нём букв игроку
* Игрок вводит буквы по одной
* Если буква в слове есть, она показывается в слове игроку
* Если слово отгадано полностью игрок победит
* После каждой ошибки, дорисовывается виселица
* У игрока всего 7 ошибок


# Как запустить

```
git clone git@github.com:sirdemin/hangman.git
cd hangman
bundle install
ruby main.rb
```

# Куда добавить новые слова

**Обязательно заглавными буквами** новые слова добавлять в `data/words.txt`.

# Версия

**ruby 2.7.2**

# Автор

[Илья Д.](https://github.com/sirdemin)

© 2020

# Text

Cоздать приложение, разбирающее текст из файла и позволяющее выполнять с текстом три различных операции.

### Требования
+ Разобранный [текст](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Text) должен быть представлен в виде объекта, содержащего, например, [абзацы](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Paragraph), [предложения](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Sentence), [лексемы](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Lexema), [слова](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Word), 
[символы](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Symbol). Лексема – часть текста, ограниченная пробельными символами. Использовать [Composite](https://github.com/darya1500/epamtc/blob/master/src/main/java/by/epam/learn/daryatarasevich/text/entity/Composite).
+ Классы с информацией являются [классами сущностей](https://github.com/darya1500/epamtc/tree/master/src/main/java/by/epam/learn/daryatarasevich/text/entity) и не должны быть перенагружены методами [логики](https://github.com/darya1500/epamtc/tree/master/src/main/java/by/epam/learn/daryatarasevich/text/action).
+ Разобранный текст необходимо восстановить в первоначальном виде. Пробелы и знаки табуляции при разборе могут заменяться одним пробелом.
+ Для деления текста на составляющие следует использовать регулярные выражения. Регулярные выражения для приложения определять
как литеральные константы.
+ Код, выполняющий разбиение текста на составляющие части, следует оформить в виде классов-парсеров с использованием 
Chain of Responsibility.
+ При разработке парсеров, разбирающих текст, необходимо следить за количеством создаваемых объектов-парсеров.
+ Для записи логов использовать Log4J.
+ Реализовывать индивидуальные задания по работе над текстом.

#### Индивидуальные задания
+ Отсортировать абзацы по количеству предложений.
+ Отсортировать слова в предложении по длине.
+ Отсортировать предложения в абзаце по количеству слов.

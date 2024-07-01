**Задание**

В клонированном репозитории:

1) Найдите полный хеш и комментарий коммита, хеш которого начинается на aefea.

2) Ответьте на вопросы.

- Какому тегу соответствует коммит 85024d3?
- Сколько родителей у коммита b8d720? Напишите их хеши.
- Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами v0.12.23 и v0.12.24.
- Найдите коммит, в котором была создана функция func providerSource, её определение в коде выглядит так: func providerSource(...) (вместо троеточия перечислены аргументы).
- Найдите все коммиты, в которых была изменена функция globalPluginDirs.
- Кто автор функции synchronizedWriters?


**Решение**

1)  Найдите полный хеш и комментарий коммита, хеш которого начинается на aefea.
   
    ![alt text](https://github.com/mezhibo/Git-tools/blob/f940792f5ce18bf7558f108f5dae06d8a1339256/IMG/1.jpg)


    ![alt text](https://github.com/mezhibo/Git-tools/blob/f940792f5ce18bf7558f108f5dae06d8a1339256/IMG/2.jpg)


2) Ответьте на вопросы.

- Какому тегу соответствует коммит 85024d3?

  ![alt text](https://github.com/mezhibo/Git-tools/blob/486eae4fa5b28838232312c75900dcd84ed3a1e5/IMG/3.jpg)

- Сколько родителей у коммита b8d720? Напишите их хеши.

  ![alt text](https://github.com/mezhibo/Git-tools/blob/2effbc34dba3883b592cbdc523b1fbd5d713aea2/IMG/4.jpg)

- Перечислите хеши и комментарии всех коммитов, которые были сделаны между тегами v0.12.23 и v0.12.24.

  ![alt text](https://github.com/mezhibo/Git-tools/blob/68d2fff73b23b5f2767b29862b85b375783c6f84/IMG/5.jpg)

- Найдите коммит, в котором была создана функция func providerSource, её определение в коде выглядит так: func providerSource(...) (вместо троеточия перечислены аргументы).

  Ищем нужный нам коммит подходящий по условию

  ![alt text](https://github.com/mezhibo/Git-tools/blob/413a9541d6ca7f8a830be23b0b32d05a13561f40/IMG/6.jpg)

  Теперь просмотрим первый найденный коммит и найдем нужную нам строчку. Вроде бы строчка нам нужная, но по условию мы должны найти СОЗДАННУЮ функция, а в этом коммите она удаляется.

  ![alt text](https://github.com/mezhibo/Git-tools/blob/413a9541d6ca7f8a830be23b0b32d05a13561f40/IMG/7.jpg)

  Поэтому просмотрим содержимое второго найденного коммита

  ![alt text](https://github.com/mezhibo/Git-tools/blob/ef185e8f6c66c26bf8f59d1217c58f9782fca60a/IMG/8.jpg)

  Этот коммит теперь соответствует нашим условиям.

- Найдите все коммиты, в которых была изменена функция globalPluginDirs.

  Ищем файл, в котором есть строка с нужной нам функцией

  ![alt text](https://github.com/mezhibo/Git-tools/blob/65acb56d75e0e968cb2e59e8169b465a73e9590d/IMG/9.jpg)

  Теперь ищем непосредственно в найденном нами файле

  ![alt text](https://github.com/mezhibo/Git-tools/blob/84c4f9ea79b22705e43f9ab53a4aa261c85869e3/IMG/10.jpg)


  - Кто автор функции synchronizedWriters?
    Выведем список со всем авторами функции synchronizedWriters
    
    ![alt text](https://github.com/mezhibo/Git-tools/blob/41a85cfb80246bc0f955fba9212f13bf3733c64e/IMG/12.jpg)
  
   


  
  

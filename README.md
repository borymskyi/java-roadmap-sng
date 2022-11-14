# :scroll: Roadmap Java developer [СНГ]

Структурированный список ресурсов для изучения Java, который поможет систематизировать занятия. Основан на личном опыте и самостоятельном изучении данной области.




## Содержание
* [JAVA CORE](#java-core)
* [ALGORYTHMS & DATA STRUCTURES](#algorythms--data-structures)
* [SQL & JDBC](#sql--jdbc)
* [HTTP & SERVLETS](#http--servlets)
* [MAVEN & GRADLE](#maven--gradle)
* [SPRING](#spring)
* [JPA & HIBERNATE](#jpa--hibernate)
* [TESTING](#testing)
* [Идем на работу](#идем-на-работу)
* [Дополнительный материал](#дополнительный-материал)





## JAVA CORE
> Это целый ряд тем. Оновные: **ООП в Java**, **Ветвление, Циклы**, **Массивы**, **Исключения**, **Коллекции**, **Внутренние классы**, **Ввод-вывод**, **Многопоточность**, **Stream API**, и еще разный ряд базовых принципов для использование всего, например основные классы Java (Object) и тд.

* Java Core с нуля *[Link 1](https://coursehunter.net/course/java-dzhava-dlya-nachinayushchih-s-nulya-do-sertifikata-oracle) | [Link 2](https://youtube.com/playlist?list=PLqj7-hRTFl_rqruGcnd2V8SPbY0j9DzT5)*
* Java Core продвинутый *[Link 1](https://coursehunter.net/course/java-poluchi-chernyy-poyas) | [Link 2](https://youtube.com/playlist?list=PLqj7-hRTFl_oDMBjI_EstsFcDAwt-Arhs)*
* Книги: *[Java Полное руководство Г.Шилдт | Java Эффективное программирование Д.Блох | Философия Java Брюс.Экк](https://t.me/dmytrii_bookshelf)*
* Практика: *[Codewars](https://www.codewars.com/kata/search/java?beta=false&order_by=popularity+desc&q=&r%5B%5D=-8&tags=)* | *[CodingBat](https://codingbat.com/java)* | *[Практические задачи по Java](https://habr.com/ru/post/440436/)* | *[1000 задач на Java](https://github.com/allicen/Java-1000)*

<details>
<summary> Дополнительный материал </summary>

Ниже *[лекции от Головача](https://youtube.com/playlist?list=PLoij6udfBnciBZf7aLRmayAzcisWfAwOY)* которые покрывают пробелы в знаниях.

* Java Core Процедурное программирование(детали основ), итерация, рекурсия, динамические структуры данных, память в Java:
  * *[Additional#1.Dec2013(Сети база) №1](https://youtube.com/playlist?list=PLoij6udfBncjdjKiKlnqikkIjrPLFeivp)*
  * *[Additional#2.SQL.Dec2013 №2](https://youtube.com/playlist?list=PLoij6udfBnchYCncZyAzZyFjTGkXIKc7B)*
  * *[(Итерация) Java Core December: Procedural Java. Лекция #1 №3](https://youtube.com/playlist?list=PLoij6udfBncigG7gvCLBMd3y0mR_ekCv8)*
  * *[(Итерация) Java Core December: Procedural Java. Лекция #2 №4](https://youtube.com/playlist?list=PLoij6udfBncjzPJ4yyysa4Fqz1BrZH3g9)*
  * *[(Рекурсия) Java Core December: Procedural Java. Лекция #3 №5](https://youtube.com/playlist?list=PLoij6udfBncifDy8AjaU5wcG_UDPjDSSb)*
  * *[(Динамические структуры данных) Java Core December: Procedural Java. Лекция #4 №6](https://youtube.com/playlist?list=PLoij6udfBncijqEUPXhY-NS0ZKWALlN0B)*
  * *[(Память в Java) Java Core December: Procedural Java. Лекция #5 №7](https://youtube.com/playlist?list=PLoij6udfBncilPJMzXtsOyUutDDULrtEm)*

* Исключения в Java, механика работы исключений, throws + checked/unchecked, иерархия исключений, классификация исключений, "устройство": message, cause, custom fields, сцепленные исключения, стратегии обработки ошибок, try-with-resources (+ suppressed exceptions), multi-catch (+ more precise rethrow):
  * *[(Основы иключения) Java Core December: Exceptions. Лекция #6 №1](https://youtube.com/playlist?list=PLoij6udfBncilVuX_R0sBrESIlyfQWVjm)*
  * *[(try-with-resources, иерархия) Java Core December: Exceptions. Лекция #7 №2](https://youtube.com/playlist?list=PLoij6udfBnchbxh8ZAY-FPlmj97aCILTY)*
  * *[(checked/unchecked, иерархия) Java Core December: Exceptions. Лекция #8 №3](https://youtube.com/playlist?list=PLoij6udfBncjLoxagaF5tGsDp-0XKMyhc)*
  * *[() Java Core December: Exceptions. Лекция #9 №4](https://youtube.com/playlist?list=PLoij6udfBnchR-Cc-RB4EUZokLrLlIuWQ)*

* Java I/O, byte-ориентированные потоки, char-ориентированные потоки, java-type-ориентированные потоки(классы-адаптеры, классы-декораторы, работа с файловой системой, сериализация и клонирование)
  * *[(кодировка) Java Core December: IO. Лекция #10 №1](https://youtube.com/playlist?list=PLoij6udfBncidoWbNwteMhqkE_uxcnWP1)*
  * *[(адаптеры/декораторы) Java Core December: IO. Лекция #11 №2](https://youtube.com/playlist?list=PLoij6udfBnchhzsjZkAbhW-V1K5dM-_Xf)*
  * *[(адаптеры/декораторы) Java Core December: IO. Лекция #12 №3](https://youtube.com/playlist?list=PLoij6udfBncgBHx7HxK8gAxV-oqT_pOob)*

* Java Collection API (big-O notation, Java generics, Iterable / Iterator, Collection API (general), List/ArrayList/LinkedList, Set/List/Map/SortedSet/SortedMap, HashSet/HashMap/hashCode()/equals(), TreeSet/TreeMap/Comparable/Comparator, Collection API (detailed)):
  * *[Java Core December:Collections API. Лекция #13 №1](https://youtube.com/playlist?list=PLoij6udfBncjiXKA5ce0hi4b4DIvGymeo)*
  * *[(дженерикс) Java Core December:Collections API. Лекция #14 №2](https://youtube.com/playlist?list=PLoij6udfBnciAPeXh5oOGBsQ2c8GlEFu0)*

* Продолжение Java IO, Стримы, адаптер/декоратор, клонирование, файловая система:
  * *[Java Core December: IO. Лекция #15 №4](https://youtube.com/playlist?list=PLoij6udfBnci29otnZedLq6x-EPlx3I4f)*

* Продолжение Java Collection:
  * *[(нотации О, equals list, сд хеш сет, мап и тд.) Java Core December: Collections. Лекция #16 №3](https://youtube.com/playlist?list=PLoij6udfBncgIlUdvGNtG2Jp7gXbDMx15)*
  * *[(хеш сет и хеш мап, структуры данных) Java Core December: Collections. Лекция #17 №4](https://youtube.com/playlist?list=PLoij6udfBncjAZTDf6Vx281R5Y9mnm93q)*

* Многопоточность(введение, Thread/Runnable run(), start(), join(), currentThread(), Модель памяти джавы, монитор, synchronized и многое другое, прерывание потока):
  * *[Java Core December: Multithreading. Лекция#18 №1](https://youtube.com/playlist?list=PLoij6udfBncgjoaFqWZSh3L-THigDum7g)*
  * *[Java Core December: Multithreading. Лекция#19 №2](https://youtu.be/Y0OaihQCFpg)*
  * *[(монитор) Java Core December: Multithreading. Лекция#20 №3](https://youtu.be/8rdrpSSV-wg)*

* Объектно-ориентированная Java(конструирование объекта, методы класса Object, перегрузка метода (overload), переопределение метода (overriding), и тд):
  * *[(конструирование объекта) Java Core December: OOP. Лекция#21 №1](https://youtu.be/150u5ofBzhc)*
  * *[Java Core December: OOP. Лекция#22 №2](https://youtube.com/playlist?list=PLoij6udfBncgtdSaq4nqVNtTqPeyh7rnV)*
  * *[(nested/inner) Java Core December: OOP. Лекция#23 №3](https://youtube.com/playlist?list=PLoij6udfBnciXh1_Itg-Hiw9EdGGzwYPE)*
  * *[(singleton,enom,multiton) Java Core December: OOP. Лекция#24 №4](https://youtube.com/playlist?list=PLoij6udfBncjjuiZQNFx_b4A5Ygdn1YbS)*
  * *[(gof, uml и тд)Java Core December: OOP. Лекция#25 №5](https://youtube.com/playlist?list=PLoij6udfBnch50JMDvipTQmAp-q4Pw6jG)*
</details>




## ALGORYTHMS & DATA STRUCTURES
> Нужно уметь применять наиболее эффективные способы решения некоторых задач, а для этого стоит быть в курсе базовых алгоритмов и структур данных: **Algorythms**(Различные сортировки, поиск значений, поиск кратчайшего пути и тд.), **Data Structures**(Списки, Очереди, Мапы, Деревья, Графы и прочее).

* Книги. *[Грокаем алгоритмы Б.Адитья | Алгоритмы. Построение и анализ](https://t.me/dmytrii_bookshelf)*
* Практика:
  * Вариант 1. Заходим на сайт *[LeetCode](https://leetcode.com/)* в разделе Explore заходим в лист *[Top Interview Questions](https://leetcode.com/explore/interview/card/top-interview-questions-easy/)* (Easy / Medium / Hard) -> берем задание -> смотрим теги задачи(Related Topics) -> берем книгу и читаем нужную тему.
  * вариант 2: читаем книгу -> узнаем новый алгоритм или структуру данных -> пытаемся написать код который делает тоже самое(сортировки, списки, очереди, поиск в ширину).
  * вариант 3: решаем задачки по теме на *[Codewars](https://www.codewars.com/kata/search/java?beta=false&order_by=popularity+desc&q=&r%5B%5D=-8&tags=)* или *[HackerRank](https://www.hackerrank.com/domains/java?filters%5Bdifficulty%5D%5B%5D=easy&filters%5Bskills%5D%5B%5D=Java%20%28Basic%29)*.

<details>
<summary> Дополнительный материал </summary>

* *[Советы от Ксении по алгоритмам](https://www.youtube.com/watch?v=_NhmGvYs8_g&t=686s)*
* *[Гайды от Жени по структурам данных](https://youtube.com/playlist?list=PLlsMRoVt5sTOKU87z9NhHHRH9nvE5chfH)*
* *[LeetCode гайды от Жени](https://youtube.com/playlist?list=PLlsMRoVt5sTPCbbIW2QZ-hRMW80lymEYR)*
</details>




## SQL & JDBC
* *[Основы SQL за 45 минут](https://youtu.be/IK6e1SFCdow)*
* *[PostgreSQL. Основы SQL](https://youtu.be/uGKIXTUjZbc)*
* *[JDBC: Введение в JDBC](https://youtube.com/playlist?list=PLIU76b8Cjem5qdMQLXiIwGLTLyUHkTqi2)*




## HTTP & SERVLETS
* *[Java EE для начинающих](https://youtube.com/playlist?list=PLAma_mKffTOTTFqIkLXgHqVuL6xJhb0mr)*

<details>
<summary> Дополнительный материал</summary>

* *[Как работает HTTPS](https://youtu.be/B3j4SS5P8tM)*
</details>




## MAVEN & GRADLE
* *[Лекция от Немчинского](https://youtu.be/IAbZVA4tK6M)*
* *[Мавен основы на хабре](https://habr.com/ru/post/77382/)*
* *[Гайд от принга по мавен и градл](http://spring-projects.ru/guides/gradle/)*
* *[Гайд по Градл](https://javarush.ru/groups/posts/2126-kratkoe-znakomstvo-s-gradle)*




## SPRING
> Содержит множество компонентов для работы с разнообразными задачами. **Spring MVC**(для разработки веб-приложений), **Spring Data**(для работы с бд), **Spring Security**(для обеспечения безопасности приложений) и тд. Нужно разобраться с базовыми принципами работы с спринг, на чем все строится. Spring Basics(IoC Container, Spring Beans, Bean Configuration, Bean Wiring и тд).
* *[Статья на хабре о механике Spring Framework и MVC](https://habr.com/ru/post/490586/)*
* *[ru Руководство по Spring](https://proselyte.net/tutorials/spring-tutorial-full-version/)*
* *[База Spring Core, MVC](https://youtube.com/playlist?list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)*
* *[Простой пример Spring Boot app, охвачены темы: MVC, REST API, Flyway](https://youtu.be/q87Xxu4NPIc)*
* *[Полный курс по Spring Framework от dmdev](https://coursehunter.net/course/springnew)*
* *[Spring Boot pet-p](https://youtube.com/playlist?list=PLU2ftbIeotGoGSEUf54LQH-DgiQPF2XRO)*
* *[Spring Boot + Vue.js pet-p](https://youtube.com/playlist?list=PLU2ftbIeotGqSTOVNjT4L3Yfy8jatCdhm)*
* Практика. Написать веб приложение, можно взять пример с вышеупомянутых каналов LetsCode / Alishev

Так же на данном этапе будет хорошим тоном понимать правила/принципы/подходы/стили проектирования такие как: The Clean Architecture, REST, SOLID, MVC:
* *[Принципы Чистой Архитектуры от Дяди Боба](https://blog.cleancoder.com/uncle-bob/2012/08/13/the-clean-architecture.html)*
* *[Создание RESTfull API app с помощью Spring](https://spring.io/guides/tutorials/rest/)*
* *[REST с Spring, туториалы](https://www.baeldung.com/rest-with-spring-series)*
* *[SOLID принципы простым языком с примерами](https://youtu.be/TxZwqVTaCmA)*




## JPA & HIBERNATE
> Спецификация, описывающая, как удобно представлять данные из бд в виде Java объектов. Спецификация не является фреймворком. Она только показывает, что должен уметь реальный фреймворк. А вот фреймворк уже реализует спецификацию. т.е. реальная работа происходит как раз в нем. **Hibernate**(фреймворк, реализующий спецификацию jpf), **ORM**(общее понятие для представления данных из бд в виде java объектов, тогда каждая строка таблицы становится java объектом).
* *[Полный курс по Hibernate](https://coursehunter.net/course/hibernate)*
* *[Гайд/Документация по Hibernate](https://proselyte.net/tutorials/hibernate-tutorial/)*
* *[Документация от спринга](https://docs.spring.io/spring-data/jpa/docs/current/reference/html/#jpa.query-methods.query-creation)*
* *[Learn JPA & Hibernate](https://www.baeldung.com/learn-jpa-hibernate)*




## TESTING
> Позволяет убедиться, что вы не допустили ошибку при написании программы. Это как бы набор маленьких программ на Java, которые проверяют правильность вашей основной программы. Также гарантируют, что будущие изменения кода программы не затронут старую логику. Таким образом вы всегда будете уверены, что ничего не сломали. Это серьезно ускоряет разработку, т.к. вам не приходится каждый раз проверять потенциальные баги. **Junit**(Java фреймворк для написания тестов самых разных видов), **Integration**(прекрасно работает в паре с другими фреймворками, например Spring). Стоит просто разобратся какие бывают виды тестов на джава, как их писать на Junit, что такое моки и тд.
* *[Habr Туториал по JUnit 5](https://habr.com/ru/post/590607/)*
* *[Habr JUnit 5](https://habr.com/ru/post/590607/)*
* *[Habr Тестирование в Java. JUnit](https://habr.com/ru/post/120101/)*




##
<details>
<summary> Лекции которые покрывают пробелы в SQL & JDBC | HTTP & SERVLETS | MAVEN & GRADLE | SPRING | JPA & HIBERNATE | TESTING </summary>

[Ссылка на лекции](https://youtube.com/playlist?list=PLoij6udfBncioun9-sBwpkpTit1SIhWko):

* Обзор Java EE / Обзор Java 8:
  * *[Jun#1.Feb 2014.Additional №1](https://youtube.com/playlist?list=PLoij6udfBnchI9V8WL1wbK67hfuJM9efz)*
  * *[Jun#2.Feb 2014.Additional java 8 №2](https://youtube.com/playlist?list=PLoij6udfBnchzRV3L10ECE0tTasKC7GdV)*

* **Протокол TCP/IP, протокол HTTP (детально) / многопоточная архитектура HTTP-сервера:**
  * *[Junior.February2014.HTTP#1 №1](https://youtube.com/playlist?list=PLoij6udfBnchmBR9V7tdSCsOdtcpPkoxo)*
  * *[Junior.February2014.HTTP#2 №2](https://youtube.com/playlist?list=PLoij6udfBncgYO5FS9U-DcBQlix8FF2Q8)*
  * *[Junior.February2014.HTTP#3 №3](https://youtube.com/playlist?list=PLoij6udfBncgYO5FS9U-DcBQlix8FF2Q8)*

* Servlet API (детально) / Spring MVC:
  * *[Junior.February2014.Servlets#3 №1](https://youtube.com/playlist?list=PLoij6udfBncjHaO5s7Ln4w4BLj5FVc49P)*
  * *[Junior.February2014.Servlets#4 №2](https://youtube.com/playlist?list=PLoij6udfBncgN40Iu3mSn0SK8T-Ug0ByH)*
  * *[Junior.February2014.Servlets#5 №3](https://youtu.be/FCKYkh74BVY)*
  * *[Junior.February2014.Servlets#6 №4](https://youtu.be/xHKT8BUZt54)*

* **Spring / Maven (детально) / Log4j (детально):**
  * *[Junior.February2014.Spring#7 №1](https://youtu.be/7Je56cl0DPE)*
  * *[Junior.February2014.Spring#8 №2](https://youtu.be/fcd6ftSLy6s)*

* Test Driven Development: JUnit, Mockito (детально):
  * *[Junior.February2014 #9_1](https://youtu.be/Khy4TJ1WsWc)*
  * *[Junior.February2014 #9_2](https://www.youtube.com/watch?v=H88JLkYrbYE&list=PLoij6udfBncioun9-sBwpkpTit1SIhWko&index=44)*

* **SQL / JDBC, connection pool (детально) / JPA 2/Hibernate:**
  * *[Junior.February2014.JDBC#9 №1](https://youtube.com/playlist?list=PLoij6udfBncijyqGvf-YLN7hAL0S6nIrG)*
  * *[Junior.February2014.JDBC#10 №2](https://youtube.com/playlist?list=PLoij6udfBncgGpXnVrDElGWoIhZMJTzr6)*
  * *[Junior.February2014.JDBC#11 №3](https://youtube.com/playlist?list=PLoij6udfBncjQ6nd4jZvelDojOLkdITDq)*
  * *[Junior.February2014.JDBC#12 №4](https://youtube.com/playlist?list=PLoij6udfBncgy-PDoYGvxyZ5L5GnqV_2R)*
  * *[Junior.February2014.JDBC#13 №5](https://youtube.com/playlist?list=PLoij6udfBncjY0jx7t8Sc-V_qoNZM5gAu)*
  * *[Junior.February2014.JDBC#14 №6](https://youtube.com/playlist?list=PLoij6udfBncigW-7YJku0LlQTDlMwmL33)*
  * *[Junior.February2014.JDBC#15 №7](https://youtube.com/playlist?list=PLoij6udfBncj5beNvOYxtPhOkAPKVYnFz)*

* OOD(SOLID)
  * *[Junior.February2014.OOD#16](https://youtube.com/playlist?list=PLoij6udfBncgRuXhcs1gsWhUlS_8ZOLbg)*

* GOF(Шаблоны ООП):
  * *[Junior.February2014.GOF#17 №1_1](https://youtu.be/3sOIVgubyeQ)*
  * *[Junior.February2014.GOF#17 №1_2](https://youtu.be/Cp6mv2F4zPo)*
  * *[Junior.February2014.GOF#17 №1_3](https://youtu.be/BCfKV4FFMhQ)*
  * *[Junior.February2014.GOF#17 №1_4](https://youtu.be/v7FfJDYvDjQ)*
  * *[Junior.February2014.GOF#17 №1_5](https://youtu.be/BCfKV4FFMhQ)*
  * *[Junior.February2014.GOF#17 №1_6](https://youtu.be/v7FfJDYvDjQ)*
  * *[Junior.February2014.GOF#17 №1_7](https://youtu.be/mfaXG9eVIEA)*
  * *[Junior.February2014.GOF#17 №1_8](https://youtu.be/V5a0JC6DVgQ)*

* JSF(JavaServer Faces):
  * *[Junior.February2014.JSF#18 №1](https://youtube.com/playlist?list=PLoij6udfBncilwh6M-OUWSxef4ZP0PjdY)*
  * *[Junior.February2014.JSF#19 №2](https://youtube.com/playlist?list=PLoij6udfBnciRUejKExnW78IDLBt7ntwv)*
  * *[Junior.February2014.JSF#20 №3](https://youtube.com/playlist?list=PLoij6udfBncgtTP0V1Z5V6zJeoYmcTpG4)*

* WebSockets:
  * *[Junior.February2014.WebSockets #21 №1](https://youtube.com/playlist?list=PLoij6udfBncjXbiZ6pmX-chxQNjANR2Gh)*

* Apache Maven:
  * *[Junior.February2014.Maven#22 №1](https://youtube.com/playlist?list=PLoij6udfBnchZ36TWDdiQsPArx-ON-1GM)*

 *Log4J:
  * *[Junior.February2014.Log4J#23 №1](https://youtube.com/playlist?list=PLoij6udfBncj2KugaIbiLz9ggQzeAtA33)*

* JPA 2/Hibernate:
  * *[Junior.February2014.JPA2&Hibernate#24](https://youtube.com/playlist?list=PLoij6udfBnci05Oh7IRN-KU3PCjLeYtez)*
</details>

##


### Идем на работу

<details>
<summary> Закрываем дыры для собеса </summary>

* **Data Structure & Algorithms** *(уметь решать не сложные а.задачи, знать базовые алгоритмы)*
  - *[Link 1 V](https://youtu.be/_NhmGvYs8_g)* | *[Link 2 L](https://leetcode.com/explore/interview/card/top-interview-questions-easy/)*

* **ООП**
  - *[Link 1](https://youtu.be/4owUYYdcAOw)* | *[Link 2](https://youtu.be/YMTdEXpQTZQ)* | *[Link 3](https://youtu.be/BYu8gT0hGCQ)* | *[Link 4 G](https://youtube.com/playlist?list=PLoij6udfBncgtdSaq4nqVNtTqPeyh7rnV)* | *[Link 5 G](https://youtube.com/playlist?list=PLoij6udfBnciXh1_Itg-Hiw9EdGGzwYPE)* | *[Link 6 G](https://youtube.com/playlist?list=PLoij6udfBncjjuiZQNFx_b4A5Ygdn1YbS)* | *[Link 7 G](https://youtube.com/playlist?list=PLoij6udfBnch50JMDvipTQmAp-q4Pw6jG)* | *[Link 8 D](https://coursehunter.net/course/java-dlya-nachinayushchih-level-2?lesson=20)* | *[Link Y](https://youtu.be/Xg_DTzM6o6U)*

* **Generics** *(как применять, как оно работает)*
  - *[Link 1 G](https://youtu.be/Yymzcnt-Ars)* | *[Link 2 D](https://coursehunter.net/course/java-dlya-nachinayushchih-level-2?lesson=27)* | *[Link 3 D](https://coursehunter.net/course/java-dlya-nachinayushchih-level-2?lesson=28)* | *[Link 4 D](https://coursehunter.net/course/java-dlya-nachinayushchih-level-2?lesson=29)*

* **Object** *(знать методы)*
  - *[Link 1](https://youtu.be/DrQqZj5OIZc)* | *[Link 2](https://www.youtube.com/watch?v=Juav74bCtZ8)* | *[Link 3](https://www.youtube.com/watch?v=NQdwRwbPVCs)* | *[Link 4](https://youtu.be/B0bweMu3m5E)*

* **Collection Framework** *(**больше всего спрашивают**, надо очень подробно знать)*
  - *[Link 1](https://youtube.com/playlist?list=PL786bPIlqEjRvuYGGDMxy6YqzG-Hizvs8)* | *[Link 2](https://youtube.com/playlist?list=PLqj7-hRTFl_oDMBjI_EstsFcDAwt-Arhs)* | *[Link 3](https://youtu.be/xVfV8r_4GYI)* | *[Link 4 G](https://youtube.com/playlist?list=PLoij6udfBncjiXKA5ce0hi4b4DIvGymeo)* | *[Link 5 G](https://youtube.com/playlist?list=PLoij6udfBnciAPeXh5oOGBsQ2c8GlEFu0)* | *[Link 6 G](https://youtube.com/playlist?list=PLoij6udfBncgIlUdvGNtG2Jp7gXbDMx15)* | *[Link 7 G](https://youtube.com/playlist?list=PLoij6udfBncjAZTDf6Vx281R5Y9mnm93q)* | *[Link 8](https://youtu.be/JDh3DsJGGMU)*

* **Lamda** *(как работает, как устроено, черный ящик)*
  - *[Link 1](https://youtu.be/jHStUYP1NEg)* | *[Link 2](https://youtu.be/33pi0sIZNEU)* | *[Link 3](https://youtu.be/sWwkwcAugR0)* | *[Link 4](https://youtu.be/oUvx2Up-PkA)* | *[Link 5](https://youtu.be/GMzP5vIG9YU)*

* **Stream** *(как работает, методы)*
  - *[Link 1](https://youtu.be/IQVwwwSe4Ic)* | *[Link 2](https://youtu.be/aC0-KsuPG0I)* | *[Link 3](https://youtu.be/RzEiCguFZiY)*

* **Garbage Collector** *(gc(), finalize(), как он чистит мусор, как он работает, можно ли заставить работать)* 
  - *[Link 1](https://youtu.be/-ayMplONmkI)*

* **Multithreading / Concurrency** **_(базовые знания)_** *(как работает многопоточность, как создать тред, sleep, join, монитор, процесс гонки)*
  - *[Link 1](https://www.youtube.com/watch?v=VbLyaPPHtrE&list=PLw6SJ6q6-1YptavAy65knVOSBZ_y6YxmV&index=4&t=47s)* | *[Link 2](https://metanit.com/java/tutorial/8.5.php)*

* **Exception** *(**логирование**, ловля их, обработка в логи)*
  - *[Link 1](https://youtu.be/_ndfgwHtcXY)* | *[Link 2 D](https://coursehunter.net/course/java-dlya-nachinayushchih-level-2?lesson=47)* | *[Link 3](https://youtu.be/mLpMtc62530)* | *[Link 4 G](https://youtube.com/playlist?list=PLoij6udfBncilVuX_R0sBrESIlyfQWVjm)* | *[Link 5 G](https://youtube.com/playlist?list=PLoij6udfBnchbxh8ZAY-FPlmj97aCILTY)* | *[Link 6 G](https://youtube.com/playlist?list=PLoij6udfBncjLoxagaF5tGsDp-0XKMyhc)* | *[Link 7 G](https://youtube.com/playlist?list=PLoij6udfBnchR-Cc-RB4EUZokLrLlIuWQ)*

* **String, String Pool** *(как работает память, как он копирует, имутабельность, отличие от других стрингов)*
  - *[Link 1 Y](https://youtu.be/d_oou6CAz5U)* | *[Link 2 Y](https://youtu.be/1QP8y6-1fD0)*

* **SQL + JDBC** *(Иметь крепкую базу, понимать как работает на практике, как создавать коннект, пулл, уровни изоляции транзакций sql _isolation levels_, грязночтение, понимание что будет происходить на уровне бд если человек читает текущую запись, а другой изменяет данные, какие данные будут у них видны и тд)*
  - *[Link 1 SQL Y](https://youtube.com/playlist?list=PLtPJ9lKvJ4oh5SdmGVusIVDPcELrJ2bsT)* | *[Link 2 SQL C](https://coursehunter.net/course/sql)* | *[Link 3 JDBC C](https://coursehunter.net/course/jdbc?lesson=1)* | *[Link 4 G](https://youtube.com/playlist?list=PLoij6udfBncijyqGvf-YLN7hAL0S6nIrG)* | *[Link 5 G](https://youtube.com/playlist?list=PLoij6udfBncgGpXnVrDElGWoIhZMJTzr6)* | *[Link 6 G](https://youtube.com/playlist?list=PLoij6udfBncjQ6nd4jZvelDojOLkdITDq)* | *[Link 7 G](https://youtube.com/playlist?list=PLoij6udfBncgy-PDoYGvxyZ5L5GnqV_2R)* | *[Link 8 G](https://youtube.com/playlist?list=PLoij6udfBncjY0jx7t8Sc-V_qoNZM5gAu)* | *[Link 9 G](https://youtube.com/playlist?list=PLoij6udfBncigW-7YJku0LlQTDlMwmL33)* | *[Link 10 G](https://youtube.com/playlist?list=PLoij6udfBncj5beNvOYxtPhOkAPKVYnFz)*

* **Spring + Hibernate + WEB** *(базовые знания Spring framework, Hibernate, понимание как устроин web, что будет если ввести слово в поисковик и тд)*
  - *[ссылка на плейлист по спрингу](https://youtube.com/playlist?list=PLAma_mKffTOR5o0WNHnY0mTjKxnCgSXrZ)*

* **Maven** *(меньше всего спрашивают) (как он устроен и как им пользоватся)*
  - *[годный гайд от Немчинского](https://www.youtube.com/watch?v=IAbZVA4tK6M)*
  - *[гайд от dmdev](https://youtube.com/playlist?list=PLnh8EajVFTl5fusY9MRBEOoLjbv8Trms5)*

* **Unit & Integation testing** *(Хотя бы понимание как это делать и зачем. Создать мини метод, сделать на него тест, на истину/ложь и на ошибку)*

* **SOLID** *(как правильно программировать, понятия ООП, интерфейсы и тд.)*
  - *[Link 1 W](https://habr.com/ru/post/688530/)* | *[Link 2 G](https://youtube.com/playlist?list=PLoij6udfBncgRuXhcs1gsWhUlS_8ZOLbg)* | *[Link 3 W](http://butunclebob.com/ArticleS.UncleBob.PrinciplesOfOod)* | *[Link 4 Y](https://youtu.be/1MDiB2Ya--4)*

* **Паттерны проектирования** *(Знать и уметь реализовать базовые популярные паттерны).* 
  - *[Link 1 W](https://refactoring.guru/ru/design-patterns)* | *[Link 2 Y](https://youtube.com/playlist?list=PLlsMRoVt5sTPgGbinwOVnaF1mxNeLAD7P)* | *[Книга: Банда четырёх](https://t.me/dmytrii_bookshelf/231)*

* **Git** *(хватит базы, уметь использовать на практике)*
  - *[основы за час по ролику](https://youtu.be/dHlhCO56Pv0)* | *[GIT Полный курс](https://youtube.com/playlist?list=PLAma_mKffTOTIomJBmL9J42PP0l7riFUO)* | *[GIT Альтернативный курс](https://www.youtube.com/playlist?list=PLuY6eeDuleIOMB2R_Kky05ZfiAx2_pbAH)* | *[GIT Интерактивный тренажер](https://learngitbranching.js.org/?locale=ru_RU)* | *[документация от Жени](https://proselyte.net/tutorials/git/introduction/)*

### Подготовка к собесу
* **Структура собиседования**
  - *[Link 1 Y](https://youtu.be/UQnpwtdHiDs)* | *[Link 2 Y](https://youtu.be/vArj4XmtxvY)* | *[Link 3 Y](https://youtu.be/lq4TKfc-Ot4)* | *[Link 4 Y](https://youtu.be/oLZuCGuAnsM)*
* **Частые вопросы для Java Junior**
  - *[Link 1](https://github.com/enhorse/java-interview)* | *[Link 2 Y](https://youtube.com/playlist?list=PLlsMRoVt5sTMMCwd_gLaaZMkQhzVh9hLA)*
* **Составляем CV** 
  - *[Link 1](https://www.youtube.com/watch?v=UV3YSVBJxX0)* | *[Link 2](https://youtu.be/nEnuP2NmMA4)* | *[Link 4](https://youtu.be/jhnsjSCgtu0)* | *[Link 5](https://youtu.be/i1tJ8FfEXv4)* | *[Link 6 CV](https://www.hiration.com/)* | *[Link 7 CV](https://www.pdf2go.com/)*
</details>

##




### Дополнительный материал

- Разное:
  - *[roadmap backend](https://roadmap.sh/backend)*
  - *[Если у тебя все совсем плохо - лекции CS50](https://youtube.com/playlist?list=PLawfWYMUziZqyUL5QDLVbe3j5BKWj42E5)*
  - *[Краткие гайды по Java](https://proselyte.net/tutorials/)*
  - *[Книга "Архитектура Современных Веб-Приложений"](https://workshop.zhashkevych.com/courses-info/60a6692126276a15b8dcfa39)*
  - *[Телеграм канал с книгами](https://t.me/dmytrii_bookshelf)* , здесь можно по тегу it найти следующие книги:
    - Java. Полное руководство 10-е изданание. Г.Шилдт
    - Java. Эффективное программирование
    - Алгоритмы на Java
    - Грокаем алгоритмы
- Годные Youtube каналы:
  - *[letstCode](https://www.youtube.com/c/letsCodeDru)*
  - *[codelike](https://www.youtube.com/c/codelike)*
  - *[Eugene Suleimanov](https://www.youtube.com/c/EugeneSuleimanov)*
  - *[dmdev](https://www.youtube.com/c/dmdev/videos)*
  - *[Ulbi TV](https://www.youtube.com/c/UlbiTV)*
  - *[Аве Кодер](https://www.youtube.com/c/%D0%90%D0%B2%D0%B5%D0%9A%D0%BE%D0%B4%D0%B5%D1%80)*
  - *[S0ER TALKS](https://www.youtube.com/channel/UCcNotjFXtUZ6bTAWk1KpOWg)*
  - *[S0ER](https://www.youtube.com/c/S0ERDEVS)*
  - *[Senior Software Vlogger](https://www.youtube.com/c/SeniorSoftwareVlogger)*
  - *[Sergey Nemchinskiy](https://www.youtube.com/c/SergeyNemchinskiy)*
  - *[ExtremeCode](https://www.youtube.com/c/ExtremeCode)*
- Статьи:
  - *[Зачем мне Java: неудобные вопросы о популярном языке и ответы на них](https://tproger.ru/articles/zachem-mne-java-voprosy-i-otvety/)*




##
[Так же вы можете поддержать автора чеканной монетой.](https://send.monobank.ua/jar/AGN7gXSmuT)

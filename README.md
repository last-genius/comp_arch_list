## ПОК

1. Перша книга, як б я настійливо радив: 
[David Harris, Sarah Harris «Digital Design and Computer Architecture»](books/Digital%20Design%20and%20Computer%20Architecture.%20ARM%20Edition%20by%20Sarah%20Harris,%20David%20Harris.pdf). 
Краще англійською і варіант ARM(*), але можна як MIPS-варіант, так і російський. 
Легко знаходиться в магазинах чи в піратів, 
[російський варіант безкоштовний.](http://microelectronica.pro/wp-content/uploads/books/digital-design-and-computer-architecture-russian-translation.pdf)
 
2. Книга Таненбаума: ["Modern Operating Systems"](books/Modern%20Operating%20Systems%20by%20Andrew%20S.%20Tanenbaum,%20Herbert%20Bos.pdf),
глави: 1, 2, 3 і 7 -- обов'язково, 4, 5 бажано. Решта можна, але ми з їх матеріалом 
потім працюватимемо. [Детальніше, що це за глави і навіщо вам вони.](http://indrekis2.blogspot.com/2016/06/blog-post.html)
 
3. [Підручник по С. Класична книга Кернігана і Річчі](books/The%20C%20Programming%20Language%20by%20Brian%20W.%20Kernighan,%20Dennis%20M.%20Ritchie.pdf) 
підійде. (Вона справді проста і доступна -- вчити С++ по довіднику Страуструпа я не радив би :=)

4. Note: I've had to comply with a DMCA takedown notice for this book. It now links to the
author's uncorrected draft for the book published for free, not the final publisher's PDF.
["Linkers and Loaders"](https://www.iecc.com/linker/)
[Amazon-сторінка](https://www.amazon.com/Linkers-Kaufmann-Software-Engineering-Programming/dp/1558604960)
Вона відносно складна для вас, але ми повинні будемо ці ідеї засвоїти так чи по іншому.

5. Кому Харріс і Харріс ну зовсім не піде, можна 
[David Patterson, John Hennessy «Computer Organization and Design: The Hardware/Software Interface»](books/Computer%20Organization%20and%20Design%20The%20Hardware%20Software%20Interface%20ARM%20Edition%20by%20David%20A.%20Patterson,%20John%20L.%20Hennessy.pdf)
-- теж дуже достойна, і на АКС буде потрібною. Якщо зовсім-зовсім важко, як найлайтовіший варіант: 
[Andrew S. Tanenbaum, Todd Austin «Structured computer organization»](books/Structured%20Computer%20Organization%20by%20Andrew%20S.%20Tanenbaum,%20%20Todd%20Austin.pdf),
 глави 1-4 (може ще 5), але єдина вартісна глава там 4-та, решта -- таке...

6. Для частини роботи із дискретними мікросхемами, яка буде в кінці, на додачу до Харріс і Харріс, 
дуже хороша книжка: [Roger Tokheim, «Digital Electronics: Principles and Applications»](books/Digital%20Electronics%20Principles%20and%20Applications%20by%20Roger%20L.%20Tokheim.pdf)
 (є російський переклад). Можна і старе видання, 1988 -- ті речі не змінилися.

7. Для практичних -- підручник по сучасному CMake ("Professional CMake: A practical guide")
Ми будемо на практичних дуже широко ним користуватися всі три курси. 

8. Embedded частина -- в коментах, бо багато.

9. Старі списки літератури -- буду сильно редагувати: 
[раз](http://indrekis2.blogspot.com/2017/10/blog-post_39.html), 
[два](http://indrekis2.blogspot.com/2017/10/blog-post_11.html), 
[три](https://dou.ua/lenta/articles/dou-books-farenyuk/).

_(*) ARM i MIPS -- це так-звані ISA, грубо кажучи, системи команд процесорів. В телефонах і наших ембеддед платах -- ARM. Десктопники і ноути наші -- всі зараз x86. Про MIPS дуже багато книжок (ті ж Хеннесі і Паттерсон -- автори MIPS), але на зустріти її важко -- в роутерах та іншому спецобладнанні буває._

## АКС 

Мінімальний список необхідних книг та статей

1. [Andrew S. Tanenbaum and Herbert Bos, "Modern Operating Systems"](books/Modern%20Operating%20Systems%20by%20Andrew%20S.%20Tanenbaum,%20Herbert%20Bos.pdf) -- вона ближча до нашого наступного курсу, ОС, але для АКС необхідними є глави 1, 2, 3, 6, 8. (4, 5 і 7 -- бажані, решта -- можуть почекати до осені).

2. David Patterson, John Hennessy [«Computer Organization and Design: The Hardware/Software Interface»](books/Computer%20Organization%20and%20Design%20The%20Hardware%20Software%20Interface%20ARM%20Edition%20by%20David%20A.%20Patterson,%20John%20L.%20Hennessy.pdf)
та ["Computer Architecture A Quantitative Approach"](books/Computer%20Architecture,%20Sixth%20Edition%20A%20Quantitative%20Approach.pdf)
цих же авторів. 

3. Brian Goetz, Tim Peierls, Joshua Bloch, Joseph Bowbeer, David Holmes, Doug Lea, ["Java Concurrency in Practice"](books/Java%20Concurrency%20in%20Practice.pdf). Книжка вже трішки давня, але все ще актуальна -- вона не містить найновіших "фішок" Java, але детально описує принципи абстракцій середнього і низького рівня, які не змінилися.
    Щодо архітектури пам'яті: "What every programmer should know about memory" by Ulrich Drepper.
    Floating-point, критична тема для AI, ML, геймдеву, інших інженерних чи наукових обчислень: "What Every Computer Scientist Should Know About Floating-Point Arithmetic" (pdf). Це мінімальна стаття! Хто хоче більшого -- тут.


Вище -- це, так би мовити. книги для оцінок D-C. Більш просунутими, для A-B є:

1. John Hennessy, David Patterson ["Computer Architecture : A Quantitative Approach"](books/Computer%20Architecture,%20Sixth%20Edition%20A%20Quantitative%20Approach.pdf)

2. David Harris, Sarah Harris [«Digital Design and Computer Architecture»](books/Digital%20Design%20and%20Computer%20Architecture.%20ARM%20Edition%20by%20Sarah%20Harris,%20David%20Harris.pdf). 

3. Anthony Williams ["C++ Concurrency in Action: Practical Multithreading"](books/C++%20Concurrency%20in%20Action.pdf)

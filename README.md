# Моё портфолио
### Первый опыт знакомства с Unity - маленькая игра-платформер
---

> [Ссылка на весь репрозиторий](https://github.com/Xeniiia/Game)  
> [Ссылка только на скрипты](https://github.com/Xeniiia/Game/tree/main/Assets/Scripts)


Это 2D платформер, все спрайты которого отрисованы мной. Скрипты на языке С#.
Для главного персонажа игры были реализованы такие механики, как:

- [x] Передвижение в стороны
- [x] Прыжок
- [x] Уcкорение (дэш), работающее как на поверхности, так и во время прыжка
- [x] Прыжки от стен
- [x] А также плохой код ;)
    
Кроме того созданы меню, несколько уровней и меню паузы, а так же добавлена музыка и звуки.
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/79145926/136772025-3ce5e030-07e4-485e-adf6-5544ebc2bea8.gif)

---

### Pacman на Unity, клиент-сервер, сериализация данных

---

> [Ссылка на репрозиторий](https://github.com/Xeniiia/UnityGame-Pacman/tree/main)  
> [Ссылка только на скрипты (клиент)](https://github.com/Xeniiia/UnityGame-Pacman/tree/main/UnityClient/Assets/Scripts)

Простая игра Pacman, логика которой обрабатывается сервером.  
Информация об уровне находится в txt файле, сервер ее обрабатывает и отправляет клиенту, который визуализирует. Логика перемещений игрока также обрабатывается сервером и только визуализируется клиентом. Сетевое взаимодействие реализовано через сокеты и асиннхронные коллбэки. Данные сериализуются с помощью **Protocol Buffers**.

![безымянный jfg5E](https://user-images.githubusercontent.com/79145926/136765732-4990cb65-bdf7-4a77-bc2e-78991ff8ef0b.png)



---

### Клиент-серверный многопользовательский чат, С++

---

> [Ссылка на репрозиторий](https://github.com/Xeniiia/Client-server-chat)

При работе над данным проектом я впервые столкнулась с клиент-серверной архитектурой. Создать передачу данных от одного клиента серверу и обратно не составило труда, но вот реализовать это же для нескольких клиентов было для меня труднее. В итоге **я использовала потоки**, создавая их для каждого нового подключившегося клиента.



---

### Изучение ООП на практике, Java

---

> [Ссылка на репрозиторий](https://github.com/Xeniiia/Some-java)

Это набор разрозненных решенных задач, в которых я осваивала не только синтаксис языка Java, но и наследование, полиморфизм и инкапсуляцию. Создавала отдельные классы и их экземпляры, впервые разделяла проект на несколько разных файлов со своим кодом. Узнала о сеттерах, геттерах, полях и методах классов.  
Кроме того, изучила тему дженериков и вызова исключений.



---

### HTML и CSS (и немного js, php и mysql)

---

> [Ссылка на репрозиторий Формы регистрации](https://github.com/Xeniiia/Registration-form)  
> [Ссылка на репрозиторий Простого калькулятора](https://github.com/Xeniiia/A-simple-calculator)  
> [Ссылка на репрозиторий Простого лэндинга](https://github.com/Xeniiia/Simple-landing-page)


Эти проекты - мое первое знакомство с HTML, CSS, PHP и запросами MySQL. В форме регистрации мною реализована пара простых страничек с формой - регистрация и вход. В проекте калькулятора есть немного js, чтобы проводить какие-то операции над значениями в поле ввода. В посадочной странице также используется JavaScript (чтобы отправка формы была невозожна, пока не стоит галочка в чекбоксе) и PHP. Кроме того, в этом проекте я использовала базу данных - при регистрации введенные данные отправляются в базу, а затем могут быть выведены в виде таблицы.

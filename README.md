# Моё портфолио
### Игра на Unity "Тир"

---

> [Ссылка на весь репрозиторий](https://github.com/Xeniiia/Shooting-gallery-Game)  
> [Ссылка только на скрипты](https://github.com/Xeniiia/Shooting-gallery-Game/tree/main/Assets/Scripts)


Основной задачей этого проекта было изучить принципы SOLID, сделать хорошую архитектуру.

![image](https://user-images.githubusercontent.com/79145926/149613368-6b61bf82-3e69-412d-8eb5-a9fe6ef1518e.png)



---

### Самый первый опыт знакомства с Unity - маленькая игра-платформер

---

> [Ссылка на весь репрозиторий](https://github.com/Xeniiia/Game)  
> [Ссылка только на скрипты](https://github.com/Xeniiia/Game/tree/main/Assets/Scripts)


Это 2D платформер, спрайты - мои. Скрипты на С#.
Пример плохого кода ;)
![ezgif com-gif-maker (1)](https://user-images.githubusercontent.com/79145926/136772025-3ce5e030-07e4-485e-adf6-5544ebc2bea8.gif)

---

### Pacman на Unity, клиент-сервер, сериализация данных

---

> [Ссылка на репрозиторий](https://github.com/Xeniiia/UnityGame-Pacman/tree/main)  
> [Ссылка только на скрипты (клиент)](https://github.com/Xeniiia/UnityGame-Pacman/tree/main/UnityClient/Assets/Scripts)

Простая игра Pacman, логика которой обрабатывается сервером.  
Информация об уровне находится в txt файле, сервер ее обрабатывает и отправляет клиенту, который визуализирует. Логика перемещений игрока также обрабатывается сервером и только визуализируется клиентом. Сетевое взаимодействие реализовано через сокеты и асиннхронные коллбэки. Данные сериализуются с помощью **Protocol Buffers**.
Какой-либо архитектуры здесь не существует :)

![безымянный jfg5E](https://user-images.githubusercontent.com/79145926/136765732-4990cb65-bdf7-4a77-bc2e-78991ff8ef0b.png)

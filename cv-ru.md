# Илья Попов
## Frontend-разработчик

***

### Контактная информация:
**E-mail:** popovemail1990@gmail.com

**Telegram:** https://t.me/poposhka1990

***

### Сопроводительная информация:
На протяжении последних 7 лет я работаю начальником отдела по оформлению документов иностранным студентам.
У меня всегда был интерес к технологиям и гаджетам. 2 года назад у меня появилась идея реализации нового сервиса для иностранных студентов.   
Для реализации этого проекта мне понадобилось повысить квалификацию и пройти курсы по основам Frontend-разработки.
В этот году я начал техническую часть и разработал вебсайт "Помощник иностранного студента".
Более того, погружение в процесс разработки так увлек меня, что я продолжил свое обучение и претендую на позицию Frontend-разработчика.

***

### Мои проекты:
1. [Помощник иностранного студента](https://poposhka1990.github.io/international-student-assistant-js/)
2. [Resource Coffee House](https://rolling-scopes-school.github.io/poposhka1990-JSFE2023Q4/)
3. [Countries of the World](https://poposhka1990.github.io/4p22-final-project-ilya-popov/)

***

### Навыки:
1. HTML, CSS, JavaScript
2. React
3. Figma (developer mode)
4. Git, GitHub, npm
5. VSCode, WebStorm

***

### Пример кода:
**Функция для получения следующего вопроса из теста по миграционному законодательству:**
```javascript
function getNextQuestion () {
    if (questionNumber <= QUESTIONS.length - 1) {
        questionNumberLabel.textContent = `${questionNumber + 1} из ${QUESTIONS.length} вопросов`
        question.textContent = QUESTIONS[questionNumber].question
        commentary.textContent = ''

        QUESTIONS[questionNumber].options.forEach((option, index) => {
            optionLabels[index].textContent = option
        })
    } else {
        result.innerHTML = `<p>У вас ${correctAnswersCount} правильных ответа из ${QUESTIONS.length} вопросов</p>`
    }
}
```

***

### Образование:
* Высшее (2018 - магистр международных отношений)
* IT курсы:
    * 2021 - iOS Development Bootcamp
    * 2022 - Основы Frontend-разработки (Университет ИнноПолис)
    * 2023 - RS School "JavaScript/Front-end course. Stage 1" (в процессе)

***

### Languages:
* English (Advanced C1)

***

### Хобби:
* Лыжный спорт, бег, велоспорт
* Пишу indie-pop музыку

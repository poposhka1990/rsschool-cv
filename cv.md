# Ilya Popov
## Junior Frontend Developer

***

### Contact information:
**E-mail:** popovemail1990@gmail.com

**Telegram:** https://t.me/poposhka1990

***

### Brief introduction:
Over 7 years I've been helping international students with documents, such as visa and registration. 
I have interest in technologies and keep acquiring new skills.   
Recently I started making a web app where my company can publish all the necessary information on documents for students.
The web app allows to computerize lots of information on the topic. 
Moreover, it gives me the opportunity to gain necessary skills for Frontend Developer position. 

***

### Skills:
1. HTML, CSS, JavaScript
2. Basics of React
3. Git, GitHub, npm
4. VSCode, WebStorm

***

### Code Example:
**Function for getting a new question that I use in a test for migration law knowledge:**
*It checks the number of a question, shows the number in a label and the question itself on the screen. 
If it is the last question, it shows the results.*
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

### My pet-projects:
1. [Динамика - Блог для спортсменов](https://dinamika-blog.netlify.app/)
2. [Помощник иностранного студента](https://poposhka1990.github.io/international-student-assistant-js/)
3. [Изучаем английский по книгам Гарри Поттера](https://harrypotter-english.netlify.app/)
4. [Конвертер изображений в текст](https://poposhka1990.github.io/scan-to-text-converter/)
5. [Resource Coffee House](https://rolling-scopes-school.github.io/poposhka1990-JSFE2023Q4/)
6. [Countries of the World](https://poposhka1990.github.io/4p22-final-project-ilya-popov/)
7. [Анимированное меню](https://poposhka1990.github.io/animated-navbar/)

***

### Education and courses:
* Higher (2018 - Master degree of International Relations)
* IT courses:
  * 2021 - iOS Development Bootcamp
  * 2022 - Basics of Frontend Development course
  * 2023 - RS School "JavaScript/Front-end course. Stage 1" (in progress)

***

### Languages:
* Russian (Native)
* English (Upper-Intermediate)
* French (Basic)
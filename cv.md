# Name
Aleksandr Hramyka

---


# Contacts
Location: Belarus - Minsk , [Telegram](https://t.me/master_thunder) , E-mail: gromvolk97@gmail.com

---

# About me

I want to study programming. It is interesting. There is always movement forward.
You do not stand still. It's better than my job. At my job, I die physically) And mb i can fast learner )

---


# Skill


I know a little JS. Made a mini-game according to the template. I understand the written code.
HTML and CSS i know too. First time using GitHub.


---

# Code

This my game
```
let clicks = 1;
let timeOut = 5000;

const display = document.getElementById('display');
const button = document.getElementById('button');
const counter = document.getElementById('counter');

button.onclick = start ;

function start() {
button.onclick = () => counter.innerHTML = ++clicks ;

display.innerHTML = formatTime(timeOut);

let startTime = Date.now() ;


const interval = setInterval(() => {

let delta = Date.now() - startTime ;

display.innerHTML = formatTime(timeOut - delta) + ' sec';

},100)



const finishTime = setTimeout(() => {

display.innerHTML = 'Game Over' ;

clearInterval(interval);
clearTimeout(finishTime);
button.onclick = 0;
counter.innerHTML = 'Вы собрали ' + clicks + ' очков'
}, timeOut)


}

function formatTime(ms) {
return Number.parseFloat(ms / 1000).toFixed(1);
}



const repeat = document.getElementById('repeat');
repeat.onclick = again ;
function again() {
button.onclick = start;
counter.innerHTML = 0;
clicks = 1;
display.innerHTML = 5 + ' sec'
}
```

---



# Practice

Practicing with myself

---

# Education

My education is not related to programming

---

# English

I'll tell truth - my English is bad.
But I lived in India for 2 months and
coped with everything

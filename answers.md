1.
aside = document.querySelector('aside.highlight');
image = aside.querySelector('img'):
image.src = https://placebear.com/200/300;

1.
portfolio = document.querySelector('div.portfolio-image');
image2 = portfolio.querySelector('img');
image.src = 'https://placebear.com/g/200/300';

2.
heading = document.querySelector('h1.highlight')
heading.innerText = 'nicolas'

3.
heading = document.getElementById('employment')
heading.querySelector('h3')
title = heading.querySelector('h3')
title.innerText = "beautiful"

4.
body = document.querySelector('body')
body.style.color = "green";

5.
elements  = document.querySelectorAll('.highlight')
for (var i=0; i < elements.length; i++){
    elements[i].color = "red"
}

6.
h1 = document.querySelector('h1')
h1.style.fontFamily = "monospace"

7.
buttons = document.querySelectorAll("a.action-icon-bg")
buttons[0].style.backgroundColor = "blue"

8.
contactform = document.querySelector(".contact-info")
contactform.placeholder = "identify yourself"

9.
message = document.querySelector("textarea")
message.placeholder = "state your buisness"

10.
contactform = document.querySelector(".contact-info")
contactform.value = "Your nemesis"

11.
contactform = document.getElementById("email")
contactform.value = "koalathebear@gmail.com"

12.
submit = document.getElementById("submit")
submit.value = "En Garde!"

13.
submit = document.getElementById("submit")
submit.disabled = true

14.
aside = document.querySelector(".highlight")
bio = document.querySelector(".bio-info")
aside.removeChild(bio)

part 2

1.1
timetravel = document.querySelectorAll(".bar-title")
div = timetravel[2].parentElement
toremove = div.parentElement
toremove.remove()

2.1
pika = document.getElementById("right-image")
dupNode = pika.cloneNode()
port = document.querySelector(".portfolio-container")
port.appendChild(dupNode)

2.2
for (var i=0; i < 10; i++){
  dupNode = pika.cloneNode(".portfolio-container")
  port.appendChild(dupNode)
}

2.3
var listItem = document.createElement('li')
var leftSpan = document.createElement('span')
var lastUpdated = document.createTextNode('Page last updated on')
leftSpan.appendChild(lastUpdated)
var leftSpan = document.createElement('span')
leftSpan.appendChild(lastUpdated)
listItem.appendChild(leftSpan)
ul = document.querySelector(".bio-info")
ul.appendChild(listItem)

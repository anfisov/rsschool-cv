# Nikita Anfisov - my CV
* **Contacts:** co_0kie (telegram)
* Non stop improve myself. I haven't any serious experience at programming, but it is interesting for me. I have some tiny experience at game dev using c# (with dictionary and forums). I'm very diligent at anything, can't stop until i found a solution.
* Навыки (языки программирования, фреймворки, методологии, системы контроля версий и инструменты разработки, которыми вы владеете)
A little knowledge of C#, java, python, HTML.
* From codewars:
link at task [here](https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1)
my solution:
***
``` javascript
function duplicateCount(text){
const newText = text.toLowerCase()
const array = newText.split('')

let newArray =[]
for (i = 0; i < array.length; i++)
{
    let a = array[i]
    if (newArray[a] != undefined)
    {
        ++newArray[a]
    }
    else
    {
        newArray[a] = 1
    }
}

console.log(newArray)

let counter = 0
for (let key in newArray)
{
    if (newArray[key] > 1)
    {
        counter += 1
    }
}
return counter
}
```
***
* Опыт работы. Junior Dev может указать пройденные курсы и тренинги, перечислить учебные проекты, или проекты, выполненные на фрилансе с указанием использованных навыков и ссылками на исходный код.
* Образование (включая курсы, семинары, лекции, онлайн-обучение)
Английский язык (уровень английского языка, если была языковая практика, расскажите о ней)
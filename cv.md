# Nikita Anfisov - my CV
* **Contacts:** co_0kie (telegram)
* Non stop improve myself. I haven't any serious experience at programming, but it is interesting for me. I have some tiny experience at game dev using c# (with dictionary and forums). I'm very diligent at anything, can't stop until i found a solution.
* A little knowledge of C#, java, python, HTML.
* From codewars:
link on task [here](https://www.codewars.com/kata/54bf1c2cd5b56cc47f0007a1).
My solution:

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

* Have not programming work experience 
* Bachelor, Institute for Radio-Electronics and Telecommunications
* English pre-intermediate
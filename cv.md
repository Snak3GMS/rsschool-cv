Vladimir Shkarubov
----------
Contacts: [vk](https://vk.com/shkarubovvova)

Since 2018 I have been interested in web development, I want to become a good front-end developer. Very easy to learn, understanding 95% of the material from the 1st try. I have always liked the topic of IT, so I love to study it.

**Skills**:HTML, CSS, SASS, LESS, JavaScript, ES6, algorithms.

Sample code from the latest [TODOLIST](https://snak3gms.github.io/) project:
--------
// Функция удаления элемента
```
function deleteElement() {
  if (list.innerHTML == '') {
        list.innerHTML = `<div class="listnull">Список пуст...</div>`;
    }
    document.querySelectorAll('.item-delete').forEach((btn, i) => {
        btn.addEventListener('click', () => {
        toDoList.splice(i, 1);
        getDoList();
        });
    }); 
}
```
// Формирование списка задач на странице из созданного массива объектов
```
function getDoList() {
    list.innerHTML='';
    toDoList.forEach((element) => {
        const elementList = document.createElement('div');
        elementList.classList.add('list__item');
        elementList.innerHTML = `<div class="wrapper"><div class="item-title">${element.name}</div><a class="item-delete"><div></div><div></div></a></div>`;
        if (element.descr.length > 0) { 
            elementList.innerHTML += `<div class="descr_todo">${element.descr}</div>`
        }
        list.append(elementList);
    });
    deleteElement();    
    localStorage.setItem('1', JSON.stringify(toDoList));
}
```

--------
**Passed courses** on JS and on creating web pages

**Secondary vocational education**, online courses by Ivan Petrichenko, self-education from the books: "You don't know JS" and "learnJavaScript"

I can read the documentation with a dictionary. English level **A2**(pre-intermediate)

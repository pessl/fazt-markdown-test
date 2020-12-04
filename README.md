<!-- HEADINGS -->
# my title h1
## my title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- italic-->
this is an *italic* text

<!-- strong-->
this is an **strong** text

<!-- strikethrough -->
este es un ~~texto~~ tachado

<!-- UL -->
* apple
    * apple 2
* orange
    * orange 2
* etc

1. apple
    1. apple 2
2. orange
    1. orange 2
3. etc

<!-- UL -->
[faztweb.com](https://www.faztweb.com)

[faztweb.com](https://www.faztweb.com "Custom Title")

<!-- Poner una cita -->
> this is a quote

<!-- Hacer separaciones -->
---
___

<!-- Poner linea de codigo o bloque de codigo -->
`console.log('Hello World")`

```
const mongoose = require('mongoose');

mongoose.set('userFindAndModify', false);
mongoose. connect('mongodb://localhost/node-notes-db', {
    useCreateIndex: true,
    useNewUrlParser: true
})
    .then(db => console.log('DB is connected'))
    .catch(err => console.error(err));
```

```javascript
const mongoose = require('mongoose');

mongoose.set('userFindAndModify', false);
mongoose. connect('mongodb://localhost/node-notes-db', {
    useCreateIndex: true,
    useNewUrlParser: true
})
    .then(db => console.log('DB is connected'))
    .catch(err => console.error(err));
```

```python
print("Hello World")
```

```html
<h1>Hello World</h1>
```

<!-- Tablas -->
|Tables         |Are          | Cool  |
|-------------- |:-----------:| -----:|
|col 3 is       |right-aligned| $.1600|
|col 2 is       |centered     |   $.12|
|zebra stripes  |are neat     |    $.1|

<!-- Imagen -->
![visual studio code logo](https://upload.wikimedia.org/wikipedia/commons/thumb/9/9a/Visual_Studio_Code_1.35_icon.svg/1200px-Visual_Studio_Code_1.35_icon.svg.png)

![visual studio code logo](logo.png "vscode logo")

<!-- GITHUB MARKDOWN-->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4

<!-- GITHUB MARKDOWN -->
* [x] Task 1
* [ ] Task 2
* [ ] Task 3
* [x] Task 4

<!-- Emoji -->
:smiley: :+1:

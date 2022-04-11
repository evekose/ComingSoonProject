# Coming Soon README
___

![Coming Soon Logo](https://image.ibb.co/f4vhyS/logo.png)

See leht on loodud näitamaks, kui palju on päevi, tunde, minuteid ja sekundeid kuupäevani 01.01.2023.

**Kalkulatsioon** on tehtud järgnevate valemite abil:
```
const days = Math.floor(distance / (1000 * 60 * 60 * 24));
    const hours = Math.floor((distance % (1000 * 60 * 60 * 24)) / (1000 * 60 * 60));
    const mins = Math.floor((distance % (1000 * 60 * 60)) / (1000 * 60));
    const seconds = Math.floor((distance % (1000 * 60)) / 1000);
```

**Kuvab tulemuse**:
```
countdown.innerHTML = `
        <div>${days}<span>Days</span></div>
        <div>${hours}<span>Hours</span></div>
        <div>${mins}<span>Minutes</span></div>
        <div>${seconds}<span>Seconds</span></div>
    `;
```


<!-- Headings -->
# Heading 1
## Heading 2
### Heading 3
##### Heading 4
##### Heading 5
###### Heading 6

<!-- Italics -->
*This text* is italic

_This text_ is italic

<!-- Strong -->
**This text** is strong

__This text__ is strong

<!-- Strikethrough -->
~~This text~~ is strikethrough

<!-- Horizontal Rule -->

---

___

<!-- Blockquote -->

> This is a quote

<!-- Links -->
[Traversy media](http://www.traversymedia.com)

[Traversy media](http://www.traversymedia.com "Traversy Media")

<!-- UL -->
* Item 1
* Item 2
* Item 3
    * Nested Item 1
    * Nested Item 2

<!-- OL -->
1. Item 1
1. Item 2
1. Item 3

<!-- Inline Code Block -->
`<p>This is a paragraph</p>`

<!-- Images -->
![Markdown Logo](https://markdown-here.com/img/icon256.png)

<!-- Github Markdown -->

<!-- Code Blocks -->
```bash
npm install

npm start
```

```javascript
    function add(num1, num2) {
     return num1 + num2;
 }
```

```python
    def add(num1, num2):
        return num1 + num2
```

<!-- Tables -->
| Name     | Email          |
| -------- | -------------- |
| John Doe | john@gmail.com |
| Jane Doe | jane@gmail.com |

<!-- Task Lists -->
* [x] Task 1
* [x] Task 2
* [ ] Task 3

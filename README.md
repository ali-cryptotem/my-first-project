# Heading 1
## Heading 2
### Heading 3
#### Heading 4
##### Heading 5
###### Heading 6

---

<h1 id="head1">For testing link-to-pages (head1)</h1>

---

# Menu


### Unordered menu
- Menu1
- Menu2
    - sub-menu1
    - sub-menu2

### Ordered menu

1. Menu1
1. Menu1

    2. sub-menu1
    2. sub-menu2

---
# Highlights

`this code is python`

**this text is bold**

*this text is italic*

***this text is italic and bold***

---

```diff
this is a code

- this code has removed

+ this code has added
```

```Js
console.log("hello")
```

```py
print("Hello world!")
```

---

> Hello, I am Alireza
>> I am python developer

---

# Links and images

we can use html code to create a link

>part 1:
>> [text](address)
#
[var-link-name]: (https://finca.ir)
> part 2: (Using var-link)
>> [text][var-link-name]

images:

we can use html code to add a link

[Picture](<images (1).jpg>)

![Picture](<images (1).jpg>)

[![Picture](<images (1).jpg>)](https://finca.ir)

---

# link on MD page's different parts:

- [click here to view head 1](#head1)
- <a href="#head1">click here to view head 1</a>

# Table

| col 1 | col 1 | col 3 |
|--|--|--|
| col 1 - Row 1 | col 2 - Row 1 | col 3 - Row 1 |
| col 1 - Row 2 | col 2 - Row 2 | col 3 - Row 2 |
| col 1 - Row 3 | col 2 - Row 3 | col 3 - Row 3 |

---

# Details

`This part can be use for Table of content`

<details>
    <summary>Menu item</summary>
    <ul>
        <li>item1</li>
        <li>item1</li>
        <li>item1</li>
        <li><details>
            <summary>item4</summary>
            <ul>
            <li>sub item1</li>
            <li>sub item2</li>
            </ul>
            </details></li>
    </ul>
    </details>
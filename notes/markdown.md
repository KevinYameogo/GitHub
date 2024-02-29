# Markdown

## Synthax You need to know

### <mark style="background:lightgreen">Definition<mark>

Markdown is an easy-to-read, easy-to-write **language for formating simple text**.

### <mark style="background:lightgreen">Paragraphs<mark>

-Seperate new paragraphs from old ones by **one empty** line to avoid issues.

-Add _two spaces_ at the end of previous line : text will be in the same paragraph but on a new line.

Example:  
provided text  
Here

### <mark style="background:lightgreen">Headings<mark>

-Heading: one pound(#) symbol followed by some text  
Example : #heading

-For any additional pound you add your headings are going to get smaller.

-Smallest heading is 6.

### <mark style="background:lightgreen">Bold / Italic<mark>

-To make a text **bold** surround it by two asteriks (at the front and end).

-or double underscore.

-Use one askeriks to _italicize_ a text (at the front and end).

-Surround text with three asteriks to make it both **bold** and _italic_

Example : **_italics_**

### <mark style="background:lightgreen">Cross off / Highlight<mark>

-use double tidle(~) to cross off a text

Example : ~~cross off~~

-Highlight a text using double equal signs(github does not support this)

Example : ==Highlight==

-or use html < mark > < /mark > <mark>element</mark>

### <mark style="background:lightgreen">Superscript subscript<mark>

-Use this symbol for superscript : ^ (github does not support this)

-Use this symbol for subscript : ~(single tidle) (github does not support this)

-or use html <sub>sub</sub> and <sup>sup</sup> tag

### <mark style="background:lightgreen">Emojis<mark>

-Copy emoji and paste it to your actual code ⌖

-Using colons = :smile: (github does not support this)

### <mark style="background:lightgreen">Code blocks<mark>

-Use one back ticks:

```java
int age = 25
```

-Across multiple line: use three back ticks.

-You can add the language depending on the editor

```js
const a = 20;
let y = 2;
```

### <mark style="background:lightgreen">Links<mark>

-Put text for the link inside a square brackets [] and add a paranthesis () after that and inside of it put a link.

Example: [google](https://google.com)

-You can also wrap it inside angle brackets (<>)
<https://google.com>

### <mark style="background:lightgreen">Images<mark>

-![]() Put **_text for the link_** inside a square brackets[] and **_put a link inside the paranthesis_** ().

-In front of square brackets **_add an exclamation mark_**.

![cat image](image2-1.jpeg)

### <mark style="background:lightgreen">BlockQuotes<mark>

-Use **_angle brackets_** infront of the text

> all
>
> > I
> >
> > > Wanted
> > >
> > > > Was
> > > >
> > > > > This

### <mark style="background:lightgreen">Horizontal rule<mark>

-Use three dashes(---),three stars(\*\*\*), or three underscores(\_\_\_) on an empty line.

Monday

---

2024.23.12

### <mark style="background:lightgreen">Lists<mark>

-Write a **_number and a dot_** followed whatever you want(make sure there is a space between the number and text).

-Does not matter what the numbers are(they can be all 1).

-For **undorder list** you can use an asteriks in front, dashes or + symbol.

-If you want to **_nest_** them inside each other you can use 4 spaces.

- red
- pink
  - blue
  - green

### <mark style="background:lightgreen">Tables<mark>

-Every row should start and end with a **_pipe symbol_**(|);

-In **_between each column_** add a pipe symbol.

-In **between first and other rows** you should have a _divider_(indicates the first row is the header and the other are normal rows).

-**Divider** should be at least **_three dashes_**.

-_To change alignment of colums_:

> to align on the right add a colon(:) on the right of the divider

> Left will align left

> on both side it will align center

| Col 1 | col 2  |
| :---: | :----: |
| table | table2 |
| score | score2 |
| price | price2 |

### <mark style="background:lightgreen">Checklists<mark>

-Use **_square brackets and add a space inside of it_** to represent it is an unchecked checkbox.

-Before square brackets you should have **_a dash followed by a space_**.

- [x] checkbox
- [ ] unchecked box

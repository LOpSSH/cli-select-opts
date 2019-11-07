
A select options utility for the terminal

# Usage

* Download and cd into the directory.
* Run `node test`.

# Examples

```js
const { Select } = require("./")

const jsFrameworkSel = new Select({
    question: "Which of these is your fav JS framework?",
    options: ["Angular", "React", "Vue", "Svelte"],
    answers: ["angular", "react", "vue", "svelte"],
    pointer: ">",
    color: "magenta"
})

jsFrameworkSel.start()
```

```js
const stylingTypeSel = new Select({
    question: "Which styling do you want?",
    options: ["CSS", "SASS", "SCSS", "LESS"],
    answers: ["css", "sass", "scss", "less"],
    pointer: "-",
    color: 'red'
})

stylingTypeSel.start()
```


# JavaScript — SuperSimpleDev Course Work

My code from working through [SuperSimpleDev's JavaScript full course](https://www.youtube.com/@SuperSimpleDev), lessons 4–12. Each file is prefixed with its lesson number, so you can watch the same projects grow from inline `onclick` snippets into separate HTML, CSS, and JS files using the DOM, event listeners, and `localStorage`.

**[Live demo](https://abeeraalam1.github.io/SuperSimpleDev-JavaScriptCourse/12r-rock-paper-scissor.html) **
## Projects

### ✊✋✌️ Rock Paper Scissors — [`12r-rock-paper-scissor.html`](12r-rock-paper-scissor.html)
The project that runs through the whole course. The final version has:
- Emoji move buttons and a running score of wins, losses, and ties
- Score saved in `localStorage`, so it survives a page refresh
- **Auto Play** mode where the computer plays itself every second (the button toggles to *Stop Playing*)
- Keyboard shortcuts: `r` rock, `p` paper, `s` scissors, `a` auto play, `Backspace` reset score
- A "Are you sure?" confirmation before the score is reset

Earlier versions (`06-`, `07-`, `09-`, `10-`, `12-rock-paper-scissor.html`) show how it was built step by step.

### ✅ Todo List — [`12-todo-list.html`](12-todo-list.html)
Add tasks with a due date, delete them, and keep them after a refresh with `localStorage`. The lesson 11 version is in `11-todo-list.html`.

### 🧮 Calculator — [`10-exercise-calculator.html`](10-exercise-calculator.html)
A button calculator that shows the expression and result on the page. Earlier versions: `05-calculator.html`, `08-calculator.html`, `09-exercise-9j.html`.

### Smaller projects
- **YouTube Subscribe button** and **Amazon shipping calculator** — `10-project-dom.html`
- **Cart quantity** counter with limits — `05-`, `06-exercise-6k-i`, `07-cart-quantity.html`, `09-exercise-9i.html`
- **Toggle buttons** — `10-exercises-10c.html`

## Lessons covered

| Lesson | Topic | Files |
| --- | --- | --- |
| 4 | HTML & CSS review | `04-website.html`, `exercise4j.html` |
| 5 | Numbers, strings, variables | `05-*.html` |
| 6 | Booleans and `if` statements | `06-*.html` |
| 7 | Functions | `07-*.html` |
| 8 | Objects, JSON, `localStorage`, references | `08-*.html` |
| 9 | The DOM | `09-*.html` |
| 10 | CSS with the DOM, `classList`, separate JS/CSS files | `10-*.html`, `scripts/10-*`, `styles/10-*` |
| 11 | Arrays and loops | `11-*.html`, `scripts/11-*` |
| 12 | Advanced functions: arrow functions, `setInterval`, `addEventListener`, keyboard events | `12-*.html`, `scripts/12-*` |

Many of the lesson files have no visible page — open the browser's **DevTools console** to see their output.

## Running it

No install or build step:

```bash
git clone https://github.com/abeeraalam1/SuperSimpleDev-JavaScriptCourse.git
cd SuperSimpleDev-JavaScriptCourse
```

Open any `.html` file in your browser — start with `12r-rock-paper-scissor.html` or `12-todo-list.html`. The VS Code **Live Server** extension gives you auto-reload while editing.

## Folder layout

```
├── NN-*.html     # Lesson files, prefixed with the lesson number
├── scripts/      # JavaScript for the bigger projects (lessons 10–12)
├── styles/       # CSS for the bigger projects
└── *-emoji.png   # Rock, paper, and scissors images
```

## Credits

Course and exercises by [SuperSimpleDev](https://supersimple.dev/).

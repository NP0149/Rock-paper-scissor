# Rock-paper-scissor Game

A simple **Rock Paper Scissor game** built using **HTML, CSS, and JavaScript**.

The game allows the user to choose rock, paper, or scissor. The computer randomly selects a choice, and the winner is calculated. The score is saved using **Local Storage**, so it remains even after refreshing the page.

---

## 🚀 Features

- 🪨 Rock selection
- 📄 Paper selection
- ✂️ Scissor selection
- 🤖 Random computer choice generation
- 🏆 Win, Lose, and Tie score tracking
- 💾 Score persistence using Local Storage
- 🔄 Reset button to clear the score
- 🖼️ Displays both:
  - User's selected image
  - Computer's selected image

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript
- Browser Local Storage

---

## 🎮 How to Play

1. Open `index.html` in your browser.
2. Click on any option:
   - Rock
   - Paper
   - Scissor
3. The computer will randomly choose its option.
4. The result will be calculated:
   
### Rules

| User | Computer | Result |
|---|---|---|
| Rock | Rock | Tie |
| Rock | Paper | Lose |
| Rock | Scissor | Win |
| Paper | Rock | Win |
| Paper | Paper | Tie |
| Paper | Scissor | Lose |
| Scissor | Rock | Lose |
| Scissor | Paper | Win |
| Scissor | Scissor | Tie |

---

## 💾 Local Storage

The game stores the score in browser local storage.

Example:

```javascript
localStorage.setItem(
    'score',
    JSON.stringify(score)
);

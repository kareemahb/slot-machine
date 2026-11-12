# 🎰 Slot Machine
 
A simple three-reel slot machine built with plain HTML, CSS, and JavaScript. Pick a bet, spin the reels, and watch your balance go up or down.
 
> Build a simple slot machine with a minimum of 5 items per reel and 3 reels. The user should be able to bet min or max and have their total update.
 
🔗 **Live Demo:** [kareemahb.github.io/slot-machine-2019-week05](https://kareemahb.github.io/slot-machine/)
 
![Slot machine with three reels, balance and bet display, and Bet Min, Spin, and Bet Max buttons](image.png)
 

 
## ✨ Features
 
- **3 reels with 5 symbols each**: 🍒 🍋 🍇 ⭐ 💎
- **Bet Min or Bet Max**: switch between a $1 and a $10 bet
- **Live balance**: you start with $100, and the balance updates after every spin
- **Payouts**:
  | Result                  | Payout       |
  | ----------------------- | ------------ |
  | 3 matching symbols 🎉   | 10× your bet |
  | 2 matching symbols      | 2× your bet  |
  | No match                | You lose your bet |
- **Clear messages** after each spin, plus a warning when your balance is too low for the bet

 
## 🔍 How It Works
 
1. **Bet Min** sets the bet to $1 and **Bet Max** sets it to $10
2. **Spin** checks that you can afford the bet, then subtracts it from your balance
3. `getRandomIcon()` picks a random symbol for each reel
4. The app checks for 3 matches, then 2 matches, adds any winnings, and shows a message

 
## 🛠️ Tech Stack
 
- HTML5
- CSS3
- JavaScript (DOM manipulation, event listeners, `Math.random()`)
No frameworks, dependencies, or build tools.
 

 
## 📁 Project Structure
 
```
slot-machine/
├── index.html   # Balance, bet, reels, and buttons
├── style.css    # Slot machine styling
├── main.js      # Betting, spinning, and payout logic
└── image.png    # README screenshot
```
 

 
## 🚀 Getting Started
 
Try it live on **[GitHub Pages](https://kareemahb.github.io/slot-machine/)**, or run it locally:
 
```bash
git clone https://github.com/kareemahb/slot-machine.git
cd slot-machine
```
 
Open `index.html` in your browser, or use the **Live Server** extension in VS Code.
 

 
## 💡 What I Learned
 
- Tracking app state (balance and bet) in variables and keeping the page in sync
- Picking random items from an array with `Math.random()` and `Math.floor()`
- Writing win conditions with `if`/`else if` and comparison operators
- Guarding against invalid actions, like betting more than the balance

 
## 👩‍💻 Created By
 
**Kareemah Bahaadur**
 [GitHub](https://github.com/kareemahb)

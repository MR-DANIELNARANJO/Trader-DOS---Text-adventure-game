# TraderDOS, a command line JavaScript application

## 1. Running this application

* `git clone` this repo.
* Open up the app in VSCode or a similar IDE.
* run `npm install` to install any dependencies this project uses.
* run `npm install chalk` to install chalk.
* run `node TraderDOS.js` and have some fun.

## 2. Dependencies

`require` package is used in this application to read in user input.

```npm install require```

```javacript
const chalk = require('chalk')
const readlineSync = require('readline-sync')
```

## 3. Game Structure

Check the game structure in this `Trello`  [board](https://trello.com/b/zTBYt0qg/trader-dos-game) 

### TraderDOS control flow

* The Game requires a full screen and ask the user to maximize the command shell
* TraderDOs initial screen displays a Menu with 3 options `1. Instructions` `2. Start trading` `0. Cancel`
#### 1. Instructions

* The game display a short description of Forex trading and let the user begin a simulated trade
* The user has 3 options `1. Buy` `2. Sell` `0. Cancel`

#### 2. Start Trading

* The user enters a name and the game begins, with a greeting and a new balance of ` $ 10 500 `
* The user can choose from a variety of derivatives as `Stocks` `Forex` `Crypto`
* The user can `1. Buy` `2. Sell` `0. Cancel`
* TraderDOS displays the current balance after each transaction and the fee for the broker `1%`
* If the user runs out of money is able to sell the position and claim a `Win` or a `Loss`
* The user is prompted to restart the game

## 4. TraderDOS

![TraderDOS-Game](./TraderDOS.gif)

## Bonus Features

If cloning this repo or working on the TraderDOS implementation, please feel free to add aditional TraderDOS features like being able to make a deposit at the begining or the option to buy more than one derivative at the same time.

The game could be more interactive if some stories are added, for example the introduction of characters as `Jamie Dimond` The Big Corporate Banker who manipulates the prices on a daily basis, OR `Janeth Yellen` who has the power of increse or decrese interest rates at will, pushing up or down prices in seconds.

Enjoy coding.

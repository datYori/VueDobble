# Dobble

Dobble is a browser game adaptation of the Dobble card game (Spot It! in the US). Players are dealt two cards with symbols on them, and have to choose the matching pair of symbols. The aim of the game is to make as many matches as possible within the time limit. 

Dobble was built over the course of five days in a team of four developers. The front end is built with Vue, and the back end is an Express server with a MongoDB database.

---

## Prerequisites

Install Node.js and MongoDB with Homebrew:

```
brew install node
brew install mongodb-community
```

---

## Running the App

### Server

Navigate to the `server` directory and then:

```
npm install
npm run seeds
npm start
```

The server runs on `localhost:3000`.

### Client

Navigate to the `client` directory and then:

```
npm install
npm run serve
```

The client runs on `localhost:8080`.

---

## How to Play

* If this is your first time trying the game, first take a look at the Tutorial accessible from the main menu, which explains the rules of the game.

* When you're ready to start the round, click "Start Game".

* As soon as the game board loads, you will see two circular cards, each with six symbols on them. There will be exactly one matching pair between the two cards. Find the matching symbols, and click on them on each card to match them.

* If you are correct, you score one point, and are dealt a new pair of cards. If not, you stay on the same pair of cards, and can guess again.

* You're under a time limit! Try to score as many points as you can before the time runs out.

* If you want to exit the game before your round ends, you can click the "Main Menu" button in the top right corner.

* When time is up, you will see a game over screen. Here, you can enter your name and click "Save" to save your score to the database. Whether you do so or not, you can click "Restart" to begin a new round, "High scores" to see the list of high scores stored in the database, or "Main menu" to go back to the main menu.

* The High Scores page can also be accessed from the main menu.

---

## Learning Points

This project was our first software development project working in a team, so we encountered a lot of learning points—both for working in a remote team and for the code itself. Key learning points include:

* event handling and data flow in Vue;

* using timers (and the importance of clearing them...);

* RESTful API creation using Express and MongoDB;

* randomisation of imported data; and

* how to collaborate as a remote team using Kanban and pair programming.

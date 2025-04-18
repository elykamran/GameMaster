<p align="center">
  <img src="https://github.com/Delaford/game/raw/master/src/assets/github/logo.png"/>
</p>


  
  **July 2022 update**: beta demo available at https://beta.delaford.com/
  
  Let me know your interest on the [GitHub discussions thread](https://github.com/delaford/game/discussions/152)!
</div>

<p align="center">
  <strong>Welcome to Delaford. An online, 2D medieval game using JavaScript and HTML5.</strong>

  <img width="704" alt="Game screenshot" src="https://github.com/delaford/game/blob/master/src/assets/github/readme_hero.png">
</p>

## Getting Started

First, fork the repository. Then, go into your favorite terminal.

    git clone git@github.com:YOUR_USERNAME/game.git
    cd game
    npm install
    npm run serve

> `npm run serve` will start the development server and watch for changes on the client-side code inside the `src` folder and otherwise elsewhere applicable.

Now, while still inside the `game` folder, open another terminal session in that same location. Type and run `npm run dev:node`. This will start the Node.js game server.

> If you want to debug, type `npm run ndb`. `ndb` is Google Chrome's Node Debugging tool which allows Node.js programs to be easily debugged and see all its context and variables. Highly recommended for a much easier time.

Now you may visit `http://localhost:8080` to login and start developing!

For a better time, make sure to join the [Discord channel](https://discord.gg/nkZnHvD) to talk to other developers for help and exclusive dicussions!

> Please be aware of a [possible scam in regards to Delaford](https://github.com/delaford/game#possible-scam-notice) that promises money for testing or similar action.

## Contributing

Please check out our [CONTRIBUTING.md](https://github.com/Delaford/game/blob/master/.github/CONTRIBUTING.md) guide on how you can actively participate in the development of this medieval game. It's pretty easy and fun!

## Systems and Engines

Here are the types of things I will be adding as a minimum viable product (alpha). Not too over the top but enough to cover the basics until more is added. Each section links to a project which will contain its sub-tasks within.

### What does a checkmark mean?

When an item is checkmarked, it means the basic foundation is in place but not necessarily complete. For example, Inventory is checkmarked but it currently only supports weapons. You can help fix that.

- [Player](https://github.com/Delaford/game/projects/1)
  - [x] Walking / pathfinding
  - [x] Context-menu / Actions
  - [ ] Health and stats
  - [x] Inventory
  - [x] Character wear
  - [ ] Your first quest
- [User Interface](https://github.com/Delaford/game/projects/2)
  - [x] Inventory tab
  - [ ] Quests tab
  - [x] Chatbox (for players and actions)
  - [x] Character wear tab
  - [x] Overall look &amp; feel
- [NPC](https://github.com/Delaford/game/projects/3)
  - [x] Trading (Shops)
  - [ ] Dialog Interaction
  - [x] Walking around
  - [x] Banking
- [Monsters](https://github.com/Delaford/game/projects/3)
  - [ ] Battle System
  - [ ] Looting
  - [ ] Spawning
- [Networking](https://github.com/Delaford/game/projects/5)
  - [x] Players see each other
  - [x] Non-playable characters
  - [ ] Monsters
  - [ ] Player trading
  - [x] Items
- World
  - [x] Respawn system
  - [ ] Player versus Player
  - [ ] Resource skills
    - [x] Mining
    - [ ] Smithing (Almost finished)
    - [ ] Fishing
    - [ ] Cooking

Once all of these items are checked, Delaford will be stable without breaking changes. But for the time being, please jump in and help add some of these features -- if you'd like!


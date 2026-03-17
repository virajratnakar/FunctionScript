🧠 FunctionScript
<h3 align="center" style="color:#7c3aed;">A Lightweight Browser-Based Scripting Language</h3> <p align="center"> Build UI, interactions, and mini apps — instantly ⚡ </p>
<p align="center"> <a href="https://virajratnakar-dev.github.io/my_first_code/"> <img src="https://img.shields.io/badge/🚀%20Live%20Demo-Click%20Here-00c853?style=for-the-badge"> </a> <img src="https://img.shields.io/badge/Status-Active-success?style=for-the-badge"> <img src="https://img.shields.io/badge/Made%20With-JavaScript-yellow?style=for-the-badge&logo=javascript"> <img src="https://img.shields.io/badge/UI-Glassmorphism-7c3aed?style=for-the-badge"> <img src="https://img.shields.io/badge/License-MIT-blue?style=for-the-badge"> </p>
🌐 Live Playground

👉 Try FunctionScript in your browser
🔗 https://virajratnakar-dev.github.io/my_first_code/

⚡ What is FunctionScript?

FunctionScript is a mini scripting language that runs entirely in the browser.

Instead of writing HTML + JS, you write:

button(Click me, notify(Hello))
text(Welcome to my app)

✨ And it instantly creates a working UI.

🚀 Features Overview
Feature	Description
🧾 Simple Syntax	Function-based commands, easy to learn
🎨 UI Generation	Buttons, inputs, cards, layouts
🧠 Built-in Logic	Lists, randomness, timers
🎮 Game Engine	Built-in mini RPG system
⚡ Live Execution	No reload, instant output
🧪 Example Code
🔹 Basic UI
title(My App)
text(Hello World)
button(Click me, notify(Hi!))
🔹 Input + List
input(Add task, addTask())
list(tasks)
🔹 Fun Effects
rainbow(Hello World)
emoji()
typewriter(This is cool!)
🔹 Pokémon Generator
summonPokemon()
list(pokemon_log)
🎮 Game Engine (Built-in)

Enable the game system:

enable(game)
startGame()
attack()
Game Features
Feature	Description
⚔️ Combat	Attack enemies
❤️ Health System	Player & enemy HP
📜 Logs	Real-time game log
🎯 Score	Track progress
📖 Core Commands
🧾 Text & Formatting
Command	Example
text	text(Hello)
title	title(My App)
bold	bold(Important)
italic	italic(Text)
🎨 UI & Layout
Command	Example
button	button(Click me, notify(Hi))
input	input(Add task, addTask())
card	card(Title, Description)
row	row(text(A), text(B))
col	col(text(A), text(B))
⚙️ Logic & Utilities
Command	Example
random	random(1,10)
repeat	repeat(3, emoji())
timestamp	timestamp()
🎉 Effects
Command	Example
rainbow	rainbow(Text)
emoji	emoji()
typewriter	typewriter(Hello)
shake	shake(Wow)
📋 Lists & Data
Command	Example
list	list(tasks)
addTask	addTask(Buy milk)
count	count(tasks)
🖥️ System
Command	Example
copy	copy(text)
paste	paste()
fullscreen	fullscreen()
⌨️ Controls
Key	Action
Ctrl + J	Run script (Windows/Linux)
Cmd + J	Run script (Mac)
🏗️ How It Works
Internal State
Variable	Purpose
FP_LISTS	Stores dynamic lists
FP_FEATURES	Feature toggles
FP_SIMPLE_GAME	Game engine state
📂 Project Structure
📁 FunctionScript
 ├── index.html   # Full engine (HTML + CSS + JS)
 └── README.md
⚠️ Limitations

❌ No advanced parser (limited nesting)

❌ No sandboxing (runs in browser)

❌ Basic error handling

⚠️ Still evolving language

🌱 Roadmap

 Advanced parser (nested functions)

 Save/load scripts

 Syntax highlighting editor

 Plugin system

 Custom user functions

 Multiplayer playground

🤝 Contributing

Want to improve FunctionScript?

1. Fork the repo
2. Make changes
3. Submit a PR 🚀
📜 License

MIT License

👨‍💻 Author

Viraj Ratnakar

💡 Idea Behind This

Instead of writing:

<button onclick="window.open('https://google.com')">Open</button>

You write:

button(Open Google, open(https://google.com))

✨ Simpler. Faster. More fun.

⭐ Support

If you like this project:

⭐ Star this repo
🚀 Share it with others

# game-launcher
An executable that launches a game via a url (like through an epic url).
game-launcher.exe "epic.something://1232412/" "game_executable_name"

## background
This is based on the guide from https://seanzwrites.com/posts/how-to-play-epic-games-on-steam-and-steamlink/.

# what do you need?
- exe filename (without ".exe")
  - run the game
  - open task manager and find your game
  - browse the location of your game's process
  - copy the name of the executable (without ".exe")

- shortcut url
  - in epic, create a desktop shortcut for your game
  - go to that shortcut's properties and copy the url

# how to use?
- clone this repo
- build the project
```
dotnet build
```
- locate game-launcher.exe and run with url and filename
```
./bin/Debug/net6.0/game-launcher.exe "URL_FIRST" "EXE_NAME"
```

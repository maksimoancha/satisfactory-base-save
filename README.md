# Satisfactory game save file

Repository include save file with `.sav` extension for game __Satisfactory__.

### How to use

  First, you need to clone repo by command:
  ```sh
  $ git clone https://github.com/maksimoancha/satisfactory-base-save.git
  ```
  Then open repo folder and copy file __supermegabase.sav__ to folder with game saves: `%localappdata%\FactoryGame\Saved\SaveGames\common\`. 
  Create `...\common\` directory if it didn't exist.
  
  ### Hot to get save file after own game
  
  After you copied save file to saves folder and start it in game, new generated folder will apear in directory `\SaveGames\` . Name of this new folder generated by your EpicLauncher UserId and will be uniq, like this: *47aa8a649c844c2cb46948896ec69b5b*. Updated with your improves save file will apear in this new folder but still have previous name: *supermegabase.sav*. Backup this file for share or anything else.
  
  ### How to propose your changes to this repo?
  
  You can propose your own changes in game save file(new buildings/optimisation/etc.) by putting a pull request for [me](https://github.com/maksimoancha12).
  To make it:
  - Clone repo
  ```sh
  $ git clone https://github.com/maksimoancha/satisfactory-base-save.git
  ```
  - Create and switch branch for you changes
  ```sh
  $ git checkout -b your-branch-name
  ```
  - Replace save file with your own file(can use GUI directory manager), commit and push changes.
  ```sh
  $ git add . & git commit -m "Your commit text"
  ```
  - Create pull request
  ```sh
  $ git request-puuuuuuuuullllllllllllllllllllllllll
  ```

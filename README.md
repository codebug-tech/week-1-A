# Intro to the TERMINAL

| Commands                            |      What They Do                                  |
|-------------------------------------|----------------------------------------------------|
| `mkdir directory_name`              | Makes a new directory                              |
| `touch file_name.extension`         | Creates a new file                                 |
| `ls`                                | Lists everything in the directory                  |
| `cd directory_name`                 | Changes to the given directory                     |
| `cd ..`                             | Moves one level up from the current directory      |
| `pwd`                               | Prints the directory you are currently in          |
| `rf -rf directory_or_file_name`     | Deletes everything in the given directory or file  |
| `mv directory_or_file new_location` | Moves a directory or file to a new location        |
| `cp directory_or_file new_location` | Copies a directory or file to another location     |
| `subl .`                            | Opens the current directory in Sublime             |

## Let's build a house 
1) Using the `cd` command navigate to your Desktop
2) Make a new folder called `house`
3) Navigate into your `house` folder
4) Make four folders inside your `house` called: `kitchen`, `bathroom`, `bedroom`, and `living_room`
5) Navigate into your `kitchen` and make four files called: `oven.txt`, `sink.txt`, `fridge.txt`, and `pantry.txt`
6) Go back to the `house` folder
7) Go into the `bedroom` and make four files called: `bed.txt`, `dresser.txt`, `lamp.txt`, and `closet.txt`
8) Go back to the `house` folder
9) Go into the `bathroom` and make three files called: `toilet.txt`, `shower.txt`, and `sink.txt`
10) Go back to the `house` and use `ls` to see what is in that folder. (You should see `kitchen`, `bathroom`, `bedroom`, and `living_room`)

### Now let's make this house a little WiLd AnD cRaZy
11) We are going to remodel the `kitchen`. So we need to move a few things into the `living_room`:
    * Go into the `kitchen`
    * Use `mv` to move the `oven` into the `living_room`
    * Use `ls` inside the `kitchen` to make sure the `oven` is gone
    * Go into the `living_room` and use `ls` to make sure the `oven` has been moved there
    * Now do the same thing with the `fridge`
12) Our contractor needs a lamp in the `kitchen`. Move the `lamp` we have in the bedroom into the `kitchen`
13) The contractor wants to demo the whole `kitchen` from the `house` folder use `rm -rf` to delete the `kitchen` folder
13) Lastly, put a `couch.txt` and a `tv.txt` in the `living_room` and enjoy some relaxation after all of your hard work!

#### Extension
14) Use subl to open `closet.txt` in Sublime. 
15) Once you've opened the file in Sublime, type the phrase "Scary Monster" in the file. 
16) Save and close the `closet.txt` file. 






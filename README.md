# Influx
#### Influx is a game developed in JavaScript. The UI is created with HTML and [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS).

Goal of the game is to develop quick addition and subtraction capabilities in children of the age group 5 to 12.

The project can be viewed [Influx](https://ndkshr.github.io/influx).

> #### The project is still under construction!

---

## The important things to be achieved.
* #### There must be one single page called stage, that acts as a interface/template to all the levels with the game rules written in the levelx.js file for that particular level.
* The **report.html** page needs an update.
  - Display the username, age, score, hits and miss.
  - Button to go back to the Quit game (use red color or bootstrap danger for the button).
* The **index.html** needs these updates.
  - Function for the mute button to funtion.(_Sounds have not been added yet_)
* #### **GamePlay** updates required:
  - Gun animation should be smooth instead of abrupt changes in position(linear transition required)


---

## Important files and expected structure of the project files

Though, all files are inside one folder, they have to be structured. The **index.html** file is the only one expected to be in the root directory of the project.

Each levels should have the same structure but must differ in their problem complexity. The levels are written inside the **levelx . html** (**x** stands for the level number), and it also has a levelx.js file corresponding to it.

##### All the level files html and js and css if any for a particular level are supposed to be put together in one folder called the *Levels*.


---

## Instructions for contribution

The contributors are requested to create a new branch and work on that fork instead. Test the working of their branch and then submit a PR request to the master branch.

---

Created and maintained by [@ndkshr](www.ndkshr.ml)

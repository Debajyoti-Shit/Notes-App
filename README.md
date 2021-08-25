# Notes-App(NodeJS Mini Project)

make a notes taking app which takes command from the terminal and performs the following functions:

## Add note 
->Requires user to enter Title and Body of the note and adds the note to our databse (json file)
## Remove note 
-> 
Requires user to enter the Title of the note they want to remove and removes that note
## List notes 
->
Lists the title of all the notes present
## Read note 
-> Requires user to enter the title of the note they want to read and displays the body of that note on the terminal

### Add note 


some example

```bash
node app.js add --title="list" --body="Code, Game, Sleep"
node app.js add --title="My title2" --body="body2"
node app.js add --title="Friends" --body="Susan, Andy, Matt, Ana"
node app.js add --title="My title3" --body="my Body3"
node app.js add --title="My hobbies" --body="web dev, coding, problem solving"
node app.js add --title="My hobbies" --body="web dev, coding, problem solving"
```
![alt text](https://github.com/Debajyoti-Shit/Notes-App/blob/main/Screenshot%20(65).png)



### Remove note 
```
node app.js remove --title="My title3"
```
![alt text](https://github.com/Debajyoti-Shit/Notes-App/blob/main/Screenshot%20(66).png)

### List notes 
```
node app.js list
```
![alt text](https://github.com/Debajyoti-Shit/Notes-App/blob/main/Screenshot%20(67).png)


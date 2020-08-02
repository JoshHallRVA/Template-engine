As a manager<br>
I want to generate a webpage that displays my team's basic info<br>
so that I have quick access to emails and GitHub profiles<br>

he dependencies are, jest for running the provided tests, <br>
and inquirer for collecting input from the user.<br>

The file Structure is:<br>

lib/ // classes and helper code<br>
output/ // rendered output<br>
templates/ // HTML template(s)<br>
test/ // jest tests<br>
Employee.test.js<br>
Engineer.test.js<br>
Intern.test.js<br>
Manager.test.js<br>
app.js // Runs the application<br>

User input<br>
The project must prompt the user to build an engineering team. An engineering<br>
team consists of a manager, and any number of engineers and interns.<br>

Roster output<br>
The project must generate a team.html page in the output directory, that displays a nicely formatted team <br>roster. Each team member should display the following in no particular order:<br>

Name<br>

Role<br>

ID<br>

Role-specific property (School, link to GitHub profile, or office number)<br>

![](inf.png)

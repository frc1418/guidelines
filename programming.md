# 1418 Programming Guidelines
This list contains general rules and regulations to be applied for all code written on this organization for Team 1418. Please don't write team code that violates these regulations without good reason. If you have write access to team repositories, please don't merge pull requests that break these rules.

## Code
* All code (and pull request discussion, etc.) must be PG. All code is eventually public and looked at by many other teams. Showing off a repository full of cuss words is bad PR and should be avoided.
* All competition repositories should be named [year]-[purpose]. For example, "2016-robot" for the 2016 robot code, or "2015-UI" for the 2015 User Interface.
    * Non-competitive repositories don't need to follow this standard. For example, if you create a tool that isn't bound to any one competition, you can name it anything you see fit, like [pybasictraining](https://github.com/frc1418/pybasictraining), [Victiscout](https://github.com/frc1418/Victiscout), or [RobotRecorder](https://github.com/frc1418/RobotRecorder).
* Use detailed comments in all code, written in proper English. Anyone on the team with even mediocre knowledge of the language the code is written in should be able to read your comments and have a good understanding of what the code does and why. A good rule of thumb is *what*, *how*, and *why*. Comment *what* the class is used for, *how* a method accomplishes it's goal, and *why* you do specific lines of code. There is no need to explain simple code such as `x + = 1 #Increment x`. These comments actually distract from the code and make it harder to read
    * Furthermore, write detailed TODOs wherever you think of something that could be improved (if you aren't able to improve it at the moment.) For example, in JavaScript:

            // TODO: Make button move better

        Or, in Python:


            # TODO: Test this autonomous at a slower speed. Normal Priority
            # FIXME: Autonomous no longer drives. High Priority
        To view a list of `TODO`s,  `Window`->`Show View`->`Tasks` while in Eclipse. Label tasks `FIXME` for higher priority.

* Always follow style guides and best practices. In our code, we like to follow these rules


  |Type | Style | Example|
  |:------------------------:|:-:|:-:|
  | Class Names | CapitalizedWords |ModularAutonomous |
  | Variables | lowercase\_with\_underscore | elevator\_position |
  | Methods | lowercase\_with\_underscore <br> \_leading\_underscore\_for\_private | get\_gyro <br> \_detect\_position\_index|
  | Spaces | 4 Spaces, no tabs | You can tell eclipse to put in 4 <br>spaces instead of tabs|
  | Modules | lowercasewords | shootball.py |
  | Folders | lowercasewords |  automations |

* For anything else consult the [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008)

* For web languages (HTML/CSS/JS), follow the [Viget FED Best Practices](https://github.com/greypants/FED-docs/blob/master/Best-Practices.md).
* Before being publicized at the end of the season, all repositories should have a `README.md` markdown file explaining their purpose, how the code was used during the season, and how those interested can make use of the code themselves.
    * At the top of each README, a short title should be present saying what the repository is. For example, "2016 Robot Code" or "2015 User Interface".
    * Underneath the title, a set of links should be present linking to the other main repositories used that season.
    * At the end of the README should be a list of authors who contributed to the repository.
    * An example of a good README can be found [here](https://github.com/frc1418/2016-robot/blob/master/README.md).
* Each public repository must additionally include a `LICENSE` file explaining how others are allowed to use our team code. You can use [this website](http://choosealicense.com) if you're not sure which license you should include on the repository. When in doubt, use MIT.

##Properties
In Java, attributes can be private, and sometimes have getters and setters. Python doesn't have private variables, so they can always be accessed just by referencing them, e.g. `x = class.var` and `class.var = 5`. This is very pythonic, and you want to use this as much as possible. 

Sometimes the variable you need isn't stored as a variable in the class. An example in the 2016 code is the gyro. Originally we had

```
def return_gyro_angle(self):
	return self.navx.getYaw()
```
but a more pythonic way of doing it would be to use a property

```
@property
def gyro_angle(self):
	return self.navx.getYaw()
```
now, you can access the gyro angle with just `self.gyro_angle`
You can use properties as a setter as well. Let's say you need to do more than assign a variable when you call a setter. 

```
@var.setter
def var(self, value):
	self._var = value
	self._boolean = True

##Testing and Deploying
pyfrc comes with builtin tests. These tests are to help you catch any errors in your code. To test code on its own, you can run `./robot.py test`. If you are deploying code to the robot, use the `deploy` argument. This will automatically test the code and deploy it. The code *will not* deploy if the tests don't pass. However, there are some situations when you want to bypass the tests and deploy the code. Likely scenarious are if the tests are failing in autonomous, but you want to run teleop. To bypass the tests:

`./robot.py deploy --skip-tests`

It's not a bad thing to skip tests, as long as you only do it in controlled situations.

## Miscellaneous
* Save a good reason not to, please use the portrait of yourself from [the Team Profiles page](http://1418.team/team) on our website as your GitHub user picture. You'll need to scale it up to 512x512 with [GIMP](http://www.gimp.org/downloads) or another photo editing tool.


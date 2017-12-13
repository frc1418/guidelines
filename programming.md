# 1418 Programming Guidelines
This list contains general rules and regulations to be applied for all code written on this organization for Team 1418.

Do not write code that violates these regulations. For those with write access to team repositories, do not merge pull requests which violate these rules.

## Code
* All code (as well as discussion on pull requests, issues, and elsewhere) must be PG. All team code is eventually publicized and may be viewed by other teams, judges, and other important persons. Promoting a repository full of cuss words is bad PR. Keep it clean.
* All competition repositories should be named [year]-[purpose]. For example, [2015-robot](https://github.com/frc1418/2015-robot), [2016-vision](https://github.com/frc1418/2016-vision), or [2017-dashboard](https://github.com/frc1418/2017-dashboard).
    * Non-competitive repositories don't need to follow this standard. For example, if you create a tool that isn't bound to any one competition, you can name it anything you see fit, like [VictiScout](https://github.com/frc1418/VictiScout), [tbapy](https://github.com/frc1418/tbapy), or [RobotRecorder](https://github.com/frc1418/RobotRecorder).
* Use detailed comments in all code, written in proper English.
    * Any experienced programmer should be able to read your comments and understand your code.
    * A good rule of thumb is to include *what*, *how*, and *why*. Comment *what* a class is used for, *how* a method accomplishes its goal, or *why* specific lines of code are included.
    * Do not write comments for simple code like `x += 1 # Increment x`. Unnecessary comments can distract from the code and make it harder to read.
    * Furthermore, write detailed TODOs wherever you think of something that could be improved (if you aren't able to improve it at the moment). For example, in JavaScript:
    ```js
    // TODO: Make button automatically hide
    ```
	for a lower priority fix, or
    ```js
	// FIXME: Camera feed broken
    ```
	for a higher priority fix.
    In Python:
    ```py
    # TODO: Test this autonomous at a slower speed.
    # FIXME: Autonomous no longer drives.
    ```

* Always follow style guides and best practices. In Python code, follow these rules:

  |Type | Style | Example|
  |:------------------------:|:-:|:-:|
  | Class Names | CapitalizedWords |ModularAutonomous |
  | Variables | lowercase\_with\_underscore | elevator\_position |
  | Methods | lowercase\_with\_underscore <br> \_leading\_underscore\_for\_private | get\_gyro <br> \_detect\_position\_index|
  | Spaces | 4 Spaces, no tabs <br> Don't leave trailing whitespace, you may wish to guard against accidental trailing spaces by running `git config --global core.whitespace warn` | You can tell eclipse to put in 4 <br>spaces instead of tabs|
  | Modules | lowercasewords | shootball.py |
  | Folders | lowercasewords |  automations |

* For anything else consult the [PEP 8 Style Guide](https://www.python.org/dev/peps/pep-0008)

* For web languages (HTML/CSS/JS), follow the [Viget FED Best Practices](https://github.com/greypants/FED-docs/blob/master/Best-Practices.md).
* Before being publicized at the end of the season, all repositories should have a `README.md` markdown file explaining their purpose, how the code was used during the season, and how those interested can make use of the code themselves.
    * At the top of each README, a short title should be present saying what the repository is. For example, "2016 Robot Code" or "2015 User Interface".
    * Underneath the title, a set of links should be present linking to the other main repositories used that season. See current repositories for an example of what this means.
    * At the end of the README should be a list of authors who contributed to the repository.
    * An example of a good README can be found [here](https://github.com/frc1418/2016-robot#readme).
* Each public repository must additionally include a `LICENSE` file explaining how others are allowed to use our team code. Our team typically uses the MIT license. You can use [this website](http://choosealicense.com) if you're not sure which license you should include on the repository.

## Properties
In languages like Java, attributes can be private, and sometimes have getters and setters. Python doesn't have private variables, so they can always be accessed just by referencing them, e.g. `x = class.var` and `class.var = 5`. This is very "pythonic," and you should use this method as much as possible.

Sometimes the variable you need isn't stored as a variable in the class. An example in the 2016 code is the gyro. Originally we had

```py
def return_gyro_angle(self):
	return self.navx.getYaw()
```

but a more Pythonic way of doing it would be to use `@property`:

```py
@property
def gyro_angle(self):
	return self.navx.getYaw()
```

now, you can access the gyro angle with just `self.gyro_angle`.
You can use properties as a setter as well. Let's say you need to do more than assign a variable when you call a setter.

```py
@var.setter
def var(self, value):
	self._var = value
	self._boolean = True
```

Note that the method name is `var` but the variable is `_var`. This is very important, and it makes sense if you think about in terms of Java. In Java, you use setters with private variables, and in Python, a 'weak' private variable is denoted by a leading underscore. In reality this differentiates between the method and the variable in as little way possible.

## Testing and Deploying
`pyfrc` comes with built-in tests. These tests are to help you catch any errors in your code. To test code on its own, you can run `./robot.py test` or `python3 robot.py test`. If you are deploying code to the robot, use the `deploy` argument instead. This will automatically test the code and deploy it. The code *will not* deploy if the tests don't pass. However, there are some situations when you want to bypass the tests and deploy the code, for example if the tests are failing in autonomous, but you only want to run teleop. To bypass the tests:

`./robot.py deploy --skip-tests`

It's not always a bad thing to skip tests, as long as you only do it in controlled situations.

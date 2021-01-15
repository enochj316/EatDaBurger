# Eat-Da-Burger! 

## Overview

* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat. Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

* Each burger in the waiting area also has a `Devour it!` button. When the user clicks it, the burger will move to the right side of the page.

* Each `devoured` burger on the right side also has a `Remove` button to be deleted from the list and the internal database in the backend.

### Deployment and Availability

* Heroku
  * Live app - https://eatdaburgerjoyson.herokuapp.com/
    * Now it seems to be working ok after having changed to `JawsDB MySQL`. _it was constantly crashing and unavailable when using `ClearDB MySQL` and `pg`_ -- see [the details](README-heroku.md)
* GitHub
  * Repository - https://github.com/enochj316/EatDaBurger
Public Good simulation
======================
This is an interactive version of the Public Good game, where you can set the participation amount for each player before starting the animation.

## Optional setup
You may set the following `data-attributes` to the canvas to change content.
- `data-currency`: the currency sign used when displayed the amount of money - defaults to € 
- `data-multipler`: the multipler float appearing during the animation - defaults to 1.6
- `data-min`: the minimum amount a user can place - defaults to 0
- `data-max`: the maximum amount a user can place - defaults to 10

## API
To communicate with the animation, you have access to the namespaced module `window.publicGood`.
The following methods are available:
- `incrementPlayer1()`: increment first character's participation
- `incrementPlayer2()`: increment second character's participation
- `incrementPlayer3()`: increment third character's participation
- `incrementPlayer4()`: increment fourth character's participation
- `decrementPlayer1()`: decrement first character's participation
- `decrementPlayer2()`: decrement second character's participation
- `decrementPlayer3()`: decrement third character's participation
- `decrementPlayer4()`: decrement fourth character's participation
- `reset()`: set all character's participation to zero
- `start()`: start the animation process, displaying the characters participation at their current state

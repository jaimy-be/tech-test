# JAIMY TECH TEST #

## Good morning ! ##

  Here is a quick technical test (take it as a game) for Jaimy recruitment.
  The goal of this game is to understand the path of your brain when you solve issues :)
  It means that nothing is hard, but pay attention of the way you organize your code.


## GOAL AND RULES OF THE GAME ##

  Create some endpoints to solve each of the exercises
  You must use Sinatra (doc: (you choose) https://en.wikipedia.org/wiki/Frank_Sinatra OR https://github.com/sinatra/sinatra)
  Your code must stored in a class with the number of the exercice (ex: ExerciseOne, ExerciseTwo ...)
  Your class must at least have a class method called 'call' and be used like a service object

Ex.1 -
  Create an enpoint to beautify any number given in cents.
  679978789 cents is hard to read, but thanks to your code, it will return --> "€ 6.799.787,89"
  Some more examples:
  * 1         -->   "€ 0,01"
  * 100       -->   "€ 1,00"
  * 0         -->   "€ 0,00"
  * 234500    -->   "€ 2.345,00"
  * random    -->   "Price is not an integer"
  * -234566   -->   "€ -2.345,66"

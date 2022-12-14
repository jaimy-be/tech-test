# JAIMY TECH TEST #

## Good morning ! ##

  Here is a quick technical test (take it as a game) for Jaimy recruitment.  
  The goal of this game is to understand the path of your brain when you solve issues :).  
  It means that nothing is hard, but pay attention of the way you organize your code.  


## GOAL AND RULES OF THE GAME ##

  * Create some endpoints to solve each of the exercises
  * You must use Sinatra (doc: (you choose) https://en.wikipedia.org/wiki/Frank_Sinatra OR https://github.com/sinatra/sinatra)
  * Your code must stored in a class with the number of the exercice (ex: ExerciseOne, ExerciseTwo ...), and this class will be called within the endpoint.  
  * Your class must at least have a class method called 'call' and be used like a service object (ex: ExerciseOne.new(my_parameter).call)
  * The endpoints will be tested via Postman after running your ruby file: ```rb tech_test.rb``` 

Ex.1 -  
  Create an enpoint to beautify any number given in cents.  
  679978789 cents is hard to read, but thanks to your code, it will return --> "€ 6.799.787,89"  
  Don't try to humanize the integer, use your brain!

  Some more examples:
  * 1         -->   "€ 0,01"
  * 100       -->   "€ 1,00"
  * 0         -->   "€ 0,00"
  * 234500    -->   "€ 2.345,00"
  * random    -->   "Price is not an integer"
  * -234566   -->   "€ -2.345,66"
  The enpoind will be reachable via POST http://localhost:4567/ex_one/my_parameter (my_parameter will be the tested value)

Ex.2 -  
  Create an endpoint to know what are the preferencies of our team  
  You first need to fecth the data in https://jaimy-api.jaimy.be/api/test/tech_test/ex_two  
  Then return a string like 'Xavier likes to eat belgian food and to drink beer.'  
  The enpoind will be reachable via POST http://localhost:4567/ex_two/my_parameter (my_parameter will be the tested value)  
  If the parameter is not included in the keys of the data, your endpoint should return 'my_parameter not found' with the actual not found parameter.  

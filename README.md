# JavaExternal

## Task1 - [Shevchenko's poem(team task).](https://github.com/ShulzhenkoA/JavaExternal_team_tasks/tree/master/tasks/poem) [Draw a figure(team task).](https://github.com/ShulzhenkoA/JavaExternal_team_tasks/tree/master/tasks/geometrical.figures/src/com/java/external)


## Task2 - [GuessTheNumber (Gaming Java with MVC pattern)](https://github.com/ShulzhenkoA/JavaExternal/tree/master/JavaGaming/src/com/javaextetnal_shulzhenko/gaming/GuessTheNumber)
The program generates a random number from 0 (inclusive) to 100 (inclusive), which is proposed to guess the player with 6 attempts. Entering non-numbers and numbers outside the range is considered as an attempt. To exit the game, enter the 'quit' command.


## Task3 - [DroidsWar](https://github.com/ShulzhenkoA/JavaExternal/tree/master/DroidsWar)
* The **DroidsWar** program allows you to create droids of different models and strengths, giving them different weapons or equipping them with different armor, as well as create non-combat droids (for example, droids for repair) and simulate the battle between them. 

* **DWv0.4** The architecture of the program is built on OOP, MVC pattern, Strategy pattern, Factory pattern. To play **DroidsWar** you must create your new accont or use earlier created. Registration and logging to account as administrator allow you watch existing list of droids, create new droids or delete droids from list. Registration and logging to account as user allow you watch existing list of droids and make battle between choosed droids.

* **DWv0.5** There is i18n in **DroidsWar**. You can choose English or Ukrainian. There have been created Junit tests for programme.


* **DWv0.6** An engine has been added to the structure of the droids that allows them to act depending on energy. User and admin accounts recived oportunities to sort droid or search them depending different criteria. 

* **DWv0.7** Admin accounts recived oportunities to create additional 'Private Droids List', create/delete droids from it, sort driods in it. 'Private Droids List' works using droids serialization.

* **DWv0.8** The logging with log4j2 has been added in the program.  


## Task4 - [SearchigTool](https://github.com/ShulzhenkoA/JavaExternal/tree/master/SearchingTool)
The program allows you to process the search, parsing and sorting of words from all URLs added to the program URLs_DB file.


## Task5 - [WeatherApp](https://github.com/ShulzhenkoA/JavaExternal/tree/master/WeatherApp/)
The program allows you to display the current weather in the requested city and weather statistics from the requested cities using your OWM API key. To request the weather, enter your OWM API key and the desired city as command line arguments.

## Task6 - [MobileTariffs](https://github.com/ShulzhenkoA/JavaExternal/tree/master/MobileTariffs/)
The program allows :
 - validate xml file with mobile tariffs(resources/tariffs.xml) with xsd schema(resources/tariffs.xsd) using SAX;
 - transform tariffs.xml and create tariffs.html using XSLT;
 - create Java objects from tariffs.xml using StAX;
 - validate created Java objects using custom annotations and corresponding validator.
 This app works using patterns "Singleton", "MVC", "Command", "Facade". "Command" is implemented using lambda expressions in CommandsModel class. 

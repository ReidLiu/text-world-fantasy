Prerequisites
-------------

- [Python](https://www.python.org/). The version needed is 2.7.x (python 3 is not yet supported).


Game environment setting
--------------------------

1. Clone this repository.
2. Run `pip install -e .` 
3. Use `cd evennia/` to change the directory .  
4. Run `.\start.sh <n>` to start up `n` different game servers, that each server will use a different port.   
During server start, the username and password need to be provided. It needs to notice that you must make it matche the framework code (the defaults are root and root for both username and password)  
5. The `telnet localhost <gameport>` is used to connect to the game server. The default game ports start from 4001 for the first game server, 4002 for the next and so on. 
6. Login using the username and password you provided and then run the following command(s) to setup the game environment:  
   @batchcommand tutorial_world.build for the Fantasy world 
7. The game servers can be stoped by using `stop.sh`


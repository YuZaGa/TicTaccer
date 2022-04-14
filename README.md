# Django-TicTacToe


# TicTaccer
A Django based implementation of popular Tic Tac Toe Game. Uses Django Channels, Websockets and redis to connect to the other player.

<h2>Project snapshot</h2>
<img src="./tictac.gif?raw=true">



## Features
1. Simplistic creation of room code.
2. Real-time updates. 


<h2>Prerequisites</h2>
<code>See the requirements.txt file</code>

## Setup
1. Git Clone this project:
2. Create an python environment with ```python -m venv venv``` or ```virtualenv venv``` and activate it with (windows:```venv\Scripts\activate```, Mac/Linux:```source venv/bin/activate```.
3. Install required packages: ``` pip install -r requirements.txt ```
4. Create superuser
5. Run app: ``` python manage.py runserver ```
6. Then go to http://127.0.0.1:8000/home in your browser

Bonus - Publish it on Heroku.

https://codeburst.io/deploy-your-django-project-for-free-140d73a2c76b

The free tier of Heroku sleeps after 30 minutes of inactivity. Use Kaffiene (http://kaffeine.herokuapp.com/) to keep it awake. 

## To-Do
1. Deployment error fix over https. The project deploys but isn't able to connect over a secure connection and since Heroku uses https, the web socket fails to establish connection. [Possible fix could be using daphne](https://www.youtube.com/watch?v=zizzeE4Obc0&list=WL&index=10). 



## Addition and Modification
Due credit to people who have worked on different components of the project beforehand. **Gaurav**

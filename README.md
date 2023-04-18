# soccer
TEAMS

Team List               GET         http://127.0.0.1:8000/api/teams
Team List By Id         GET         http://127.0.0.1:8000/api/teams/1
Create teams            POST        http://127.0.0.1:8000/api/teams
Update Team             PUT         http://127.0.0.1:8000/api/teams/1
Delete Team             Delete      http://127.0.0.1:8000/api/teams/1


PLAYERS

Player List             GET         http://127.0.0.1:8000/api/players
Player List By Id       GET         http://127.0.0.1:8000/api/players/1
Create Player           POST        http://127.0.0.1:8000/api/players
Update Player           PUT         http://127.0.0.1:8000/api/players/1
Delete Player           Delete      http://127.0.0.1:8000/api/players/1
Player Based on Team    GET         http://127.0.0.1:8000/api/teams/{TEAM ID OR TEAM NAME}/players


REGISTER                POST        http://127.0.0.1:8000/api/register
Fields
name, email, password, confirm_password, role (default 1 for admin and 2 for user)


LOGIN                   POST        http://127.0.0.1:8000/api/login
Fields
email and password


NOTE
1. After Successful Login Token will be received.
2. The Token has to be passed as Bearrer Token in Authorization in all POST, PUT and DELETE request.

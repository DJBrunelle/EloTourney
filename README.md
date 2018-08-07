# Elo Tourney

## API
### Players
 
| Method | Endpoint        | Usage                  | Returns         |
| ------ | --------------- | ---------------------- | --------------- |
| GET    | /v1/players     | Get all players        | List of Players |
| GET    | /v1/players/:id | Get player with :id    | Player          |
| PUT    | /v1/players/:id | Update player with :id | --              |
| DELETE | /v1/players/:id | Delete player with :id | --              |
| POST   | /v1/players     | Create new player      | --              |

### Leagues
 
| Method | Endpoint        | Usage                  | Returns         |
| ------ | --------------- | ---------------------- | --------------- |
| GET    | /v1/players     | Get all leagues        | List of Leagues |
| GET    | /v1/leagues/:id | Get league with :id    | League          |
| PUT    | /v1/leagues/:id | Update league with :id | --              |
| DELETE | /v1/leagues/:id | Delete league with :id | --              |
| POST   | /v1/leagues     | Create new league      | --              |

### Tournament
 
| Method | Endpoint                  | Usage                      | Returns             |
| ------ | ------------------------- | -------------------------- | ------------------- |
| GET    | /v1/Tournaments           | Get all tournaments        | List of Tournaments |
| GET    | /v1/tournaments/:id       | Get tournament with :id    | Tournament          |
| PUT    | /v1/tournaments/:id       | Update tournament with :id | --                  |
| PUT    | /v1/tournaments/:id/start | start tournament with :id  | --                  |
| DELETE | /v1/tournaments/:id       | Delete tournament with :id | --                  |
| POST   | /v1/tournaments           | Create new tournament      | --                  |

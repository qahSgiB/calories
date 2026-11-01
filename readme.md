# *CalorieS*
CalorieS is website for tracking your daily calories and nutrients intake.
It offers setting goals and graph visualizations and statistics of the data.
It also has social aspect, users posts photos of their meals which can be viewed by their friends in a feed.

Some notable used technologies: TypeScript (both on backend and frontend), React, Prisma, TanStack Query.

The project was developed in a team of 4 people.
I was a main developer of the infrastucture, the lower layers of backend and frontend, and the profile functionality (login, sessions, friends functionality) both backend and frontend part.

## Running
### Prerequsities
Few prerequsities are required in order to run the application:
 - **node.js**: official installation guide: https://nodejs.org/en/download
 - **docker**: official web: https://www.docker.com/

### Configuration
Backend, frontend and databse are configured using configuration files.
In order for the application to run these files must created and configured.

List of the configuration files:
 - `db/db_password.txt`
 - `be/.env`
 - `fe/.env`

For each of these files there is a sample file. It is enough to copy the sample file and rename it, the default values are good enough to run the application.

### Start the application
Run `npm install` in `be`, `fe` and `shared` folders (each of them is separate node project):
```
npm install
```

Start the database (in `db` folder):
```
docker compose up
```

Start the backend (in `be` folder):
```
npm run start
```

Start the frontend (in `fe` folder):
```
npm run dev
```

## Origin
I developed this project as a submission to a web development course (PB138) at my university (MUNI).
